# Awesome Arcade Coder

A repo for aggregating information, projects and whatever else relating to the Arcade Coder by Tech Will Save Us.

## Information

### [Discord](https://discord.gg/mqRF4cSS)

Place for asking questions quickly from other people, currently the bulk of information is here but the plan is to keep things as public as possible.

### [Arcade Coder Wiki](https://jake-walker.github.io/rs-arcade-coder/hardware/overview/)

A pretty thorough overview of the key operations of the board with some great visual prompts

### [Repo's wiki](https://github.com/padraigfl/awesome-arcade-coder/wiki)

A publicly editable wiki for dropping in information as you find things, someone will tidy it up as things mature.

### [Readme of original reverse engineering project](https://github.com/padraigfl/twsu-arcade-coder-esp32/blob/master/README.md)

Single page dumping ground of details on how the board operates and how it was reverse engineered. Likely has some assumptions which are incorrect.

## Projects

TODO: improve the ordering and scoping of this section when things are more formed. 

### [Arduino IDE library](https://github.com/padraigfl/twsu-arcade-coder-esp32)

The original reverse engineering project for the board. Library for handling inputs and rendering simple RGB matrix values to work with Arduino IDE. There is a lot of room for optimisation and the accelerometer has not yet been implemented.
The code has been written in deliberately simple C with minimal dependencies and can hopefully be a good reference point for future more-advanced libraries.

### [ArcadeCoder-Python](https://github.com/ItsJustAGitHubMichealWhosGonnaSeeIt5Ppl/ArcadeCoder-Python)

Builds upon the initial Arduino IDE discoveries to get the board working with CircuitPython. The accelerometer was fully reverse engineered first here.

### [rs-arcade-coder](https://github.com/jake-walker/rs-arcade-coder)

A very promising Rust library for the Arcade Coder with demos. Currently seems to be the most optimised library for the board.

## Credit

- https://github.com/bensleveritt - For both being basically the sole person regularly pushing to get people stopping these from being e-waste over the last few years and setting up the Discord 
- Middleparkers - For generously sharing dozens of Arcade Coders to developers on [Reddit](https://www.reddit.com/r/LinusTechTips/comments/1jgk9cr/how_can_i_stop_all_of_this_from_becoming_ewaste/), massively boosting the device's exposure in the process
- https://github.com/LukeMoll - Reverse engineering work and vital electronics experise
- https://github.com/ItsJustAGitHubMichealWhosGonnaSeeIt5Ppl - Reverse engineering work, CircuitPython implementation
- https://github.com/jake-walker - Reverse engineering work, Rust implementation and documentation
- https://github.com/padraigfl - For his efforts bringing everything together, kickstarting the project, and spearheading the findings
