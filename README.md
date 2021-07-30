# Twitch-Quiz-Bot

This is an updated version of the [Dota-Quiz-Twitch-Bot](https://github.com/Party-Hats/Dota-Quiz-Twitch-Bot)  
These are the major changes:
- It uses Java and [twitch4j](https://github.com/twitch4j/twitch4j) instead of JavaScript
- It has a bigger scope in terms of games. Instead of just being able to have quiz questions for Dota2, it has multiple quiz-libraries and is able to switch between them when the streamer changes played games
- It has a bigger scope in terms of twitch channels. Instead of just being able to connect to one twitch text channel, it will be able to handle multiple channels at the same time, each with their own quiz-libraries and user stats
- It uses a containerized persistance layer to save user stats and other data
- It saves questions set up in the WebUI into a persistance layer independent of the server (e.g. a private GitHub repository)
