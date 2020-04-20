# Pong-using-Lua:fire:
2D Pong game using Lua

# Installation :building_construction:
1. Download love2d. https://love2d.org/#download
2. For getting started with love2d visit https://love2d.org/wiki/Getting_Started
3. Install Sublime Text https://www.sublimetext.com/
4. Visit the link in point 2 to learn basics 
5. Save the code with `.lua` extension
6. Run the basic code on Sublime Text by going to Tools -> Build System -> Lua
7. press CTRL+B
8. If it doesnt work go to Tools -> Build System -> New Build Systems 
9. Type According to your system
# For Windows
`{
    "selector": "source.lua",
    "file_regex": "^Error: (?:[^:]+: )?([^: ]+?):(\\d+):() ([^:]*)$",
    "windows": {
        "cmd": ["C:/Program Files/LOVE/love.exe", "${folder:${file_path}}"],
        "shell": true
    }`
# For MAC    
    `"osx": {
        "cmd": ["/Applications/love.app/Contents/MacOS/love", "${folder:${file_path}}"]
    }`
# For Linux    
    `"linux": {
        "cmd": ["love", "${folder:${file_path}}"]
    }`
10. Save with extension `.sublime-build`    
11. press CTRL+B
# Contributors :construction_worker:

* [KARAN](https://github.com/FlashTech-dev)

Made with :heart: by [Karan](https://github.com/FlashTech-dev).


Inspired by CS50's Intro to Game Development from Harvard University.
