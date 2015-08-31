## Manually wget'd all of the highest somafm mp3 stream playlists for the convenience of having in a single directory --- with appeal to those of us who may not wish to have one extra browser window open and instead relegate that function to one more open terminal for posterity's sake.

```
for i in http://somafm.com/bootliquor.pls http://somafm.com/metal.pls http://somafm.com/brfm.pls http://somafm.com/fluid.pls http://somafm.com/seventies320.pls http://somafm.com/groovesalad.pls http://somafm.com/defcon.pls http://somafm.com/spacestation.pls http://somafm.com/dronezone.pls http://somafm.com/lush.pls http://somafm.com/digitalis.pls http://somafm.com/indiepop.pls http://somafm.com/bagel.pls http://somafm.com/thistle.pls http://somafm.com/folkfwd.pls http://somafm.com/bootliquor.pls http://somafm.com/7soul.pls http://somafm.com/earwaves.pls http://somafm.com/missioncontrol.pls http://somafm.com/illstreet.pls http://somafm.com/beatblender.pls http://somafm.com/sf1033.pls http://somafm.com/doomed.pls http://somafm.com/covers.pls http://somafm.com/u80s192.pls http://somafm.com/thetrip.pls http://somafm.com/cliqhop.pls http://somafm.com/dubstep256.pls http://somafm.com/poptron.pls http://somafm.com/secretagent.pls http://somafm.com/sonicuniverse192.pls http://somafm.com/suburbsofgoa.pls http://somafm.com/deepspaceone.pls; do echo $i; wget $i; done
```

```
mplayer -playlist bootliquor.pls
```
