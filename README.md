# Simple-Labyrinth-Game-Using-SDL
Simple Labyrinth Game Using SDL with a maze generation algorithm


# Test
https://user-images.githubusercontent.com/61565747/213938393-45997596-a02a-4293-9287-9a5f3486a218.mp4

# Maze generation
Different outcome every time (3 examples)
https://user-images.githubusercontent.com/61565747/213938642-86812502-6c86-4297-9062-36568385e998.mp4

# Clipping
Added clipping to avoid impossible scenarios
https://user-images.githubusercontent.com/61565747/213938731-f65d1784-d50b-4e96-b4f1-cb304ed6a0f7.mp4






# How to install/play (linux)
Prerequisites:
sudo apt-get install libsdl1.2-dev
sudo apt-get install libsdl-image1.2-dev
sudo apt-get install libsdl-mixer1.2-dev
sudo apt-get install libsdl-ttf2.0-dev



Code compilation:
gcc generate_laby.c functions.c laby_main.c constantes.h affichage.h algorithme.h -o prog -lSDL -lSDL_image -lSDL_mixer -lSDL_ttf


Execution:
./prog
