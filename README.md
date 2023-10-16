# Ivory tower

## Features
The game rule is simple -- Be a professional programmer and fix bugs of a "Ivory tower".
Which support for at most 4 players and at least 1 player. This is a good game to play
with friends and familes.

## Design
I always wanted to develop a game by myself (I mean no any engine) so this would be my totoal first try.
This game is quite easy because it doesn't have networking and physics and other advanced topics, so
its develop curve would be quite flat. However it's also not quite so easy as well.

This project is written by C++. There are few things I have to overcome. First is renderer, I would use Vulkan here, since Vulkan is
modern and has a bright future also its performance is quite good (OpenGL maybe will come as a low performance mode and D3D12 and metal is on the way). 
Second is "audio" I would use "miniaudio" library for my game and modify some
code to adjust my purpose. Third is UI, I would use "RmlUI" which is a "HTML/CSS" based UI library it
can create many beautiful effects.

This is my personal project ofcourse, but in the future it could be a part of "SubIT lab" as well.

## Compiling
There are a few things that needs to be done

1. Install `VulkanSDK` on https://www.lunarg.com/vulkan-sdk/ choose your platform and install it straight forward.
2. Make sure you have installed `CMake` which is a cross -paltform C++ manager tool. Then run following commands in your terminal.
3. Run following code under your project's root folder.
```bash
mkdir build
cmake ..
```
4. Enjoy.

Enjoy the game.
## Screen Shots
## License
All source codes are under the MIT license, for more people to learn and play.