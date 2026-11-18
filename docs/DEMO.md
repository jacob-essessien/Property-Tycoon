# Property Tycoon demo notes

[Existing gameplay video](media/gameplay.mp4) · [Video still](media/gameplay-still.jpg)

The 20-second MP4 was already present in public commit `c94973c`. It shows the home
screen, player/token selection and opening turns using scripted input. The new
JPEG is extracted at 14 seconds from that file; it is not a new gameplay capture.

On **17 November 2026**, the repository was downloaded into an isolated checkout,
Pygame 2.6.1 was installed and `python -X utf8 -m property_tycoon` launched the home
window. The native capture tool rejected its window binding, so the existing video
was retained instead of claiming a successful new recording.

`python -B -m unittest discover -s tests -v`: **11 tests passed** under Python
3.12.14. These are focused regressions, not certification of a complete match.
The bankruptcy, shared-state and endgame limitations in [KNOWN-ISSUES.md](KNOWN-ISSUES.md)
remain applicable.

For a live walkthrough, follow the README's launcher instructions: Full Game,
player count, token selection, Play, then roll dice and pass GO before purchasing.
Keep the group-project attribution visible when presenting the demo.
