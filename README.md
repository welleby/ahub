# **ahub**
**Ahub** is a:
- Multiroom-audio-sync-system
- A free multiroom-speaker-solution
- A system to be used in combination with any active speaker as an alternative to commercial products like Sonos or Bose SoundTouch
- Pretty much a free alternative to https://www.thisisbeep.com/ 
- Based on Java for portability
- 100% compatible with RaspberryPi (In fact, developed with the RaspberryPi in mind)

Okay, but what does it do?
**Ahub** is a classical client-server-system. 
The clients are called ANodes. The ANodes are supposed to be running on a system that is connected to an active speaker.
The **Ahub**-server is a lightweight server which broadcasts any audio stream to a set of ANodes.
The clients can be configured with a delay to make a neat multiroom sound-experience.

Example setup:
- PC or SmartPhone running Spotify and **Ahub**-server
- RaspberryPi#1 running **Anode**-client, connected to an active speaker in the kitchen.
- RaspberryPi#2 running **Anode**-client, connected to an active speaker in the living room.
- RaspberryPi#3 running **Anode**-client, connected to an active ceiling speaker in the bathroom.