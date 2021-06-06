### Howdy 🤠

This profile is used primarily to house the various LolByte repos. LolByte is a suite of applications including: browser extensions, desktop and iOS/Android apps.

## Links to Repos

- [Web Extension](https://github.com/ACSchott526/lolbyte)
- [Backend Service](https://github.com/ACSchott526/lolbyte-service)
- [Mobile App](https://github.com/ACSchott526/lolbyte-react-native)
- [Desktop App](https://github.com/ACSchott526/lolbyte-electron)

## History
### Summary

I created LolByte in 2014 because I wanted to try building a Chrome extension for fun. Riot had just released the first version of their API and I noticed there weren't any good League of Legends web extensions. This was my first attempt at building a fully functional end to end app from scratch. LolByte has gone through various iterations and I've used the project as an opportunity to learn and apply new technologies over the years. What started as a vanilla HTML/JS/CSS + PHP/Apache app has evolved into a React + Kotlin/Kubernetes app in the 6 years I have been maintaining the project.

### LolByte Evolution
#### Version 1

Originally called "LolMatches", I was basically just winging the UI and came up with this very basic look. It had such limited functionality that I actually included links out to LolNexus and LolKing. However, it was a full functioning app that talked to the Riot API so I was happy with it!

<img src="https://user-images.githubusercontent.com/5995446/120909611-8c058f00-c62b-11eb-8c51-f11c629ffdf2.JPG" alt="lolbyte1" width="400"/>

#### Version 2 (~2014)

This was the first production version of LolByte. In contrast to the first version, this UI was designed by an artist and emulated the look and feel of the League client at the time. I posted it on Reddit and gained ~3000 users: https://www.reddit.com/r/leagueoflegends/comments/2irv1x/introducing_lolbyte_a_fully_featured_and_free/

The backend initially used PHP running on Apache web server. I eventually rebuilt the backend with Java running on Tomcat a year or so later.

<img src="https://user-images.githubusercontent.com/5995446/120909621-9c1d6e80-c62b-11eb-82a6-ec4a15bba11b.JPG" alt="lolbyte2" width="400"/>

#### Version 3 (~2016)

After a couple years of success with LolByte, it felt like it was time to revamp the UI. This design is a lot sleeker than the previous one. I learned a lot from building the previous version which I applied here. Namely, I started using JQuery which made writing Javascript a little more manageable. However, I opted to not use any fancy frameworks like React/Vue/Angular which made maintenance difficult over time (but debugging was easy!). I eventually rewrote the backend, heavily making use of the Java streaming API. I also learned Docker and got the backend deployed that way. After that, the project was basically in maintenance mode until 2020 where I was just updating any time there were new champs/games/items. I found ways to make all this dynamic in future iterations which made my life a lot easier in terms of maintenance!

<img src="https://user-images.githubusercontent.com/5995446/120909625-a0498c00-c62b-11eb-88fc-b7f9caf41bea.JPG" alt="lolbyte3" width="400"/>

#### Version 4 (~2020)

After many years of running LolByte, I felt it was really time to modernize the frontend and backend and apply all the things I had learned up to that point. This iteration introduced a lot of challenges. It was my first attempt at making a mobile app. I opted to use React native so that I could seamlessly deploy to iOS or Android and give myself and excuse to learn React. In 2021, I completely revamped the backend into a much more streamlined service. I built it in Kotlin using Spring Boot and set up the deployment in the managed Kubernetes service on Digital Ocean. In contrast to previous versions, this setup requires almost not maintenance at all which is great!

<img src="https://user-images.githubusercontent.com/5995446/120909626-a2abe600-c62b-11eb-8bcc-00a2738c99ca.JPG" alt="lolbyte4" width="350"/>
