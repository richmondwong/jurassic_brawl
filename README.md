# Jurassic Brawl

!["Intro GIF"](https://github.com/richmondwong/jurassic_brawl/blob/master/screenshots/one.gif)

Jurassic Brawl is a classic 2D multiplayer game in the vein of Nintendo's Super Smash Bros. This game won first place at the Feb 2019 Lighthouse Labs projects competition as voted by 100+ audience members.

The aim of the game is simple: extinguish your lizard brethren using a hail of lethal fireballs and Mike Tyson-like dino headbutts.

Grab weapon and health power-ups to ensure you're the last one standing (and while you're at it, see if you can etch your name in the high scores list).

We made Jurassic Brawl to recapture the old school console gaming experience of playing together with friends in the same room. Play together with 3 other players on any mobile device (phones and tablets across all operating systems are compatible) which via Socket.io we've turned into wireless gamepads.

Jurassic Brawl was created by [Shih-chieh “CJ” Ke](https://github.com/RayCJ87), [Edward Yang](https://github.com/edwardcode) and Richmond Wong.

## Screenshots

Battling it out in the desert (along with indisputable archaeological evidence that large modern mammals did infact co-exist alongside dinosaurs).

!["Screenshot 1"](https://github.com/richmondwong/jurassic_brawl/blob/master/screenshots/one.png)

Health power-up sky drops are randomized by location. Grab the bazooka to inflict double damage.

!["Screenshot 2"](https://github.com/richmondwong/jurassic_brawl/blob/master/screenshots/two.png)

Start screen.

!["Screenshot 3"](https://github.com/richmondwong/jurassic_brawl/blob/master/screenshots/start.png)

Wireless gamepad on mobile phone / tablet. Joystick has full 360 degree movement.

!["Screenshot 4"](https://github.com/richmondwong/jurassic_brawl/blob/master/screenshots/gamepad_one.png)

## Dependencies

- Phaser game engine
- Socket.io
- Express
- MongoDB
- EJS
- Bootstrap

## Getting Started

- Install all dependencies (using **npm install**)
- Run the development web server using the **npm start** command
- Go to **localhost:3000/newgame** in your browser
- You will need the IP address of your wifi network for your mobile device. Use your respective IP address to connect to **your-IP-address:3000/player** on your mobile device's browser
- If not all players present have a mobile device, they can play using the onscreen controller by following these steps: (1.) Open a new browser window; (2.) Connect to **localhost:3000/player**
- Finally, you can play the game on your computer's browser by clicking **New Game** and then **Ready** when all four players have connected their controllers
