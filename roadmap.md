# Roadmap <!-- docsify ignore-all -->

## Collection of ideas and milestones

This will be an ever changing list of goals towards certain milestones, like an alpha build, which I personally consider to be a state in which the game is playable start to finish, but lacks content and  polish.

This list is in no particular order as what I currently work on implementing is heavily dependent on what I feel like doing and any attempt at following any strict "task list" will fail miserably and make want to progress less.

Chaos is my way.

## Current goals

- Introduce overworld map, cities, caves, forests, lakes and others.
    - Add minimap?
- Introduce aquifers to current procgen algorithm
- Expand procgen with new generation methods outside of just cellular automata:
    - Room generators, tree or graph based
    - Door-n-key generators
    - Some noise based generation for various bits like forests
    - Co-join some of them to work together on one map (map that has some rooms inside a cave, for a goblin camp of sorts, for example)
- Improve loot generation
- Add more advanced  AI and mob types
- Add interactions between AI driven entities and world (not only AI and player, this one is already achieve partially through Goblin type enemy)
- Add end goal
- Improve handling of non-hostile entities
- Stats system (more complicated one)
- Improve interface (bare bones for now)
- Graphical tiles
- Configurable settings and graphics

## Goals completed

- Performance improvements to cellular automata
- More "sane" mimic handling
- Interactable objects with their own handler and component
- Joining of separated map elements
- Saving and loading
- Inventory and items (added to player)
    - Add inventory to enemies with drops on death
