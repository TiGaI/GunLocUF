# gun-loc
Gun Loc aims to bring firearms into the Internet of Things. The product offered by our company consists of a firearm integrated accelerometer which is used to deliver signals to our Arduino microcontroller to, in turn, send a message via Bluetooth to a Java applet. The applet takes this message and turns it into an HTTP POST request, sending it to our Node server that does two things: 1 - it updates the gun's alert status in our Mongo database and 2 - it sends a POST request to the Twilio API. The firearm owner then receives a text alert to their personal cell phone, and at the same time our Angular web application is updated to reflect the new alert status of the firearm. Microsoft Azure lives at the heart of Gun Loc, powering our server and our database. 

![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/homescreen.jpg "HomePage") 
![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/Dashboard.png "HomePage") 
![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/Dashboard1.png "HomePage") 
![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/Dashboard2.png "HomePage") 
![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/proto1.jpg "HomePage") 
![GunLocUF](https://github.com/TiGaI/GunLocUF/blob/master/pictures/proto2.png "HomePage") 

## HackIllinois 2016 - 3rd Place

## US Imagine Cup Finalist

## TOP 10 UF Gator Business Competition

[WebApp Hosted on Azure](http://gun-loc.azurewebsites.net/)
[Devpost Submission](http://devpost.com/software/gun-loc)
