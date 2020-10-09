                            ========================= BATTLESHIP APP =========================
            
* Initial project planning: While learning web development in self isolation, I discovered the Battleship game to be a very good learning experience that has different functionalities and logic that can make me understand algorithms even better. I then decided to try and re-create the game myself.

* Summary: in order to play, the player has to select a letter from the alphabet from A-H that represents a particular column, and then select a number from 1-7 which altogether will be the player's guess on the board of the game. If the guess is correct, a location of a ship is hit. If it is incorrect, it is a miss. The game ends when all locations of all ships are hit and the player is able to see how many tries it took to finish the game.


* Development experience: The game follows an MVC sctructure, where the model, view and controller are separate objects that have their own responsibilities. It was quite difficult to find ways how to divide the logic between them and make them work together and a lot of errors were present. I started with the creation of the view object first, and then ensured quality assurance by testing if the game displays the correct information if I hardcode the numbers at first. I then followed with creating and testing the model, and finally the controller. Each object has different responsiblities, and the biggest challenge I would say was figuring out how to programme the controller in order to process a guess, ensure it is a correct guess and pass it on to the model. The experience of writting the game was very rewarding and exciting to follow through.

* Bugs: When I hit a location of one of the ships, if I re-enter that board location again, it results another hit at the same spot. 

* Future improvements: If I could improve the game in future times, I would add sound effects when a ship is sinked or an animation on the grid that displays a sinking ship. I would probably also add a level system where the harder the level, the larger the game with a bigger number of ships to target.


                        ========================== Project plan deliverables =======================
                                    
* Scope: 
01 - What are you aiming to build? - browser based battleship game
02 - What features will it have? - A grid on the page where the view will update depending on guess, a message box that displays "Hit", "Miss", "Sunk ship" and an input where player can submit guess
03 - What do you think you can implement in the time period? - Implement all three objects of the game mechanics, style game and make it easy to play


            




