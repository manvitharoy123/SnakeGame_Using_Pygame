# SnakeGame_Using_Pygame
A snake game written in Python using the Pygame library
Also you can adjust the difficulty level at the start 
You can add your own custom background ,color,shape(may be rectagle,square,circle with radius)
<img width="554" alt="1" src="https://user-images.githubusercontent.com/71482396/133750617-0a60df1e-5901-4e78-8ee7-0c4bcdc1c414.png">
<img width="541" alt="2" src="https://user-images.githubusercontent.com/71482396/133750630-9e282ca1-6f91-4fb0-a97f-b8f7b4bf59e8.png">
You can alter the background using:

game_window.fill("Your color")

pygame.draw.rect(game_window, blue, pygame.Rect(pos[0], pos[1], 10, 10))
#for rectangle shape

replace draw.rectangle with draww.circle to get the shape of a circle with constraints (game_window, red, [food_pos[0], food_pos[1]],5)   
#first one represents screen, second represents the color , the fourth one represents the radius 

