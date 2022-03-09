# threemc-orderly-image

[![Build status](https://badge.buildkite.com/6a023cde961638e7779fe0458d216e582f98181b37d2d4e519.svg)](https://buildkite.com/mrc-ide/threemc-orderly-image)

This is the docker container for [mrc-ide/threemc-orderly](https://github.com/mrc-ide/threemc-orderly).

This repo is a fork of [`montagu-orderly`](https://github.com/vimc/montagu-orderly) with minor modifications

**Interaction with the server**.  These commands interact with the orderly server on the *same host* as you run it.  If you run these on your desktop they will not affect any other machine.

Make sure you have the most recent version of the container with with

Update the `https://github.com/mrc-ide/threemc-orderly` repo on the orderly volume

```
./pull_sources
```

Run orderly commands with

```
./orderly run <name>
./orderly list names
./orderly --help
```

etc.

Get a shell on the container with

```
./shell
```

## Building the image

The image is built on [Buildkite](https://buildkite.com/mrc-ide/threemc-orderly-image)
