
* Under open source license
* No ©copyright issues
* Anyone can be modify this code as well
* Specifically we will be happy whenever you use our code in your website(^_^)
* Designed by @BlackX-Lolipop
* Content available by @BlackX-732
* Content available @ https://github.com/BlackX-732/AwesomeMenu
* Version 21.2.7
* @https://facebook.com/BlackX-732



Module/Library/function/icons used in this project:
------------------------------------------------------
 
 * cdjns of font-awesome https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css
 * jQuery v3.3.1 | (c) JS Foundation and other contributors | jquery.org/license
 * HTML-5
 * Custom css
 * Custom javascript
 * & some icon.I don't know if someone have enough time to claim that's ownership [XD] .
 

  Important information of this project:
-------------------------------------------

* Custom css file path -> /dist/css/menu-style.css
* Custom js file path -> /dist/js/menu.js
* Path of jquery -> /dist/js/jquery.min.js
* Path of font-awesome -> /dist/font-awesome/ [We remove it for huge size.You can download it by below's instruction]
* Path of icon and image -> /dist/img/


 Dowload font-awesome:
 ---------------------
 
 * Download font-awesome's latest librabry https://fontawesome.com/
 * Replace it into /dist as /dist/font-awesome
 * Remove the comment of font-awesome link from index.html
 * Also you can delete the cdnjs linkup from index.html
 
 Why .collapse:
--------------------

* we used .collapse in -> /dist/css/menu-style.css if though it doesn't exist in -> /index.html
* .collapse is exist in -> /dist/js/menu.js
* We created this class by this script/selector -> $(".wrapper").toggleClass("collapse");


 Change the Header Text:
------------------------

* Find out class="title" in /index.html
* Then change the text of class="title-hide" && class="sec-span"


 Change the Sidebar icon and username:
--------------------------------------

* Find out class="profile" in /index.html
* Then change <img src="dist/img/avatar.png" alt=""><p>BlackX-732</p>



 How to classify different background source before collapse and after collapse:
--------------------------------------------------------------------------------

If you want to change background source of .main-container after collapse then ad below's code into .collapse .main-container

    background: url(new-image.jpg) no-repeat center center;
    background-size: cover;
    height: 100vh;

* no-repeat -> for miss-match size of image
* center -> vertically center
* center -> horizontally center
* 100vh -> 100% vertical & 100% horizontal

 For little more smoothness add this to previous class

    transition: 0.3s;


That's all.Enjoy Our code by your own way.(^_^)
