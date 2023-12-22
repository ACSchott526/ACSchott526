## Howdy 🤠

This profile is used primarily to house the various LolByte repos. LolByte is a suite of applications including: browser extensions, desktop and iOS/Android apps.

## Links to Repos

- [Web Extension](https://github.com/lolbyte-code/lolbyte)
- [Backend Service](https://github.com/lolbyte-code/lolbyte-service)
- [Mobile App](https://github.com/lolbyte-code/lolbyte-react-native)
- [Desktop App](https://github.com/lolbyte-code/lolbyte-electron)

## History
### Summary

I created LolByte in 2014 because I wanted to try building a Chrome extension for fun. Riot had just released the first version of their API and I noticed there weren't any good League of Legends web extensions. This was my first attempt at building a fully functional end to end app from scratch. LolByte has gone through various iterations and I've used the project as an opportunity to learn and apply new technologies over the years. What started as a vanilla HTML/JS/CSS + PHP/Apache app has evolved into a React + Kotlin/Kubernetes app in the 7 years I have been maintaining the project.

### LolByte Evolution
#### Version 1

Originally called "LolMatches", I was basically just winging the UI and came up with this very basic look. It had such limited functionality that I actually included links out to LolNexus and LolKing. However, it was a fully functioning app that talked to the Riot API so I was happy with it!

<p align="center">
  <img width="400" alt="120940371-d2152e00-c6d1-11eb-9f33-829a50072fc3" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/bfcec71d-fe01-4843-923c-2381121df0a5">
  <img width="400" alt="120940408-025ccc80-c6d2-11eb-9d15-8a45aa838ee8" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/0a31ad39-bf13-46d3-acc9-5698a3f1a6b8">
</p>

#### Version 2 (~2014)

This was the first production version of LolByte. In contrast to the first version, this UI was designed by an artist and emulated the look and feel of the League client at the time. I posted it on Reddit and gained ~3000 users: https://www.reddit.com/r/leagueoflegends/comments/2irv1x/introducing_lolbyte_a_fully_featured_and_free/

The backend initially used PHP running on Apache web server. I eventually rebuilt the backend with Java running on Tomcat a year or so later.

<p align="center">
  <img width="400" alt="120940430-17d1f680-c6d2-11eb-8f8b-25de9db9bf25" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/b730cf4b-34dd-4d5d-86e3-9b9ef620d6fa">
  <img width="400" alt="120940431-19032380-c6d2-11eb-9e55-238986570759" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/46f4b1a0-747b-4429-b8f0-80e07a92d6ca">
  <img width="400" alt="120940432-199bba00-c6d2-11eb-9736-afe00bc52fe2" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/0b6585c7-f2f5-4b0c-b921-e650a4ccca1a">
</p>

#### Version 3 (~2016)

After a couple years of success with LolByte, it felt like it was time to revamp the UI. This design is a lot sleeker than the previous one. I learned a lot from building the previous version which I applied here. Namely, I started using JQuery which made writing Javascript a little more manageable. However, I opted to not use any fancy frameworks like React/Vue/Angular which made maintenance difficult over time (but debugging was easy!). I eventually rewrote the backend, heavily making use of the Java streaming API. I also learned Docker and got the backend deployed that way. After that, the project was basically in maintenance mode until 2020 where I was just updating any time there were new champs/games/items. I found ways to make all this dynamic in future iterations which made my life a lot easier in terms of maintenance.

<p align="center">
  <img width="400" alt="120940480-61badc80-c6d2-11eb-8c12-0e94cab3a269" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/367329fc-6e39-4703-ad55-fb8b8fc6f0f0">
  <img width="400" alt="121127283-62409980-c7de-11eb-9f6d-ad2348bdbd55" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/39a94bf1-4646-4329-aa2e-72111a11f6e4">
  <img width="400" alt="121127280-62409980-c7de-11eb-9a39-5641525c6f84" src="https://github.com/lolbyte-code/lolbyte-code/assets/5995446/a91488e7-7ed6-4b95-b584-b38663c313eb">
</p>

#### Version 4 (~2020)

After many years of running LolByte, I felt it was really time to modernize the frontend and backend and apply all the things I had learned up to that point. This iteration introduced a lot of challenges. It was my first attempt at making a mobile app. I opted to use React native so that I could seamlessly deploy to iOS or Android and give myself an excuse to learn React. In 2021, I completely revamped the backend into a much more streamlined service. I built it in Kotlin using Spring Boot and set up the deployment in a managed Kubernetes service. In contrast to previous versions, this setup requires almost no maintenance at all which is great!

<p align="center">
  <img width="275" alt="120940667-43a1ac00-c6d3-11eb-95b9-54f631eb1f70" src="https://lolbyte.me/img/image1.png">
  <img width="275" alt="120940664-42707f00-c6d3-11eb-868d-52d7252faf8d" src="https://lolbyte.me/img/image2.png">
  <img width="275" alt="120940666-43091580-c6d3-11eb-9f5e-5968a0327289" src="https://lolbyte.me/img/image3.png">
  <img width="275" alt="120940661-413f5200-c6d3-11eb-8d09-902d8df788c5" src="https://lolbyte.me/img/image4.png">
  <img width="275" alt="120940661-413f5200-c6d3-11eb-8d09-902d8df788c5" src="https://lolbyte.me/img/image5.png">
</p>

### Future

LolByte is the side project that keeps on giving. I imagine as the years go by I will continue to update it in order to learn new tools and technologies. If you want to give LolByte a shot, just search for it in whatever app store you'd like.

### Feedback

Feel free to email me at crxlolbyte@gmail for any feedback, comments or questions!
