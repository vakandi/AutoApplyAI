# AutoApply AI for Linkedin and Indeed

## Introduction

This project is a web application that allows users to apply to jobs on Linkedin and Indeed using their resume and cover letter. The application uses Selenium to automate the process of applying to jobs on Linkedin and Indeed. The user can upload their resume and cover letter to the application and the application will use the information in the resume and cover letter to apply to jobs on Linkedin and Indeed. The user can also specify the job title, location, and keywords for the jobs they want to apply to. The application will then search for jobs on Linkedin and Indeed that match the user's criteria and apply to them.

## Installation

No Installation necesarry, to use : 

Windows :
```
Run the AutoApplyAI.exe Application
```

Linux & MacOS :
```
Run ./AutoApplyAI Binary
```

## Environment variables

```
set LINKEDIN_EMAIL="" with your linkedin email if you want to use linkedin application
set LINKEDIN_PASSWORD="" with your linkedin password if you want to use linkedin application
set INDEED_EMAIL="" with your indeed email if you want to use indeed application
set INDEED_PASSWORD="" with your indeed password if you want to use indeed application
set CV_FILE="" or none at all if you want to use the linkedin default cv
set TEMPLATE_LETTER_FILE="" or none at all, if you want to use our default motivation letter
set CHROMEDRIVER_PATH="" or none at all, if you want to use the default chromedriver for linux 64bits
set API_KEY_NOTIF="" with your api key from PushAPI Android Notifications if you want to use the notification system to alert you if the loggin of linkedin or indeed failed or need a validation from you
```

# Android Notifications

To use the Android Notifications, you need to download the PushAPI app on your phone and create an account. Then, you can get your API key and put it in the .env file.
The app is available on the Play Store :
https://play.google.com/store/apps/details?id=net.xdroid.pn
(It can be setup in 20 seconds, no need to create an account, just download the app and use it)
