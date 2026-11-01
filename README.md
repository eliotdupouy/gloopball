# Gloopball

A jelly sport in the browser. Drive up the walls, boost, flip and fly, and sink a big bouncy ball into the other team's hole.

**Play: https://eliotdupouy.github.io/gloopball/**

- **Against bots:** pick a mode and press Play kickoff.
- **Against a friend:** pick "A friend online", copy the link and send it. When you're both in, press Ready and the 1v1 starts.

Modes: **Sinkhole** (the goals are holes in the floor) and **Classic** (wall goals). With **Spikes** on, the ball sticks to you when you pop them: carry it and dunk it in their hole, or spit it. Spikes work online too.

Runs on WebGPU, with WebGL2 as a fallback. Online play goes peer to peer over WebRTC, using PeerJS's free public server to find each other.
