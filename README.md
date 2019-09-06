# No Mo' Expo FOMO

Expo is built on React Native which is built on react + js + Android + iOS + web. When any innovation happens in any one of those stacks, there can be considerable lag time before adoption and support in Expo.

This is a dumping ground of me trying to hack support of various technologies into Expo with react-native-web support when possible.

To demonstrate the minimal path to setting up each tech, all setups will be done in branches / PRs that target `master`. The `master` branch will exist only as a starter Expo project and this README.

Most hacks require changes in dependencies so I rely heavily on the wonderful [patch-package](https://github.com/ds300/patch-package). When I add a patch to a compiled dependency, I'll add the diff to compiled bundle as well as duplicate it to the source for readability if source is included in the package.

Ideally, I'll find a way to turn the hacks into proper upstream fixes, but when that's not possible, I hope this serves as a useful guide to get some things working:

TODO:

- [ ] Cavy
- [ ] Miragejs
- [ ] react-navigation@5
