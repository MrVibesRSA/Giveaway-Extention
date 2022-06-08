# How to install, setup and working with the commands.

### Installing the actions.
+ Copy the raw code from [Importcode.md](/Importcode.md "Link to the code") and import it in to Streamer.bot, there should be 9 new Actions now. 
+ Example: ![alt text](img/1.png "image title")

### Setup Instructions.
+ Firstly we need to create two new text files for the Giveaway actions to use, Where you save them is ultamatly up to you
  but for example sake and my choise I'll do so in the H:\Streamer.bot x64\data\ folder.
+ You can do so by right clicking  emty space in the folder and going to new and selecting New Text Document. Now you can call
  the one ListEntries and the other one ListWinners.
+ Example: ![alt text](img/2.png "image title")
+ Now that our file system is ready we can head over to Streamer.bot and finish up our setup with a few more steps.
+ Under "Giveaway - Setup : !giveawaysetup" Sub-Actions you will see two file locations we need to point to our newly
  created files.
+ Example: ![alt text](img/3.png "image title")
+ Next we create some Chat Commands  and link them to there actions.
    + Giveaway - Setup : !giveawaysetup,      		Recommended Allow user only "The streamer".
    + Giveaway - Set Info : !setinfo,         		Recommended Allow Mods only.
    + Giveaway - Set Duration : !setduration, 		Recommended Allow Mods only.
    + Giveaway - Set Allowed Entries : !setentries, 	Recommended Allow Mods only.
    + Giveaway - Run : !rungiveaway, 			Recommended Allow Mods only.
    + Giveaway - Pick Winner : !pickwinner, 		Recommended Allow Mods only.
    + Giveaway - Clear : !clear, 			Recommended Allow Mods only.
    + Giveaway - Enter : !enter, 			Recommended Allow Everyone.
    + Giveaway : !giveaway, 				Recommended Allow Everyone.
    + Example: ![alt text](img/4.png "image title")
+ Finally we can run the !giveawaysetup in twitch chat to Complete our setup.
+ The Setup is now complete and you ready to learn how to use the Actions/Commands.

### How to use the Giveaway Commands.
+ Now for the Admin to get the Giveaway ready, recommended to do so before stream but can be done while streaming.
+ Using the !setinfo allows you or a mod to set the info for the give away keeping in mind twitch's 500 character limit in chat.
+ Example: ![alt text](img/5.png "image title")
+ Using the !setduration "Number" allows you or a mod to set the duration the give away will run for in minutes with a minimum of 5 minutes.
  this means you can run  the give away  for 60 min just chat break or for an entire 3 hour (180 minute) stream.
+ Example: ![alt text](img/6.png "image title")
+ Sets the duration of the give away for 10 minutes, once the duration is over viewers are unable to enter regardless of the 
  entries they have left.
+ Using the !setentries allows you or a mod to spedify the amout of times a Viewer is allowed to enter the giveaway.
+ Example: ![alt text](img/7.png "image title")
+ Sets the Limit of entries to 5, giving our viers more of a chance to win. The limite can be razed during a giveaway,
  but lowered is not recomended as this will put new entries at a disatvantage.
+ Using the !rungiveaway allows you or a mod to start the giveaway, this will run for the previous set duration. While
  the give away is running viewers able to entre the giveaway till their entries are up.
+ Example: ![alt text](img/8.png "image title")
+ You are also able to run the giveaway multiple times, incase you feel like giving chat another chance to get there entries in.
  Each time you use the the !rungiveaway command it will run for the the previous set duration unless you have set a new duration.
+ Using the !pickwinner allows you or a mod the randomly pick  a Winner from the Entries.
+ Example: ![alt text](img/9.png "image title")
+ You are also able to pick multiple winners bay adding a space with a number to the end of the !pickwinner command, as in the example.