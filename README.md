
# obsidian.js

obsidian.js is a Minecraft server written in [Coco](http://satyr.github.com/coco/),
aiming for extensibility and being fun to play around with as a developer.


## What can it do?

- Parse and compile all packets except enchantments, hopefully
- Login, complete with authentication
- Chunk sending, currently only a finite flat plane
- Players can see each other


## Running

Get [Node.js](http://nodejs.org/) if you don't have it already.  
Install [Coco](http://satyr.github.com/coco/): `npm install -g coco`  
Run it: `coco src/main`
