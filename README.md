# Museum of Moving Image Game
As part of my internship with the Museum of Moving of Image through my status as a CUNY Cultural Corp student, I decided to create a game that helped push museum goers
to attempt to try their hand at coding!
The Museum of Moving Image uses Pico-8 as tool to teach video game programming, so I set out to figure out a fun and interesting way to get more people involved.
I partnered with Cindy Liu, a graphic design artist at the museum, and we set off to create a game inspired by the aesthetics of the Museum of Moving Image.

## The Goal
The goal was to get mueseum visitors to try their hand at coding. I realized how difficult and off putting initial code is, so I attempted to do **two** things.
1) Create a story that museum visitors could attatch themselves to.
2) Abstract the code as much as possible to ensure no loss of engagement.

I decided that to engage the audience of the average museum visitor, creating a **Zine** or a little comic book would be a good approach. This zine could be stationed 
near the exhibit, and could quickly relay multiple things: the story, and the teaching.

With the goal established, I worked to get the game, and the general flow of the story going.

## The Setup
Over the span of 5 weeks, I partnered with Cindy Liu to draft out multiple renditions of the Zine that would fit the goofy narrative of the game. During this time,
Cindy also attributed to all the assets of the game, which can be viewed directly in the file! It's amazing work, and I'm so happy with how she was able to deliver my
vision. 

During this time, I spent a lot of time iterating over which part specifically should the user *code*. I came to the conclusion that **movement** is an aspect of game design
that players love to control; how fast a player moves, how slow, can I jump, can I do anything with the movement to break the game? (yes you can).
So I created a simple game that had floor collision that worked by creating an invisible rectangle around the player; if the player collided with an object that had a flag, 
that player would be pushed back based on their x position. 
I stored all the player information in a table (tables in Pico-8 are considered composite data structures, similar to arrays) and I came to the part of the code the player had to 
change manually. I abstracted away all the programming syntax that made beginners quit and the result came to a piece of code that was succint and to the point.
I felt as though this was a good point to end, as if the player had any inkling to continue game programming, they could explore the treasure trove of information in a further and
more complete setting.

## The Results
My internship ended just as I got the game up and running on the Museum's computer unfortunately. But this game was a big step in contributing to code **that matters** and being able
to work with an artist on this project was truly an amazing experience. The process was dificult, and I found myself tangling at online resources, but I'm proud of my and Cindy's work!

### Steps to play
The file (momigame_3.p8) is posted above. 
1) Copy the **entire** file (momigame_3.p8) to a text document (TextEdit, Notepad, VS Code).
2) Name the text document, and save that text document as extension **.p8**. (ex: mygame.p8)
3) Locate where you saved that .p8 file and move that file to where your Pico-8 carts folder is located on your system (if you don't know, you can type FOLDER in the command line of Pico-8).
4) In Pico-8, at the command line type LOAD *mygame.p8*. Replace *mygame.p8* with the name of your file.
5) Run the file!

You can view all the amazing art, and code to your heart's content. There's an intentional bug to allow you as the player to add movement to the character. Hope you enjoy! (and break the game).
