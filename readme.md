```

 /$$   /$$ /$$$$$$$         /$$$$$$        /$$$$$$$$ /$$
| $$  / $$| $$__  $$       /$$__  $$      | $$_____/|__/
|  $$/ $$/| $$  \ $$      |__/  \ $$      | $$       /$$  /$$$$$$  /$$$$$$/$$$$   /$$$$$$
 \  $$$$/ | $$  | $$        /$$$$$$/      | $$$$$   | $$ /$$__  $$| $$_  $$_  $$ |____  $$
  >$$  $$ | $$  | $$       /$$____/       | $$__/   | $$| $$  \ $$| $$ \ $$ \ $$  /$$$$$$$
 /$$/\  $$| $$  | $$      | $$            | $$      | $$| $$  | $$| $$ | $$ | $$ /$$__  $$
| $$  \ $$| $$$$$$$/      | $$$$$$$$      | $$      | $$|  $$$$$$$| $$ | $$ | $$|  $$$$$$$
|__/  |__/|_______/       |________/      |__/      |__/ \____  $$|__/ |__/ |__/ \_______/
                                                         /$$  \ $$
                                                        |  $$$$$$/
                                                         \______/
```

Makes textboxes crossover nicely from XD to Figma. Essentially a wrapper around one long regex that replaces \<tspans> that should have been enters, so that makes svgs copied from XD work nicer with Figma. Everything else works by itself , this was the only hurdle porting over stuff so hopefully this fixes it. Might get a few ghost enters in a few edge cases but I don't feel like working too much on them.
