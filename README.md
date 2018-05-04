# Android Text Recognition using Google Mobile Vision API

Optical Charecter Recognition (OCR) is the ability that gives a mobile to read text appears in image. We will create Android App that uses Google Mobile Vision API.

Google Mobile Vision API can also be used for barcode and face detection.

# Set up
 * To use Google Mobile Vision API we have to add dependenciy.
 `implementation 'com.google.android.gms:play-services-vision:15.0.1'`
 * Add camera permission in `AndroidManifest.xml` file
<uses-permission android:name="android.permission.CAMERA" />

# Troubleshooting
Text recognition API need to download few files. Download will initiate at the time of installation but it may take a few moment. Util then app will not be able to use Vision API. In that case please wait few moment and try again.

# Screen Shot
![android_text_screen_shot](https://i.imgur.com/Wd2meo7.png)

![android_text_screen_shot](https://i.imgur.com/UPlb1iO.png)
