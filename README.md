# Kazoo
Kazoo is a set of tools for Kahoot!

## Kahoot has fixed the infinite-name bug
But it's now broken again ;)

Kahoot added a nice JS variable to their index.js file; `maxCollaborationNameLength=15`. Kazoo now automagically swaps out this variable to 999999 length. (by rerouting the index.js request to the js branch of this repo, using jsdelivr.)


