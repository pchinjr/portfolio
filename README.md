# Paul Chin Jr. Web Developer Portfolio
Welcome to a list of my personal projects and contributions. I started learning how to program after attending International Nodebots Day 2015 at the [757 Makerspace](http://757makerspace.com) in Norfolk, VA. I received my first Nodebot and was hooked. Since then, I have been on a never ending quest to learn as much as I can about web technologies. 

---
## Ghostbusters Marketing Website
My first project after finishing html/css/js basics. I pretended that the Ghostbusters hired me to create a slick marketing website for them. 

In this project I learned how to: 
* Use Bootstrap
* Modify an HTML template
* Host a Static Site
* Use git and Github

Check it out [HERE](http://ghostbusters.bitballoon.com)[SOURCE](http://github.com/pchinjr/ghostbusters)
![Ghostbusters Homepage](http://i.imgur.com/EA1jVfs.png)

---
## Ghost Reporter App
The Ghostbusters loved the marketing site so much, that they wanted me to create an app that let's anyone report ghost sightings. This was a huge challenge for me to take on. It quickly taught me how to expand my skills to to the back end using  NodeJS with a database.

In this project I learned how to: 
* Deploy an app to Heroku
* Use MongoDB
* Use Jade templates

Check it out [HERE](http://ghostreporter.herokuapp.com)[SOURCE](http://github.com/pchinjr/ghostreporter)
![Ghost Reporter](http://i.imgur.com/gnS6vcp.png)

UPDATED: I wanted to learn some React, so I built a new version with React and [deployed](https://ghostreporter-react-lxuotvklmv.now.sh/) it to Zeit's Now. There is also a [version](https://ghostreact.firebaseapp.com/) built with Firebase.

In the update I learned: 
* New deployment methods
* Firebase
* React

---
## Deletion
This was my first Code&Art project. I wanted to create an app that highlights the ephemeral nature of digital thought. While it is true that nothing on the internet dies, it is easier now than ever to make something completely impermanent. All you have to do is delete it from memory and pull the power. In this experiment I invite the viewer to sit at a blank screen and just type whatever they want. 

Eventually, I would like to have it become an installation where it's a darkened room that is empty except for a keyboard on a pedestal. The screen is projected on an empty wall. Other thoughts I had were to introduce random music and lights to affect the mood of the viewer to see if it changes what they write and their overall experience.

In this project I learned how to: 
* Develop a concept into working code
* Store user input in an array and manipulate the array
* Actually delete the first character on a timer! 
* Display the results
* Use JQuery

Check it out [HERE](http://pchinjr.github.io/deletion)[SOURCE](http://github.com/pchinjr/deletion)
![Deletion App](http://i.imgur.com/JtCxTzx.png)

---
## Random Carry
I am a volunteer and member of Babywearing International of Hampton Roads. It's an educational and community outreach organization that teaches caregivers the tools of babywearing. Babywearing is a huge part of how I parent, and I wanted to give back something. I created this app during Babywearing Week to promote the cause. In a couple of days, I figured out how to convert a huge excel spreadsheet of wrap sizes and carry types to generate a random carry for caregivers. When I orginally wanted to make an app, I came up with really wild ideas. However, after actually asking the community what they wanted, they told me that they just needed something to help them choose what carry to do on any given day. Thus, random carry was created. 

In this project I learned how to: 
* Listen to user needs
* Work with JSON as a data model 
* Create business logic that fit the user needs

Check it out [HERE](http://randomcarry.bitballoon.com)[SOURCE](http://github.com/pchinjr/randomcarry)
![Random Carry](http://i.imgur.com/YPm7S7x.png)

---
## Dicey
I knew I wanted to make some sort of game for my next project. This concept came out of a conversation I had with my college roomate. He was alaways desinging games in his spare time and I asked him, what would be the simplest game I could make with random numbers. The result was Dice Wars. This was a huge technical challenge for me. I managed to put together a functioning game with turns and a winner. I had a lot of fun trying to make it more balanced and of course, have plenty of ideas on how to make it better in the future. This was also the first project I presented as a lightning talk at [NorfolkJS](http://www.norfolkjs.org). The talk was about the pure magic of github pull requests. You can read a summary of my talk on my [Medium Blog - Pull Requests are Magic](https://medium.com/@paulchinjr/pull-requests-are-magic-58f24f0e8760)

In this project I learned how to:
* Wrestle with game state
* Use a sprite based animation library
* Put everything I've learned so far into practice

Check it out [HERE](http://pchinjr.github.io/dicey)[SOURCE](http://github.com/pchinjr/dicey)
![Dice Wars](http://i.imgur.com/FPjKCbh.png)

---
## Catte Trader
This idea came from my initial investigations with the Twilio API. I have always been intrigued by how much could be done with just text over the network. All of the early computer games were text based and I remembered playing Drug Wars on my calculator in high school. Shortly after I began trying to recreate Drug Wars though SMS, everyone told me it was a terrible idea and the DEA would be breaking my door down. That caused me to switch gears and replaced drugs with cats. The result is the beginning of the hardcore world of underground cat trading. This was the first time I created my own API from scratch to fetch current prices from a server. It's still in the very early stages, but my plan is to use Twilio and AWS Lambda Functions to create a full sms game. 

Things I learned in this project: 
* Twilio API
* REST endpoints

Check it out [HERE](http://pchinjr.github.io/cattetrader)[SOURCE](http://github.com/pchinjr/cattetrader)
![Catte Trader](http://i.imgur.com/OAAlO5b.png)

---
## Cage Bot
Cage Bot is my most ambitious project and has allowed me to give talks at two developer conferences, Hampton Roads DevFest 2016 and Revolution Conf 2017. I wanted to create a physical interaction layer to worship Nicolas Cage, the internet meme. This project has gone through multiple iterations already. It began with a Node script to sweep a servo and blink an LED. Then I added a web interface. Then I moved the node server to a Raspberry Pi to be able to run it without my laptop. After that I added a public webpage that allowed for remote control of the hardware. My latest iteration included Microsoft's Machine Vision API to recognize a photo of Nicolas Cage to unlock the ability of remote control. 

Things I have learned in this project: 
* Web Sockets with multiple clients joining in a lobby
* Arduino Hardware - streaming real time data from a sensor to the web front end
* Raspberry Pi Hardware - runs the local Node server
* Deploying to Digital Ocean - hosts the public web interface
* Machine Learning APIs - Microsoft Cognitive Services Machine Vision
* Streaming binary data and the Node Buffer object - Users capture a photo with their mobile device and stream the data directly to Microsoft for analysis
* Publishing to npm

Check out a video of it [Here](https://www.youtube.com/watch?v=FxLoW4LnonQ)
[The source for the local node server](https://github.com/pchinjr/sock-puppet)
[The source for the Machine learning public side](https://github.com/pchinjr/cage-ai)
![Cage Bot](http://i.imgur.com/kwNqTuI.jpg)
![Cage Bot Inferface](http://i.imgur.com/QO4ThPR.png)

## Collaborative Projects and Open Source Contributions
I have also submitted pull requests to different projects and made sites for other people.

* [Code for Hampton Roads - Bus Tracker](https://github.com/Code4HR/hrt-bus-finder/pull/177)
* [PopUp Robots Site](https://github.com/popuprobots/popuprobots.github.io)
* [International Babywearing Week 2016](https://github.com/pchinjr/ibw2016)
* [Node core contribution at 2016 Collaboration Summit](https://github.com/nodejs/node/pull/9973) - The coolest thing I've ever done. 

---
## Acknowledgements
I could never ever ever have gotten this far without the awesome help and support of the great community of developers and tech enthusiasts in Hampton Roads. Join the community and come to the meetups. I promise you'll meet great people and learn more than you could ever imagine. Request a Slack Invite at [757Dev.org](http://757dev.org)
