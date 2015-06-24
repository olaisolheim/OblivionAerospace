# Oblivion Aerospace Pack

A small parts package of heat shields for Kerbal Space Program (KSP) that also works with the Deadly Reentry (DR) plugin by Starwaster.

Features:
* Currently features the *Conical Heat Shield* inspired by the sphere-cone heat shield on the Mars Science Laboratory.
  * Comes in three sizes: 1.25m, 2.5m, and 3.75m.
  * Works great with Ferram Aerospace Research (FAR) by ferram4, in that sphere-cone shaped heat shields offer greater control (by lift) over blunt ones.
  * Comes with an auto-shroud adapter that meets flush with the shield. It works just like the stock heat shields. Just add something to the heat shield's bottom node (like a decoupler) and the shroud/adapter will appear!
  * Supports the Deadly Reentry plugin by Starwaster, based on the works by NathanKell, ialdabaoth (who is awesome), and r4m0n.
  * Unlike the heat shields in DR, the Conical Heat Shield does not have an omni-decoupler. Instead, it has a single decoupler on the top attachment point (yellow/black ring), allowing for more custom designs.

Known issues:
* Stock KSP has an issue with rescaleFactor on root parts. Since this mod uses rescaleFactor, you should avoid using these shields as the root part on your vessel.

Future:
* More heat shields based on real-life ones, like a Galileo-style reflective heat shield.
* I've been playing with the idea of a giant heat shield with a "hatch" at the center, allowing for engines to fire through it once the hatch is open, allowing for a more realistic spaceship design with g-forces pointing the same direction during both burns and aerobraking (like the one in BBC's documentary Space Odyssey: Voyage to the Planets).
* I have plans on making all heat shields tweakable in size, like the brilliant Procedural Fairings mod by e-dog.

Thanks to...
* ialdabaoth and r4m0n, for creating the excellent Deadly Reentry mod, and to NathanKell and Starwaster for extending upon and maintaining it. Reentry would be boring without it!
* ferram4, for creating Ferram Aerospace Research, which really makes the KSP experience for me!
* Squad, for making such a great game! (And now finally stock heating!)
* Hattivat, for testing.

License is CC BY-SA (see `LICENSE` for details).

[![CC BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

License for ModuleManager is CC SA, maintained by sarbian, original copyright by Ialdabaoth (see `README_ModuleManager.md` for details).

[![CC SA](https://i.creativecommons.org/l/sa/1.0/88x31.png)](http://creativecommons.org/licenses/sa/1.0/)

# Installation

Install by merging the `GameData` folder in the zip with the `GameData` folder in your KSP install.

* I highly recommend Deadly Reentry for more realistic re-entry and heating.

# Changelog

**v0.1.5**
* Maintenance release to support KSP 1.0.4.
* Tweaked heat shield configurations to reflect changes in stock heat model.

**v0.1.4**
* Maintenance release to have the heat shields support stock heating. Does not support DR until Starwaster releases a version compatible with KSP 1.0 in a few days.
* Not backwards compatible with previous versions of this mod (if you really, really need this, send me a message on the forums and I'll help you fix your save so it magically works with the new version :)).
* Command Pod Heat Shield still in the works, but textures are WIP, so I moved it to v0.2.0 (alpha for it shortly).
* Oh, and the mod is using ModuleManager now. :)

**v0.1.3**
* Corrected the bottom node size of all three heat shields and tweaked some reentry parameters. Many thanks to Hattivat for testing and pointing this out. :)

**v0.1.2**
* Added an auto-shroud to the Conical Heat Shield. It works like an engine shroud. Just add something to the heat shield's bottom node (like a decoupler) and the shroud/adapter will appear!

**v0.1.1**
* Added the Duna Exploration Rover example craft using the Conical Heat Shield for reentry. (You'll need the Procedural Fairings mod by e-dog.)

**v0.1.0** Initial release.
* Added the Conical Heat Shield.

