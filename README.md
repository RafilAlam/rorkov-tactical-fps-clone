# Repository Installation

    Download Node from https://nodejs.org/en

    After installation, paste this into the command line: npm install -g npm@9.8.1

    In the same session, paste: npm install -g roblox-ts

    Install Aftman from https://github.com/LPGhatguy/aftman/releases, extract it, run the .exe, then open a terminal and type: aftman self-install

    Paste this command in the terminal and wait for the Rojo server to install: aftman add rojo-rbx/rojo

    Paste: aftman install

    Go to GitHub and set up your SSH key

    Download the latest Roblox place file without scripts

    Open the installed place file

    Install the Rojo plugin from https://rojo.space/docs/v7/getting-started/installation/ > "Installing the plugin" > from Roblox.com

    Clone the repo using git clone [SSH link from GitHub (Code > Clone > SSH)]

    Open a terminal session in your IDE and paste: npm i

    After packages finish installing, paste: npm run watch

    Open another terminal session and paste: rojo serve

    Go to the Roblox place and connect the plugin to the Rojo server

    Start coding

# Writing Code

    Define types using PascalCase

    Define classes using PascalCase

    Use camelCase for functions, variables, etc.

    Name files using snake_case

# npm Scripts
## npm run devbuild

Compiles the project to Lua, creates a devbuild.rbxl file with all game models, and opens it in Roblox Studio. Use only if you don’t have a place with the current models.
## npm run build

Compiles the project to Lua and immediately starts the Rojo server. Use when you already have a place with models and want to test your code.
## npm run watch

Runs rbxtsc in watch mode — recompiles every time a file is saved or created in the project folder.
