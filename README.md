# mobile_phisher
Mobile_phisher allows you to host mobile Phishing Pages on 000webhost.com without Getting your Account deleted
# Why This New Tool?
000webhost.com Blocks Those Guys Who Uploads a Nice looking index.html file that calls a stupid looking php file which saves a text file in the website, and that text file contains all passwords that were captured by your nice looking index.html

# How Does This Saves Us From Getting Blocked?
In this case we upload a nice looking index.html and a stupid looking php, But the Diffrence is that this php does not saves the Credentials in a text file but instead sends them to the attacker via email.

# Setup

1:) create a free account on 000webhost.com
2:) login to file manager
3:) create a folder to keep your files
4:) upload all the three files in mobile_phisher to your folder that you created in step-3.
5:) edit action.php and add any valid email to line 14 ( without brackets )
The email that you add to line 14 is the email address that you will get your credential emails from ( it will br spoofed )
6:) add your email ( Receiver's Email ) to line 15.
7:) save and close action.php and go to your website

https://yoursubdomain.000webhostapp.com/yourfolder/index.html

# ScreenShots
#Website

![alt text](http://pwnedbyme.000webhostapp.com/preview.jpg)

#Email

![alt text](http://pwnedbyme.000webhostapp.com/preview1.jpg)
