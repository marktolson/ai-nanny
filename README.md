# AI Nanny - Because I Couldn't Think Of A Better Name

Use the power of AI to help monitor your kidlets during the Coronavirus isolation period. This simple site allows you to connect multiple live streams using your old phones, then utilises machine learning models (COCO SSD mobilenet & tensorflow lite) to detect the presence of people appearing in the streams. When no people are detected in all views (ie. your baby is no longer visible to any camera), the page requests you attention.

[Click here to use the site](https://marktolson.github.io/ai-nanny/)


# Screenshots
![AI Nanny](http://marktolson.github.io/ai-nanny/nanny1.gif)


# How To Setup
1. Install [IP Webcam](https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_AU) or another cam streaming app that can encode to the MJPEG format.

2. Obtain the cam stream URL of the video from the app (example: http://192.168.1.20:8080/video)

3. Go to [this site](https://marktolson.github.io/ai-nanny/)

4. Enter the streaming url from the IP Camera app.

5. Click the 'Add' button.

6. Once all cams have been added, click the 'START MONITORING' button.

* For best results reduce the stream resolution in th IP Camera app to around 640px wide.
