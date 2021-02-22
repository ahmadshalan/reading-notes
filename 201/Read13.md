# N07:THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

Cookies wer invented early for restoring small amout of dat. and they have 3 downsides:
1. it should be included with each HTTP request. so it will slow down the web application.
2. send the data unencripted over the internet. also because it is included with each HTTP request.
3. limited to 4 KB.

Now what achieved  by HTML5 and not with cookies:
1. a lot of storage
2. on the client
3. presists beyond the page refresh.
4. not transmitted to server.


## Local Storage before HTML5:

userDta was invented by Microsoft with DHTML Behaviors. it allows web storage up to 64 KB per domain.<br />

In 2002 Adobe introduce a feature on flash 6 (Flash Cookies) which allows to store data up to 100 KB.<br />
In 2006 Flash 8 came and it gives each domain 100KB for free. it promopts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

## Introducing HTML5 Storage:

Web Storage was a part of HTML5 till it was split up to uninteressting political reasons. Some webbrowers are refering to it as DOM Storage or Local Storage. <br />

HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. <br />

## USING HTML5 STORAGE:

HTML5 Storage is based on named key/value pairs. The named key is a string. The data can be any type supported by JavaScript, including:

1. strings.
2. Booleans.
3. integers.
4. floats. 

all the data is actually stored as a string. if need to restore other than string, then to use functions. <br />


## TRACKING CHANGES TO THE HTML5 STORAGE AREA

to track of when the storage area changes, ywe have to trap or call The storage event using the function name with ().

## LIMITATIONS IN CURRENT BROWSERS

5 megabytes is how much storage space each origin gets by default.

## BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS

In 2007, Google launched Gears an open source browser included an embedded database based on SQLite. this prototype later influenced the creation of the Web SQL Database specification. which allows to mke new things on JavaScript.








