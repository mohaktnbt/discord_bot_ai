
![Logo](https://github.com/Nsiem/HawkHacksProject/blob/master/assets/vivyailogo.png)

Vivy is a smart, creative, clever AI that wants to talk with you!
 


## Inspiration
We've always loved AI, and GPT-3 was an AI algorithm we've wanted to utilize for some time now. Then we learned about the power of Assembly.ai and it clicked, let's make a AI bot to talk with on discord. We also wanted to base it off of a character from an Anime we both enjoyed, Vivy: Flourites eyes. Vivy is a robotic AI who loves to sing, and we wanted to bring her personality to life in our bot.


## What it does
- Vivy is an AI that will have a conversation with you on discord
- Vivy will join a voice channel and then listen to the user
- Vivy then verbally responds to anything the user says.
- The conversation is transcribed in a text-channel so you will never forgot!
## How we built it
- First we set up a basic discord bot to retreive audio that converts 
- We then send the wavfile data to Assemblyai and then wait for it to be processed, retreiveing the speech-to-text
- Then we sent the text to gpt3, including our prompts, to generate a contextual response
- Finally we used utilized Google's text to speech to generate along with GPT3 repspone to create an MP3 file to play back to the user on discord .


## Challenges we ran into'
- Transcription time 
- Figuring out how to use all the api's
- Incorparating Vivi's traits for GPT3 to learn from 

## Accomplishments that we're proud of
- Saving audio from discord call



## What we learned
- Project implementation/development skills
- AssemblyAI, GPT3, Discord.js, Google Cloud 
## What's next for Vivy.ai
After creating Vivy.ai we realize the potential it has for voice commands in discord, so a potential future would be to make a voice assistant discord bot to complete actions on the server. We also want to allow others to use Vivy.ai, so hosting it on the cloud will allow hundreds to talk with her.




## Deployment

To start, clone this repo:

```
git clone https://github.com/Nsiem/HawkHacksProject.git
```

After you have cloned the project install the dependencies inside the folder:
```
npm init
npm install
```

Setup your environment variables by changing   ``.env.example`` to just ``.env`` and then populate the varibles inside:
```
TOKEN = <Your Discord Bot Token>
CLIENTID = <Your Discord Client ID>
GUILDID = <Your Discord Guild/Server ID >
ASSEMBLYAPIKEY = <Your AssemblyAI Ai API Key>
OPENAI_API_KEY = <Your OPENAI_API_KEY>
```

Run project 
```
node .
```

Invite the bot the server and 
## Demo 
https://youtu.be/h-NpXro3NgM

## Bonus

![Alt Text](https://c.tenor.com/IVVJbs0N7DcAAAAC/vivy-dance.gif)

