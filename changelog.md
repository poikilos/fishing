# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),


## [git] - 2021-11-27
(Poikilos)

### Added
- Add coral5 (green) (as per Echoes91 ethereal).

### Changed
- Revert seaweed harvesting from 1 in 4 to 1 in 5 so this mod doesn't have weird differences from ethereal (as per Echoes91 ethereal).
- Revert worm recipe from 4 to 2 dirt so this mod doesn't have weird differences from ethereal (as per Echoes91 ethereal) and MinetestForFun fishing.

### Fixed
- Fix capitalization and grammar for the "Your fish got away..." to make it easier to comprehend at a glance.
- Change `sel` to a local variable in sealife.lua (as per Echoes91 ethereal).
- Revert "fishing:sandy" to drop "default:sand" since "fishing:sandy" is a mapgen node for generating seaweed so possessing it would generate free seaweed forever (as per Echoes91 ethereal).


## [simple_fishing] - 2014-09-15
(Changes by Xanthin vs last Echoes91/ethereal, as noted by Poikilos)

### Changed
- Change the namespace to fishing.
- Make "fishing:sandy" drop itself instead of "default:sand"
- Make seaweed drop 1 in 4 chance not 1 in 5 (vs Echoes91)
- Move the sashimi recipe to seaplants.lua so that if seaplants.lua
  doesn't run, there won't be a recipe with an unknown node
  ("fishing:seaweed").
- Change the worm recipe from 2 dirt to 4 dirt.
