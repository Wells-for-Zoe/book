# Flority Features

## General Information on Collection Logic
Flority data collection is centred around the capture of highly accurate geotagged photos and associated attributes. Therefore, the camera module will only display an image and allow data capture if the geospatial accuracy is below the systems-wide set threshold (e.g. less than 15m). While it may be annoying at times to have to wait few seconds to capture a photo it is the only way to ensure that captured data will be consistent between thousands of users.

Custom forms allow the collection of any additional attributes, comments and surveys if desired. These are usually directly associated and therefore attached to a previously captured GPS-Photo. These forms are co-created by the project administration and the greenhouse.Flority team.

Flority is supposed to be used in the field to collect actual tamper proof ground truth data. 
It will not allow to geotag or upload any previously captured images from your phone Gallery by design. 

## Installation
On your Android phone, scan this QR code or open this link (available soon) and download, install and Open Flority. 
It will prompt several warning messages. Always select the red circled Answer ![image](https://github.com/Wells-for-Zoe/book/assets/97762115/2ab90bdd-5784-4b5a-bb89-90af16760263) ![image](https://github.com/Wells-for-Zoe/book/assets/97762115/25e3f4bb-083c-4ace-93f7-b315fa2d08b1) ![image](https://github.com/Wells-for-Zoe/book/assets/97762115/c155dc36-de19-45e7-a3c6-8544259dce97)



## Compatibility 
Flority App currently is only compatible with Android devices

## Log in and User Account
The User Account for greenhouse. and Flority is identical as it is technically one single User Account used on both the web-Interface greenhouse. and the mobile App Flority. As soon as your Administrator invites you to the Platform you are required to change your Password. Please note that simple passwords like ABC12345 will not work and special case, number and capital and small letters must be used. Enter your Username and Password (both are case sensitive) ![image](https://github.com/Wells-for-Zoe/book/assets/97762115/6ed9dc8f-fe1c-447d-930f-b2319dc2bbc7)
![image](https://github.com/Wells-for-Zoe/book/assets/97762115/586f1fbf-ada4-4947-a8ed-bbc637dd6b90) ![image](https://github.com/Wells-for-Zoe/book/assets/97762115/6dce5ce2-4ed4-4e97-a739-c481e2838897)

## I don't have an Account
If you do not have an Account or your Account Details are wrong you should contact your respective Administrator/Superior who can create an Account for you if your organization is already registered in the system. If not reach out to info@flority.app. 
Even if you should not have an account you still have the option to use the App in the most basic variant to capture accurate GPS-Photos which are saved in your phone gallery (any sort of automatic upload to greenhouse. will not be available in this mode, as well as any custom forms which actually make the App powerful).
Should you get logged out occasionally please contact info@flority.app as this is not supposed to happen.
![image](https://github.com/Wells-for-Zoe/book/assets/97762115/7a8d9406-9edc-4d8f-abd8-72a1167d961a)


## Centralized Remote User Configuration
Flority App currently has no settings that can be customized in App by the user. This is by design to keep complexity minimal for the end user in the field but give the Project Administrator maximum flexibility while deploying hundreds of citizen science ground truth data collectors. It is technically possible to adjust each and any setting for each user or user group and the following settings can technically be adjusted. 
* Image Quality and Resolution in Megapixels
* Minimum required geospatial accuracy
* available tags
* available forms
* available Menu Options
* daily upload limits
* remote App deactivation

## Photo storage
Flority App creates two identical copies of each photo captured: One copy is stored in your regular phone gallery and you have full access to it, the other copy is hidden in a cryptographically sealed file location within Flority App and can not be manually deleted. This is necessary to ensure that submitted photos are always original and unaltered. 

## Training Mode (optionally available)
![image](https://github.com/Wells-for-Zoe/book/assets/97762115/5e73c7b4-a316-4066-a9ca-e14304a8007e)

A special Training Mode can be activated and it is - as the name suggests - only meant for purely Training data. IMPORTANT: TRAINING DATA WILL AUTOMATICALLY BE DELETED FROM THE SYSTEM AFTER 14 DAYS.
We know that people like the system so much that they demonstrate it to others all the time and suddenly random snapshots appear in the system. Please remind users to use training mode in these cases. It will always deactivate automatically after going back to the Main Overview Page to not use it accidentally. 


## Geospatial Accuracy
If your device does not yet have the required geopositional accuracy (which is defined by the Project or Organization Administrator) a warning message will appear. Should this message show up in the field for several minutes repeatedly please reach out to your project administrator and let us know which device and user name you are using as we could then decrease the accuracy threshold required. 
Android offers a minimum setting of 5m.
![image](https://github.com/Wells-for-Zoe/book/assets/97762115/185e0fde-4c74-48e2-9869-7ad82e143d74)

## tags

Tags help planting organizations to categorize images and data in their system. If you use our system to document not only planting activities but also things like community gatherings, site preparation then it can help to use these tags so while it is not mandatory we highly recommend it. Some tags will have Forms connected with it so for example the tag "Disturbance (Fire/Flood...) will have a Form with additional options to describe the situation as default.
![image](https://github.com/Wells-for-Zoe/book/assets/97762115/bb90be63-9cad-482a-a6b2-223bc4beecb1)


## forms

A form is usually co-designed by the Superior Project Developer and highly standardized to fit the criteria the project documentation protocol requires. Forms can include additional Options to add GPS-Photos (e.g. for Accounting Documentation it is possible and actually feasible to use Flority) as well as any sort of usual Form Options be it Multiple Choice, Numbers or written answers.  

## Automatic Upload = ON

During Field Data Collection the setting: Automatic Upload = ON automatically uploads all data captured should cellular data network be available. This can be useful for bulk-shooting of planting proof (e.g. seedlings planted along a road) and it helps to activate this feature to very inexperienced users to make sure that their field data will successfully submitted. 
Should network fail then it will automatically retried.


WARNING: Should you capture a private or sensitive photo by accident then Automatic Upload will push that to the server immediately nevertheless, so please be mindful of data privacy. Should you need to delete a photo from the greenhouse. system it is possible and described in the greenhouse tutorial.


WARNING: If a user captures a photo and uploads it immediately then Administrators can instantly derive the actual live geolocation of the person and might be able to follow you.


#### There are several reasons why it can be helpful to deactivate Automatic Upload:
* You do not want your Project Administrators to be able to track your live location? Just upload all photos from the field at once in the evening when in a safe place.
* A free Wifi network is available at the end of the field data recording activity and cellular data costs can thereby be saved by deactivating Automatic Upload
* Your phone battery is weak or has a low charge? Deactivating Auto Upload will save battery as no data will be shared via the App.
* With automatic upload it is not possible to review, delete or edit your photos before they are uploaded. Deactivating Automatic Upload gives you access to Gallery Functions.

## Automatic Upload = OFF:
Deactivating the Automatic Upload can have some benefits but it bears the risk that inexperienced users simply forget to submit photos. However it allows (optional setting) to access the internal Flority Gallery Functionality where photos can be reviewed, deleted, tags be edited and forms answered.
Any data captured will accumulate on your phone and not be deleted from the internal Flority storage, so if you were to never upload photos but keep capturing photos your storage might eventually run low. 


## Gallery Functionality (optional)
The Gallery within Flority App is only available if Automatic Upload = OFF. Images can be viewn near full screen by touching the double headed arrow for a brief moment. 

### Delete Images
Multiple images can be selected and deleted. This function can help inexperienced users to remove seemingly identical duplicates to avoid clogging the system with multiple near-identical datapoints. Deleting near-identical duplicates, blurry, incomplete or unwanted photos will save data on user-side and is thereby highly recommended.

### Tag Images
Should a user accidentally have used the wrong tag then it is possible on page two of the Flority Gallery to select multiple images and change their tag.

### Edit Forms
Should a comment or a form be associated and attached to an image then the form details can be altered at a later stage should the Automatic Upload be off. This can be helpful in the following scenarios:
* Some form answers can not be given at the specific moment maybe due to a local expert not being on site
* In bad weather conditions it can be helpful to postpone tedious comment writing to a place where there is no rain/wind or strong sunshine

#### Optional 
If all form answers are optional then the Form Icon is white and information can be given but also an image itself could be submitted without any additional attributes given.


#### Mandatory
If at least one form answer is mandatory then the form icon is red and Information must be entered before the corresponding image or Polygon can be uploaded or be submitted for upload.

### Confirm and Upload
### Change #tags



For example:
- Taking Photos
- Uploading Photos
- Filling out Forms
