# Awesome Arcade Coder

A repo for aggregating information, projects and whatever else relating to the Arcade Coder by Tech Will Save Us.

Please check out the wiki and contribute if you have anything useful to share. It's early days now but we'll try to keep everything organised. We are looking for both projects around the device and information on the original firmware.

## Information

### [Discord](https://discord.gg/mqRF4cSS)

Place for asking questions quickly from other people, currently the bulk of information is here but the plan is to keep things as public as possible.

### [Readme of original reverse engineering project](https://github.com/padraigfl/twsu-arcade-coder-esp32/blob/master/README.md)

This is probably the most central point for information currently but that will change soon. This repository was not made by someone experienced in electronics and that likely shows.

### [Wiki](https://github.com/padraigfl/awesome-arcade-coder/wiki) (in progress)

A publicly editable wiki for documenting information in an organised manner. This is very early days but will hopefully become a central point for information.

## Projects

TODO: improve the ordering and scoping of this section when things are more formed. 

### [Arduino IDE library](https://github.com/padraigfl/twsu-arcade-coder-esp32)

Library for handling inputs and rendering simple RGB matrix values following the initial reverse engineering stages. There is a lot of room for optimisation and the accelerometer has not yet been implemented.
The code has been written in deliberately simple C with minimal dependencies and can hopefully be a good reference point for future more-advanced libraries.

### [ArcadeCoder-Python](https://github.com/ItsJustAGitHubMichealWhosGonnaSeeIt5Ppl/ArcadeCoder-Python)

Builds upon the initial Arduino IDE discoveries to get the board working with CircuitPython. The accelerometer was fully reverse engineered first here .

## Credit

People not mentioned elsewhere on this page who have been invaluable in getting this device revitalised. Please inform us if there's someone missing here or if someone wants to be removed.

- https://github.com/bensleveritt : For both being basically the sole person regularly pushing to get people stopping these from being e-waste over the last few years and setting up the Discord 
- Middleparkers: For generously sharing dozens of Arcade Coders to developers on [Reddit](https://www.reddit.com/r/LinusTechTips/comments/1jgk9cr/how_can_i_stop_all_of_this_from_becoming_ewaste/), massively boosting the devices exposure in the process
- https://github.com/LukeMoll : Reverse engineering work and vital electronics experise
- https://github.com/jake-walker : Reverse engineering work and documentation