# LTSAcaptures

# web project design notes 

project name?
1.	manual image match - lets people match photos
	generates some generic output data

volunteer 1
    email the volunteer
	- http://capture-match.hoza.us/020821terrestialday/All1PerCapture
	- http://amby-sto-match.hoza.us 
	- login id (characters a-z0-9) (must be unique duh)




ux:
1. http://capture-match.hoza.us/020821terrestialday/All1PerCapture
2. first name: [       ] last name: [       ] [let's match!]
3. http://capture-match.hoza.us/020821terrestialday/All1PerCapture?name=bradhoza
3. do-they-match page is shown
	a. find first picture from source folder that needs a match
	b. find "random" picture from target folder that needs a match
	c. present page
	d. record answer
	e. repeat



source folder:
a
b
c
d

target folder
1
2
3
4

match questions:
a-3 same
a-2 diff
a-1 diff
a-4 diff
b-4 same
b-1 
b-3
b-2

```
configuration of website
==============================================================
project-welcome.txt
welcome to the long-toed salamander match maker website. <3

project-question.txt
Are these two pictures of the same salamander?

project-images-url.txt
https://github.com/JuliannaHoza/LTSAcaptures/tree/main/photos/

project-target-folder.txt
All1PerCapture

volunteer-list.txt
[username:csv-list-of-source-folders]
bradhoza:011321terrestrialday,012021terrestrialnight
jacksonhall:012021terrestrialnight
===============================================================
```

```
do-they-match page:
-------------------------
welcome to the long-toed salamander match maker website. <3
-------------------------
Are these two pictures of the same individual?
-------------------------
pic1     | pic2
8473.jpg | 1284.jpg
------------------------
(*) same 
( ) different 
[back] [next]

viewing match 1/300 [*               ]
```

http://capture-match.hoza.us

volunteer-list.txt (could be a dropdown list)
bradhoza:




	020821terrestialday/cropped --> All1PerCaptureCropped


	1. (s) PXL_20210226_171401708.jpg vs. (t) PXL_20201213_160305221crop.jpg
	     ---> (brad)_PXL_20210226_171401708.jpg__PXL_20201213_160305221crop__.txt [yes/no]
	2.
	3.


	
		
2. 	process MIM output into the format you want (CSV)
	171401708,160305221,yes,brad
	


code stored in github manual-image-match
data stored in github? salamander-uw-etc

_ create a github account
	bradhoza
	barumpus

_ install visual studio code?
