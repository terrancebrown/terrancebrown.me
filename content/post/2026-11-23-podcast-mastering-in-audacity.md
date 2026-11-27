---
title: "Podcast mastering in Audacity, the long way round"
date: 2026-11-23
draft: false
description: "The full Audacity routine we used to turn raw FLAC recordings into a finished episode, dredged up from my old notes."
summary: "Mono mixdowns, aligning on the word biscuits, noise gates, compression and a test listener who listens to six minutes. The whole routine, from my old notes."
tags: ["podcasting", "audio", "audacity"]
---

Found these notes while clearing out old snippets: the complete routine we used to master podcast episodes in Audacity. Reading them back, I am struck by how much of it was ritual: the same sequence every episode, mostly because it worked and nobody wanted to renegotiate the liturgy mid-season.

It started with the file discipline. After recording, each person dropped their FLAC into `Dropbox/MAAPodcast/S09E00`, where the season and episode numbers lived in the folder name. Unromantic, but it meant we never lost an episode to naming chaos.

Then the routine proper:

1. **Mix down to mono.** Each track individually: Tracks, then Stereo Track to Mono. Nobody needs stereo breathing on a voice track.
2. **Align the tracks.** Everyone gets nudged until they line up on the "biscuits". Whatever the first spoken word was, that was the anchor. There is probably a joke in there about biscuits holding the whole operation together, and I am choosing not to make it.
3. **Noise removal** (called Noise Reduction on newer Audacity versions), applied per track.
4. **Gate, optionally.** If someone's track carried a lot of room noise, the Gate plugin silenced them between sentences. It never removed the noise entirely, it just stopped it from shouldering in while others spoke. Needed `swh-plugins` installed: `sudo apt install swh-plugins`.
5. **Equalisation**, per track.
6. **Remove peaks, optionally.** Tedious but worth it: flattening the worst peaks before compression gave a more uniform result. Amplify, then Repeat where needed.
7. **An editing listen**, hunting for the usual crimes.
8. **Compression.** Normalised the volume and, per my notes, made us sound sexier. Hard to argue with the results.
9. **Small volume trims** on each track's slider until everyone sat at roughly the same level.
10. **Panning.** Nudging tracks left and right with the L-R slider so voices occupied their own corners of the stereo field.
11. **A quick listen through**, both with and without headphones. Car listeners and kitchen listeners were the ones who complained when voices sat too quiet, and they were right.
12. **Save.** Always at this exact point. Ask me how I know.
13. **Mix and render**, then compressor, amplify, and Truncate Silence over the combined track.
14. **Export the selected audio** as FLAC, named `S09E00.flac`, season and episode numbers padded, always.
15. **The test listen.** Another member of the team checked the first three and last three minutes for sync and sound. Six minutes of quality control per hour of audio. It caught more problems than you would think.

Further reading, per the notes: microphonebasics.com's Audacity for podcasting guide.

I doubt I will run this exact routine again. Audacity has moved on, and so have podcasts, but the bones of it hold: mono voices, honest alignment, compress last, listen like someone in a car.
