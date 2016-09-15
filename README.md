[![Build
Status](https://travis-ci.org/nickbabcock/boxcars.svg?branch=master)](https://travis-ci.org/nickbabcock/boxcars)

# boxcars

[Boxcars](https://github.com/nickbabcock/boxcars), also stylized as boxca-rs,
is an example of a [Rocket League](http://www.rocketleaguegame.com/) replay
parser written in [Rust](https://www.rust-lang.org/en-US/) using
[nom](https://github.com/Geal/nom) for parsing and
[serde](https://github.com/serde-rs/serde) for serialization. As stated in the
title, this is an example, as this library in no way competes with the other
feature complete parsers such as [Octane](https://github.com/tfausak/octane)
and
[RocketLeagueReplayParser](https://github.com/jjbott/RocketLeagueReplayParser).
Rather, let boxcars be a good example of Rust code using nom, and serde as
extensive examples are hard to come by. While lacking feature completeness and
user friendly error message -- [among other
issues](https://github.com/nickbabcock/boxcars/issues), tests and documentation
strive to be thorough.

Library currently only compiles on Rust nightly. The code is well documented,
give it a read!

Parses and outputs JSON data from replay in 1-2ms, but your mileage may vary.