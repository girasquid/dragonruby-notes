# dragonruby-notes

My notes on Dragonruby. https://dragonruby.org/

## Things to know

- resolution is always 1280x720, it is resized and scaled for you (hard-code your pixel positions!)
- x,y coordinate position starts from the bottom left
- ticks are (almost always) 60 per second, code is run 60 times per second. Don't need to write anything involving delta time.

## Doing upgrades

```bash
luke@dreambridge ~/projects/platformer
 % rsync -av --progress ~/Downloads/dragonruby-macos/ . --exclude mygame
```