# Instructions

1. Install [crank](https://github.com/pd-rs/crank) `cargo install --git=https://github.com/pd-rs/crank`
2. `crank run`

----

 Based on [bevy_playdate](https://github.com/seurimas/bevy_playdate/). Thanks to some hacked dependencies for `no_std` support:
- https://github.com/Maximetinu/bevy/tree/nostd, forked from https://github.com/seurimas/bevy
- https://github.com/Maximetinu/instant/tree/nostd, forked from https://github.com/seurimas/instant
- https://github.com/Maximetinu/petgraph/tree/nostd, forked from https://github.com/seurimas/petgraph

For reference, Bevy support for embedded platforms like the Playdate is being discussed at https://github.com/bevyengine/bevy/discussions/10680.

See [this](https://github.com/bevyengine/bevy/discussions/10680#discussioncomment-8025944) and [this](https://github.com/bevyengine/bevy/discussions/10680#discussioncomment-9341710).
