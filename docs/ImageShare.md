# ImageShare

ImageShare is my lightweight web app for uploading and sharing images, 

originally created as a replacement for the Nintendo 3DS Image Share service.

It has gone through a lot of code updates and migrations over the last few years to keep it compatible with aging web browsers,

and now I've rolled out another update.
 
# Features

 - mageShare still allows you to choose an image from your device, click Upload, and get a QR code linking to the image that you can easily scan with another nearby device. It's still entirely server-side PHP, so it loads quickly, even on low-end and legacy web browsers that can no longer connect to image upload services directly.

 - The app previously used Imgur for all image uploads, but that API isn't always reliable, so ImageShare now fully supports ImgBB as an alternative platform. You can select which service to use from the main upload page. For security reasons, images uploaded anonymously through ImgBB are deleted after two minutes, which should be long enough to save the image after scanning the QR code.
 
 [Patreon](https://www.patreon.com/posts/96400980)  
 [Github](https://github.com/corbindavenport/imageshare)