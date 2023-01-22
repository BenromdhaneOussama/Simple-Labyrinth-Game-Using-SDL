# Simple-Labyrinth-Game-Using-SDL
Simple Labyrinth Game Using SDL with a maze generation algorithm


# Test
![test](https://user-images.githubusercontent.com/61565747/213939115-38089106-f6a5-405f-a4a4-f00b3ee287c7.gif)

# Maze generation
Different outcome every time (3 examples)

![random](https://user-images.githubusercontent.com/61565747/213938995-a9413030-a3eb-431c-8719-e4d71cb104ed.gif)

# Clipping
Added clipping to avoid impossible scenarios

![clipping](https://user-images.githubusercontent.com/61565747/213939063-4c36fee2-575f-4109-b0b3-568e7f1f5557.gif)






# How to install/play (linux)
Prerequisites:<br>
sudo apt-get install libsdl1.2-dev <br>
sudo apt-get install libsdl-image1.2-dev <br>
sudo apt-get install libsdl-mixer1.2-dev <br>
sudo apt-get install libsdl-ttf2.0-dev <br>



Code compilation: <br>
gcc generate_laby.c functions.c laby_main.c constantes.h affichage.h algorithme.h -o prog -lSDL -lSDL_image -lSDL_mixer -lSDL_ttf


Execution:
./prog
