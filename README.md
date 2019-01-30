# cuddly-fiesta
PhotoFrame-Concept

This project is to create a digital photoframe which can be used to share albums using only HW.

## MVP ##

### Backend ###
- DB with storage locker for file blobs and JWT auth for 1 time use codes
- API to communicate with FE uploader + HW client

### FE - Uploader ###
- React.JS
- File support
+- Resizing
+- Encrypt
+- Upload

### FE - rPI - Downloader ###
- Python?
- File support
+- Decrypt files
- Show pictures in slideshow
+- option - set timer per picture
+- option - set schedule for screen on time
+- option - choose order of pictures?

## Stretch

As files are not stored centrally they are being kept in local storage, if you want to share the files to a second frame this needs to be done from the original device which downloaded all the photos/ 

### FE - rPI - Downloader ###
- Add upload functionality

### Backend ###
- Sync functionality?
