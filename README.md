# ChatGPT-App

A simple ChatGPT app built using OpenAI API using Java for the backend and OKHTTP library for creating HTTP requests
  | build.gradle

Add the below dependency in Module level build.gradle

  | implementation("com.squareup.okhttp3:okhttp:4.10.0")

AndroidManifest.xml In AndroidManifest.xml file give the permission to use Internet

  | <uses-permission android:name="android.permission.INTERNET" />

API Call URL

  | https://api.openai.com/v1/completions

ScreenShorts
![ChatGpt_ScreenShot1](https://github.com/aashu217-coder/ChatGPT-App/assets/115043992/974455e8-2b33-425e-b365-562a2f2eb488)

![ChatGpt_ScreenShot2](https://github.com/aashu217-coder/ChatGPT-App/assets/115043992/3b434261-8309-49cf-8c63-d3b395fb6664)
