# ortlinde

"Simple SDVX Konasute Launcher"

Simple, as in simple on the code side. Doesn't try to deal with complicated auth, multiple games, UI, etc. Instead just prompts for your cookie from the official site if expired.

For a more fleshed-out one (not an endorsement! I haven't ever even downloaded it!), https://github.com/anon5r/KsGameLauncher could be better.

I built this for myself to have a quick double click in to the game and easily auditable source code :)

## Usage

Build with `go build`, or find precompiled downloads here: https://github.com/NexerqDev/ortlinde/releases

Then simply follow the instructions given! You do require an existing SDVX Konasute installation, which should be automatically detected.

NOTE: Ortlinde will assume you want to bypass patching (the official launcher) and hop right into the game. However, if you do wish to launch into the launcher (i.e. to patch/adjust settings), please provide simply `launcher` as the first argument to Ortlinde and you will be launched in there instead.

## Licence

BSD-2-Clause
