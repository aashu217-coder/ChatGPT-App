# ChatGPT-App

A simple ChatGPT app built using OpenAI API using `Java` for the backend and `OKHTTP library` for creating HTTP requests

> build.gradle

Add the below dependency in Module level build.gradle
```bash
 implementation("com.squareup.okhttp3:okhttp:4.10.0")
```

> AndroidManifest.xml
In AndroidManifest.xml file give the permission to use Internet

```bash
 <uses-permission android:name="android.permission.INTERNET" />
```

> API Call URL

```bash
https://api.openai.com/v1/completions
```

## Screenshots

<div style="display:flex">
<img src="https://github.com/pkini2002/Social-media-web-app/assets/84091455/e53c7c4f-4b1b-4164-9917-a6096e72843a" width="500" height="500">
<img src="https://github.com/pkini2002/Social-media-web-app/assets/84091455/4cbf80eb-f346-409e-81fc-46d6bf23a022" width="500" height="500">
</div>


## References

- <a href="https://platform.openai.com/docs/introduction">ChatGPT Documentation</a>
- <a href="https://square.github.io/okhttp/">OKHTTP Library Documentation</a>
