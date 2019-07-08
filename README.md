# SSML-prosody-library
## A collection of pre-built speech synthesis settings used to convey emotion. 

Pre created prosody settings (Volume, Pitch, Rate) matched to theatrical voice descriptors, including terms like these:

- grumble
- ambivalent
- harsh
- sarcastic
- scornful
- arrogant
- impassioned
- indignant
- inquisitive
- sincere
- jovial
- solemn
- thoughtful
- elated
- threatening

---

## Example of "Excited" Prosody
```
<prosody rate="fast" pitch="high" volumn="loud">This voice is very excited!</prosody>
```

SSML can be tested using [IBM's interactive demo](https://text-to-speech-demo.ng.bluemix.net/)

---
# How to contribute
Any help would be much appreciated! I'm no expert in the human voice but this library may prove extremely useful to anyone developing a VUI tool.

Simply [add an xml document](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/) to the repository containing the prosody tag and attributes to emulate a style of voice. Make sure to name the document with your term. For example the above lives in excited.xml.
