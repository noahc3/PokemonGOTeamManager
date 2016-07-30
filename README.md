# Pokemon GO Team Manager

View and manage your Pokemon GO accounts from your PC

Note that the code is a big garbled mess. I've never made something using two (arguably terrible) languages before. I began working on this before API's for Java and C# were available.

##Submitting an Issue

Before creating an issue, **make sure you are always running the latest version from the [release tab!](https://github.com/noahc3/PokemonGoTeamManager/releases)**

IF you are having an issue with logging in, please edit auth.bat, and on a new line put the word 'pause' (no quotes ofc). Then, submit an issue with a SCREENSHOT of the full command prompt window, and please upload the contents of output.txt to pastebin or paste.ee (or similar). **Always create a new issue!!!**

OTHERWISE, simply submit an issue describing what you were doing when the error occurs, and please upload the contents of output.txt to pastebin or paste.ee (or similar).

## Running and Compiling the Source Code
If you are a user and not a developer, grab the binaries from the releases tab or https://s3.amazonaws.com/noahc3-go/manager.html!

The applications GUI is built in Autohotkey. It should be compatible with any autohotkey_L version (1.1.xxx, tested with Autohotkey 1.1.22.09) Install autohotkey, Python 2.7, PIP, and make sure all requirements from \libs\requirements.txt are installed (Install Dependencies.ahk should do this for you). Run auth.ahk to use the application.

To compile, use ahk2exe on auth.ahk, tv.ahk (Install Dependencies.ahk optional, not needed to function). Run the compiled auth.ahk to use. DO NOT compile any ahk files in \libs\!

## Credits

tejado - pgoapi https://github.com/tejado/pgoapi

TehDing - Pokemon GO Python API https://github.com/rubenvereecken/pokemongo-api
