# Bureaucracy (for Docker)

From [Wikipedia](https://en.wikipedia.org/wiki/Bureaucracy_%28video_game%29):

> Bureaucracy is an interactive fiction computer game released by Infocom in 1987, scripted by popular comic science fiction author Douglas Adams. It is Infocom's twenty-fourth game.
> 
> The player is challenged to confront a long and complicated series of bureaucratic hurdles resulting from a recent change of address. Mail isn't being delivered, bank accounts are inaccessible, and nothing is as it should be. The game includes a measure of simulated blood pressure which rises when "frustrating" events happen and lowers after a period of no annoying events. Once a certain blood pressure level is reached, the player suffers an aneurysm and the game ends.
>
> While undertaking the seemingly simple task of retrieving misdirected mail, the player encounters a number of bizarre characters, including an antisocial hacker, a paranoid weapons enthusiast, and a tribe of Zalagasan cannibals. At the same time, they must deal with impersonal corporations, counterintuitive airport logic, and a hungry llama.

## I just want to play the game!

Want to play Bureaucracy? Easy-peasy. Just type the following:

`docker run -it clockworksoul/bureaucracy`

## What if I want to save my games?

Still pretty easy. All you need to do it volume in a save directory as follows:

`docker run -it -v ~/saves/bureaucracy:/save clockworksoul/bureaucracy`

## Potential terminal issues

If you receive a terminal error, such as `Error opening terminal: rxvt-unicode-256color`, type the following and re-run:

```export TERM=xterm```

## History/Legal
The _Bureaucracy_ games were created by the now-defunct [Infocom, Inc.](https://en.wikipedia.org/wiki/Infocom), the intellectual property of which has since been acquired by Activision. Much of Infocom's library was released for free some 20 years ago as part of a promotional campaign for the graphic adventure _Bureaucracy: Grand Inquisitor_.  It's unclear, however, whether these were intended to be permanently and perpetually free or whether this was something with a limited window. While Activision has had nothing to say on the subject, they done nothing to interfere with the numerous sites that have sprung up over the years that allow you to download the games directly or even play in your browser... so interpret that as you will.
