# Liri-Bot
Language Interpretation and Recognition Interface
## Assignment Details
In this assignment I was tasked with the problem of creating a LIRI Bot. Similar to Apple's SIRI, Speech Interpretation and Recognition Interface. LIRI take commands via the command line, rather than using voice recognition to interpret the data.


### Gif Of The App In Action
![](lirigif.gif)
### Technologies Used
* JavaScript
* Node.js
* Moment.js
* API's
  * Spotify
  * OMDB
  * Bands In Town


### How The App Was Created

First and foremost, to create this app. We are going to need to be able to access the API's. After searching about and grabbing the API's `BandsinTown` `OMDB` and `Spotify` HTTP's. I was able to create any access needed for those API's via tokens/API Keys. 

Second, after first finding the API to where the user will query. I created the files needed for the assignment which can be found in this Github Repository! 

The third step, in the process of creating LIRI, was grabbing the response using a backend API request with the node package 'axios'. 

Once the response from the API has been 'console.log()'. The fourth and final step to the project, to create the functions and statements making the user functionality simplistic. 


### Future Enhancements

Bring a little bit more user functionality to the picture by adding simplistic yet readable inputs that make it easier for the user to search using a certain keyword rather than concatenated words.
Add a front-end to this project. Having it display on an HTML page rather than sitting in the back-end so more users can use this app. 
