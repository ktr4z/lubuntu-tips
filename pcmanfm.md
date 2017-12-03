# pcmanfm

## Open new window by default
Edit file `/usr/share/applications/pcmanfm.desktop`:
Change

    Exec=pcmanfm %U

To

    Exec=pcmanfm -n %U
