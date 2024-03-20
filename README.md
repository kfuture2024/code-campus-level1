# code-campus-level1 Day 8

## Learn
Check how to accept input from user on a terminal in NodeJS. Could be similar to below.   

Run ```npm install prompt-sync```

(There will be new file package.json and also new folder node_modules. Ignore for now.)   

Then in the code:     
```
const prompt = require('prompt-sync')();

const userInput = prompt('Enter an input:');
//userInput will have the user input
```

Later on you can use the prompt function anywhere.

## Task
***Gambling Game***
- You need to build a game which will have 2 players, recieve the name of the players from terminal.
- Once the names are received, it should ask which player will start?
- Once player is confirmed, gambling starts.

*The game*
- The terminal will ask for the user to hit enter and then it should generate random number between 0 to 6.
- Until there is not a 0 the score for the user keeps adding. If the generated number is 0, the score totally becomes 0.
- User will have option to quit(n) or continue(y) with chance. If user quits the chance - his score remains same as he got. That means if User A has 10 total, it remains. And user B can play and when User A gets chance again, it adds to 10.
- Whenever the opponent quits or hits 0, the other user gets chance.
- Who reaches a total of 40 wins the game.
- Print the message - User <username> is the winner.

  
*Sample*
- User A,B are players.
- User A starts the game.
- User A gets 2, continues his chance with y and gets 3 and then quits with n. A has a score of 5.
- User B hits y and gets 4, again y and gets 5, again y and gets 0 - User B total is 0.
- User A continues and hits y, gets 1 then quits with n. User A now has 6.
- B starts and gets 5 and he now has 5 and the game continues until anyone gets 40.


Explore and use any concepts and build the game.

### Note:
If you are facing any issues, 
- Make use of [discussions](https://github.com/kfuture2024/code-campus-level1/discussions/9) 
- Ask in the Wildr CodeCampus community. 
[Click here on your phone](https://wildr.com/invite/ioaN)
