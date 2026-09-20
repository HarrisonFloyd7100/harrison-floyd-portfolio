This folder holds the media the site links to. Nothing here is required for
the site to work — every reference below is optional and just fills in a
placeholder that currently shows as a bordered "add media" box.

Resume
------
assets/resume.pdf
  Your resume, exported as a PDF. On your Google Site it's currently named
  HarrisonFloyd_Resume_PostSummer_2026.pdf — rename it to resume.pdf, or
  keep its original name and update the href in the Resume section of
  index.html to match.

Project media (all optional — used in the placeholder "media" boxes)
----------------------------------------------------------------------
Unreal Engine 5 — Ninja Night
  media/ninja-night-combat.mp4      (tech demo trailer / combat footage)
  media/ninja-night-wallrun.jpg     (wall run start logic screenshot)

Unreal Engine 5 — AI and Networking Horde Shooter
  media/horde-shooter-demo.mp4      (tech showcase video)
  media/horde-shooter-animtree.jpg  (animation tree blueprint overview)
  media/horde-shooter-transition.jpg (unarmed-to-rifle walk transition)

Godot 4 — Physics Collision Simulation
  media/physics-sim-playthrough.mp4
  media/physics-sim-code.jpg

Godot 4 — 2D Coin Collector
  media/coin-collector-playthrough.mkv
  media/coin-collector-code.jpg

AWS — Database Synch
  media/aws-canvassync-arch.jpg
  media/aws-trainingsync-arch.jpg

Robotics Coursework — Gateway to Robotics
  media/spot-leg-ik.mov

Combat Robotics — The Baja Bunny
  media/baja-bunny-photo.jpg
  media/baja-bunny-fight.mp4

To actually show an image or video instead of the placeholder box, replace
the relevant <div class="media">...</div> block in index.html with an
<img src="assets/media/your-file.jpg" alt="..."> or
<video src="assets/media/your-file.mp4" controls></video> tag.
