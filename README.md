# Installing Node.js on WSL2

## Install Node Version Manager (NVM) on Ubuntu

Node Version Manager (NVM) is a tool that will allow you to download and install
multiple versions of Node.js, one of the environments for the JavaScript
programming language that we teach at Flatiron School. Installing NVM is the
first step in installing Node.js on your Ubuntu operating system.

### Action Item

1. Open the "Ubuntu" application using the "Start" menu
2. Type `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.36.0/install.sh | bash` and press `<Enter>`
3. Close the "Ubuntu" application
4. Reopen the "Ubuntu" application
5. Type `nvm` and press `<Enter>`

### Check Your Work

If you see a message ending with "Note: to remove, delete, or uninstall nvm",
continue below.

## Install Node.js on Ubuntu

For our JavaScript labs and lessons, we expect that students use Node.js on
Ubuntu. If Node Version Manager (NVM) has been successfully installed, you can
quickly install Node.js with a couple of commands.

### Action Item

1. Open the "Ubuntu" application using the "Start" menu
2. Type `nvm install node` and press `<Enter>`
3. Type `nvm list` and press `<Enter>`

### Check Your Work

<iframe width="560" height="315" src="https://www.youtube.com/embed/bOajXY2CMq4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you see a message starting with "-> v14.13.0", continue to the next lesson,
**Installing Databases on WSL2**.
