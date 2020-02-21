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

## Contributing

### Rules
  1. Enjoy what you're doing
  2. If someone questions something you do, don't get feisty. Explain your thought process and they might learn from it
  3. Don't be a dick

### Git Flow

We use git flow to manage our branching workflow.
Default settings are used, but here they are if you want them:

```
[gitflow "branch"]
	master = master
	develop = develop
[gitflow "prefix"]
	feature = feature/
	release = release/
	hotfix = hotfix/
	versiontag = 
	bugfix = bugfix/
	support = support/
```

## License

See [LICENSE](./LICENSE)

## Credits

So far just me ;(
