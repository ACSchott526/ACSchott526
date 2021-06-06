## Howdy 🤠

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

Originally called "LolMatches", I was basically just winging the UI and came up with this very basic look. It had such limited functionality that I actually included links out to LolNexus and LolKing. However, it was a fully functioning app that talked to the Riot API so I was happy with it!

<img src="https://user-images.githubusercontent.com/5995446/120940371-d2152e00-c6d1-11eb-9f33-829a50072fc3.png" alt="lolbyte1a" width="400"/>
<img src="https://user-images.githubusercontent.com/5995446/120940408-025ccc80-c6d2-11eb-9d15-8a45aa838ee8.png" alt="lolbyte1b" width="400"/>

#### Version 2 (~2014)

This was the first production version of LolByte. In contrast to the first version, this UI was designed by an artist and emulated the look and feel of the League client at the time. I posted it on Reddit and gained ~3000 users: https://www.reddit.com/r/leagueoflegends/comments/2irv1x/introducing_lolbyte_a_fully_featured_and_free/

The backend initially used PHP running on Apache web server. I eventually rebuilt the backend with Java running on Tomcat a year or so later.

<img src="https://user-images.githubusercontent.com/5995446/120940430-17d1f680-c6d2-11eb-8f8b-25de9db9bf25.png" alt="lolbyte2a" width="400"/>
<img src="https://user-images.githubusercontent.com/5995446/120940431-19032380-c6d2-11eb-9e55-238986570759.png" alt="lolbyte2b" width="400"/>
<img src="https://user-images.githubusercontent.com/5995446/120940432-199bba00-c6d2-11eb-9736-afe00bc52fe2.png" alt="lolbyte2c" width="400"/>

#### Version 3 (~2016)

After a couple years of success with LolByte, it felt like it was time to revamp the UI. This design is a lot sleeker than the previous one. I learned a lot from building the previous version which I applied here. Namely, I started using JQuery which made writing Javascript a little more manageable. However, I opted to not use any fancy frameworks like React/Vue/Angular which made maintenance difficult over time (but debugging was easy!). I eventually rewrote the backend, heavily making use of the Java streaming API. I also learned Docker and got the backend deployed that way. After that, the project was basically in maintenance mode until 2020 where I was just updating any time there were new champs/games/items. I found ways to make all this dynamic in future iterations which made my life a lot easier in terms of maintenance!

<img src="https://user-images.githubusercontent.com/5995446/120940480-61badc80-c6d2-11eb-8c12-0e94cab3a269.png" alt="lolbyte3a" width="400"/>
<img src="https://user-images.githubusercontent.com/5995446/120940484-641d3680-c6d2-11eb-9ed5-f168c8e8ebe3.png" alt="lolbyte3b" width="400"/>
<img src="https://user-images.githubusercontent.com/5995446/120940486-654e6380-c6d2-11eb-9deb-22d87efa8ba8.png" alt="lolbyte3c" width="400"/>

#### Version 4 (~2020)

After many years of running LolByte, I felt it was really time to modernize the frontend and backend and apply all the things I had learned up to that point. This iteration introduced a lot of challenges. It was my first attempt at making a mobile app. I opted to use React native so that I could seamlessly deploy to iOS or Android and give myself an excuse to learn React. In 2021, I completely revamped the backend into a much more streamlined service. I built it in Kotlin using Spring Boot and set up the deployment in a managed Kubernetes service. In contrast to previous versions, this setup requires almost no maintenance at all which is great!

<img src="https://user-images.githubusercontent.com/5995446/120940661-413f5200-c6d3-11eb-8d09-902d8df788c5.png" alt="lolbyte4a" width="300"/>
<img src="https://user-images.githubusercontent.com/5995446/120940667-43a1ac00-c6d3-11eb-95b9-54f631eb1f70.png" alt="lolbyte4b" width="300"/>
<img src="https://user-images.githubusercontent.com/5995446/120940664-42707f00-c6d3-11eb-868d-52d7252faf8d.png" alt="lolbyte4c" width="300"/>
<img src="https://user-images.githubusercontent.com/5995446/120940666-43091580-c6d3-11eb-9f5e-5968a0327289.png" alt="lolbyte4d" width="300"/>

### Future

LolByte is the side project that keeps on giving. I imagine as the years go by I will continue to update it in order to learn new tools and technologies. If you want to give LolByte a shot, just search for it in whatever app store you'd like.

### Feedback

Feel to to email me at crxlolbyte@gmail for any feedback, comments or questions!
