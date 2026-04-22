# Lisens

QBCore Framework
Opphavsrett (C) 2021 Joshua Eger

Dette programmet er fri programvare: du kan redistribuere det og/eller endre
det under vilkårene i GNU General Public License som publisert av
Free Software Foundation, enten versjon 3 av lisensen, eller
(etter ditt valg) en senere versjon.

Dette programmet distribueres i håp om at det vil være nyttig,
men UTEN NOEN GARANTI; uten engang den implisitte garantien om
SALGBARHET eller EGNETHET FOR ET SPESIFIKT FORMÅL. Se
GNU General Public License for flere detaljer.

Du skal ha mottatt en kopi av GNU General Public License
sammen med dette programmet. Hvis ikke, se https://www.gnu.org/licenses/


## Dependencies
- [ox_lib](https://github.com/CommunityOx/ox_lib)
- [qbx_core](https://github.com/Qbox-project/qbx_core)

## Screenshots
![Spawn selector](https://i.imgur.com/nz0mPGe.png)

## Features
- Ability to select spawn after selecting the character

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure ox_lib
ensure qbx_core
ensure qb-spawn
```

## Configuration
An example to add spawn option
```
QB.Spawns = {
    ["spawn1"] = { -- Needs to be unique
        coords = vector4(1.1, -1.1, 1.1, 180.0), -- Coords player will be spawned
        location = "spawn1", -- Needs to be unique
        label = "Spawn 1 Name", -- This is the label which will show up in selection menu.
    },
    ["spawn2"] = { -- Needs to be unique
        coords = vector4(1.1, -1.1, 1.1, 180.0), -- Coords player will be spawned
        location = "spawn2", -- Needs to be unique
        label = "Spawn 2 Name", -- This is the label which will show up in selection menu.
    },
}
```
