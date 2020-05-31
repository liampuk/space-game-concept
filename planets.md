# Planets
> [<< back to readme](README.md)

A random number of planets is allocated to each star system. When generated planets have various properties, including atmosphere, resources and existing population. Planets are procedurally generated when a player enters the system. Settlements can be placed in locations on the planet, taking up space and exerting influence over the planet/system.

Planet surfaces can be displayed in different modes. Normal shows the terrain and location/size of settlements Geology mode displays patches of resources to give an overview of where to place settlements (ie. metal ores, soil nutrients).

## Terrain
Terrain is procedurally generated. This is inspired by an image from [Arvi "Hempuli" Teikari's blog:](https://www.hempuli.com/blogblog/archives/186)

![terrain](http://www.hempuli.com/blogblog/wp-content/uploads/2010/08/city.png)
> Img. 1

The terrain will have some influence over where resources generate

## Geology
Resources will generate in patches on the planet surface. Types of commodities will clump together during generation with different proportion (e.g. metal ores will clump with one main type). Types of generated resource patches are:

- Metal ores
- Coal
- Uranium
- Forests
- Oil

Different rock types will also be displayed, which will affect how large a settlement can grow in an area.

## Atmosphere
The atmosphere of a planet can be either habitable or non-habitable. Non-habitable planets require all buildings to have canopies which increases their cost to produce.

Atmospheres can also become polluted which will reduce population happiness.

## Claiming settlements
Settlements placed are visible to all players, and so each settlement takes up space, forcing players to explore further out into space to found a civ.

Each player is allowed 3 settlements per world, with the expectation that one is a hub, one is a mining outpost and one is a farming outpost. The location of each will affect how productive they are.

## Settlement growth
While settlements take up a small amount of space on the surface at first (like the crosses in Img. 1), they will grow over time removing space for other players to settle.

## Control of the planet
The bigger a settlement/the more productive it is, the more influence it will exert over the planet. The player who has the most control of the planet will gain various perks
- > TODO add perks for control of planet.

## Generation
Planets will be procedurally generated when first encountered by a player. They will then be added to the database. To keep the game size small (and if possible) only player modifications to the planets will be saved, their terrain will be generated each time they are visited by a player using a stable seed (system name, etc.).

## Attacking settlements
***This is a stretch goal***