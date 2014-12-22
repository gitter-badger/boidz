# Haxe Boids

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mlms13/boidz?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is a Haxe implementation of the Boids flocking algorithm.

[Canvas Demo](https://rawgit.com/fponticelli/boidz/master/bin/index.html)

## Running It

Assuming you've installed [Lime and OpenFL](http://www.openfl.org/documentation/setup/install-haxe/), you can run the boids simulation with `lime test <platform>` where `<platform>` is one of the targets listed in `lime help`.

Currently, the boids fly toward the center, then leave the frame. Coming soon: speed limitations and boundary constraints. Until then, enjoy a couple seconds of boid flocking.
