# IPhone - Photo Display Issues

Seeing images being shown upside down on places other than the live site? Were the photos taken with an iPhone? Then good chance that the EXIF value for the image has been set to reflect as such.

Places where this occurrence has been noticed:

* On iOS Mobile Apps
* When Sharing a listing to Facebook
* Browsing listings on the website on iPhone using Safari

This issue occurs when the user takes a photo with an iPhone in a certain way. Currently, when we pull the images in from the MLS we do not have a way to ignore the EXIF value like the website application does for other operating systems.&#x20;

If you have an issue reported for this case, the best way to get it resolved would be for a new photo to be uploaded with an EXIF value of 0000. This value can be checked/edited manually by checking under the photo's details tab. Alternatively you can suggest taking new photos using a camera that is not iOS and uploading those images to the MLS.

Here are a few sources for some background info:

This page: [http://www.geek.com/apple/why-iphone-pictures-flip-when-emailed-and-how-to-fix-it-1602306/](http://www.geek.com/apple/why-iphone-pictures-flip-when-emailed-and-how-to-fix-it-1602306/) is more friendly then most:

"The issue originated back when iOS 5 was released, because the operating system introduced the culprit: the ability to snap a photo with the phone’s volume up button. Basically, the camera’s sensor doesn’t realize when you rotate the phone to take a picture. Supposedly, your phone doesn’t correct the orientation itself because doing so would make it harder for the phone to take another picture immediately after the last. Instead, the iPhone writes the orientation info to the EXIF data of the image.

The reason why the images flip when you email them or transfer them to certain operating systems is because not all environments acknowledge EXIF data. This means that the orientation tags aren’t being acknowledged."

3 possible ways to get around this:\
1 - Upload photos to your computer and flip/rotate them before sending .\
2 - Take the photo with the volume buttons oriented on the bottom of your phone rather than the top. (easiest option)\
3 - Use a camera app that records the image information once it is taken, such as Camera+.

Couple more articles that detail this occurrence:\
[http://iphonephotographyschool.com/iphone-photos-upside-down/](http://iphonephotographyschool.com/iphone-photos-upside-down/)\
[http://www.howtogeek.com/254830/why-your-photos-dont-always-appear-correctly-rotated/](http://www.howtogeek.com/254830/why-your-photos-dont-always-appear-correctly-rotated/)
