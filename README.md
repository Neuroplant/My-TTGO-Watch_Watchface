
this is an Addon to https://github.com/sharandac/My-TTGO-Watch

### Replace "note" with Analog Watchface

in "src/gui/gui.cpp"

Line 34:
replace 
```
#include "mainbar/note_tile/note_tile.h"
```
with
```
#include "mainbar/watchface_tile/watchface_tile.h"
```

Line 68:
replace
```
note_tile_setup();
```
with
```
watchface_tile_setup();
```

copy Folder "watchface_tile" to "src/gui/mainbar"
