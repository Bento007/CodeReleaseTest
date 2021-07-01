## Experiment

how does commitizen affect my code and release history

adding change 1!

locally we bump a tag and cut a release

If we would like to generate release notes here is my first steps solution:
1. use conventionalcommit message :white_check_mark:
1. setup commitizen for whichever data portal
1. whenever we do a release to prod run cz bump --changelog . This will tag the current branch with a new version based on the commits since the last tag.
