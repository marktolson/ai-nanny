# AI Nanny - Because I Couldn't Think Of A Better Name

Use the power of AI to help monitor your kidlets during the Coronavirus isolation period. 

This simple site allows you to connect multiple live streams using your old phones, then utilises machine learning models (COCO SSD mobilenet & tensorflow lite) to detect the presence of people appearing in the streams. When no people are detected in all views (ie. your baby is no longer visible to any camera), the page requests you attention. There is nothing to install, just click the link below and add your cam streams.

*[Click here to use the site](https://marktolson.github.io/ai-nanny/)*

Feel free to do as you wish with the code. It's very easy to modify to monitor animals / pets and other objects. 

Disclaimer: It's very poorly written and probably really buggy. I was tired and just needed a solution by the time my child woke up from her nap!

# Screenshots
![AI Nanny](http://marktolson.github.io/ai-nanny/nanny1.gif)


# How To Setup
1. Grab some old phones and install [IP Webcam](https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_AU) or another cam streaming app that can encode to the MJPEG format.

2. Obtain the cam stream URL of the video from the app (example: http://192.168.1.20:8080/video) NOTE: You'll need to append the '/video' to the end of the URL if using the IP Camera app. 

3. Go to [this site](https://marktolson.github.io/ai-nanny/)

4. Enter the streaming url from the IP Camera app.

5. Click the 'Add' button.

6. Once all cams have been added, click the 'START MONITORING' button.

* For best results reduce the stream resolution in th IP Camera app to around 640px wide.
