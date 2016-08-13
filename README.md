# taking_data

In this competition, you are going to predict the demographics of a user (gender and age) based on their app download and usage behaviors. 

The Data is collected from TalkingData SDK integrated within mobile apps TalkingData serves under the service term between TalkingData and mobile app developers. Full recognition and consent from individual user of those apps have been obtained, and appropriate anonymization have been performed to protect privacy. Due to confidentiality, we won't provide details on how the gender and age data was obtained. Please treat them as accurate ground truth for prediction. 

The data schema can be represented in the following chart:

gender_age
device_id
gender
age
group
events
event_id
device_id
timestamp
longitude
latitude
app_labels
app_id
label_id
label_categories
label_id
category
app_events
event_id
app_id
is_installed
is_active
phone_brand_device_model
device_id
phone_brand
device_model
File descriptions
gender_age_train.csv, gender_age_test.csv - the training and test set
group: this is the target variable you are going to predict
events.csv, app_events.csv - when a user uses TalkingData SDK, the event gets logged in this data. Each event has an event id, location (lat/long), and the event corresponds to a list of apps in app_events.
timestamp: when the user is using an app with TalkingData SDK
app_labels.csv - apps and their labels, the label_id's can be used to join with label_categories
label_categories.csv - apps' labels and their categories in text
phone_brand_device_model.csv - device ids, brand, and models
