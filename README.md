# hydrant

hydrant is a fully open source implementation of a Minecraft server for 1.12.2

## Plans
  - Modularity (core, worldgen etc...)
  - Use of free (as in freedom) software libraries
  - Less use of abstraction in favour of performance
  - Extensible via Lua or alternative scripting language
  - Reduced memory footprint:
    - Compression of idling chunks
    - Optimized active chunk storage
  - Improved entity management:
    - Reduced ticking when not close to player/active entity
    - "Smart AI" (yeah, good luck with that one)
  - Improved player resource management

## Progress
  - [ ] Server thread starts
  - [ ] Shows in server list (responds to ping)
  - [ ] Client can authenticate with server
  - [ ] Client can load into empty world
  - [ ] Player can move
  - [ ] Player can interact with blocks
  - [ ] Multiple players can see same world state
  - [ ] Multiple players can interact with update on all clients
  - [ ] More to come...

## Credits

So far just me ;(
