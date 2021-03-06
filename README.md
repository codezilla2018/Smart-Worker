
# Smart Worker
chashikajw007@gmail.com | Chashika Weerathunga | chashikajw | IA11


![launcher icon](https://github.com/chashikajw/smart-worker-images/blob/master/logo.png)
# Work Smart - Earn Smart

Domestic services android app with a map. Users can search and get information about nearest domestic services and anyone can request to serve. People also can add services via the app.
- Require GPS location. 
- Require internet connection.
- Require person details to register the app

### Installation
[Downlaod apk](https://github.com/codezilla2018/Smart-Worker/tree/master/Demo%20apk)</br>

### How to setup? 
 
 - Clone the project
 - Import it to the Android studio
 - Build the project
 - You have to get your Gogle map API key and repalxe it to @string/google_map_api key string attribute.because my key can be not working for you
 - Developed Android studio version is 3.0.1, if you are using Android studio 2.  you have to change the some of dependancies in the gradle file according to your version.
 

## Application guide

### If you are a new user, you have to register

You can simply register the app submiting require details 


<img src="https://github.com/chashikajw/smart-worker-images/blob/master/signup.png" alt="Network Enable" width="320" height="550"><br/>


### If you are a registered user, you can login to the app

You have to give email and password

<img src="https://github.com/chashikajw/smart-worker-images/blob/master/login.png" alt="Network Enable" width="320" height="550"><br/>


### Require permissions

When you login to app you have to enable GPS and internet

<img src="https://github.com/chashikajw/smart-worker-images/blob/master/permissions.png" alt="Network Enable" width="320" height="550"><br/>

### Main menu of the app

This is the main menu of the app. there are two buttons and image buttons here. 
- JOB MAP ->  you can view the all services pressing this button
- Add Jobs -> you can add services presiing this button
- Logo(image buton) ->  you can view the all services pressing this button
- Action bar -> LogOut - > you can sign of from the app


<img src="https://github.com/chashikajw/smart-worker-images/blob/master/mainmenu.png" alt="Network Enable" width="320" height="550"><br/>


### Service map.

This is the service map. you can find the all locations of availble services and clicking the markers you can view all details of the services. 

- GPS icon -> re locate to your location
- Info icon -> view details of serched loaction
- Marker clicking -> view all details of the service 

When you click the marker it apprears the direction button in right bottom, clicking that button you can direct to google maps to find the direction to the location from your location 


<p><img src="https://github.com/chashikajw/smart-worker-images/blob/master/map.png" alt="Network Enable" width="320" height="550">

<img src="https://github.com/chashikajw/smart-worker-images/blob/master/mapdetails.png" alt="Network Enable" width="320" height="550">

<img src="https://github.com/chashikajw/smart-worker-images/blob/master/direction.png" alt="Network Enable" width="320" height="550"><br>
</p>


### Add Services.

Filling this details you can add a service to the map. also you can set any location to the service


<p><img src="https://github.com/chashikajw/smart-worker-images/blob/master/addservice.png" alt="Network Enable" width="320" height="550">


<img src="https://github.com/chashikajw/smart-worker-images/blob/master/submitlocation.png" alt="Network Enable" width="320" height="550">
<br>
</p>


**Used APIs**</br>
[Google Map API](https://developers.google.com/maps/documentation/)</br>
[Google Places API](https://developers.google.com/places/?hl=de)</br>
[Firebase Database](https://firebase.google.com/docs/database/)</br>
[Firebase Authentication](https://firebase.google.com/docs/auth/)</br>

**Licence**</br>
[MIT licence](https://github.com/codezilla2018/Smart-Worker/blob/master/LICENSE)

