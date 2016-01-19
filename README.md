# Sel Follower

A short command line utility which polls X Selection buffers, and outputs changing values.

# Example

Git clone every link copied into the clipboard:

`sel-follower -b | xargs -n1 git clone`
