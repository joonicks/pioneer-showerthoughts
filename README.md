# pioneer-showerthoughts
Ideas and roadmaps for Pioneer


* One time use hyperdrive
- limited range 10ly?
- change device from "unused" to "burnt out" after use
- small mass (1t)


* mass transit overflow missions to nearby stars <10ly
    mass transit failed for some reason and X passengers need transit
    make "logical jump destinations" more likely to have "extra" missions
    if the player is going anyways, go with them


* large cargo missions (~100t?)

* passenger + cargo at once missions

* push fuel scooping as an event in lua instead of just adding hydrogen to cargo in C++

* push lack of cargo life support as lua event instead of handling it in C++

* MAJOR: change mass attributes to kg instead of tonnes

* rework engines to base everything on ISP instead of the current mishmash
    make ISP a difficulty setting

* make lua SpaceStation:Constructor() call "setDefaultStationProperties()"
    check each unique station for a custom settings json file
    set unique station identifier as "station charter license nr#"
    allow license to be visually overriden, like "Unlicensed"
    read Lore text from the same json file