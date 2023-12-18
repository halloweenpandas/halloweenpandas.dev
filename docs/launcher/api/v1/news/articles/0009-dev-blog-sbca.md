---
type: dev-blog
title: Special Beam Cannon (Awakening)
banner: Blue Space Wallpapers.jpg
authors:
- chaosbeat
release: "2023-06-01T00:00:00.000Z"
---


![](https://static.wixstatic.com/media/ba9dcd_6cac69598fb64f929bbe77b18694def0~mv2.jpg/v1/fill/w_740,h_416,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ba9dcd_6cac69598fb64f929bbe77b18694def0~mv2.jpg)

___

Wanted to take a moment to discuss the animation/clean-up process involved with the skills found in the latest Compatibility Update! While the Special Beam Cannon from Superhero is present in Legends, the animation is very heavily stylized to fit specifically for that game, which creates a few issues when trying to port it to XV2. For instance:

1.  The animation is baked at 30fps, and when interpolated creates several spots where it lags in an unappealing way
    
2.  There are many awkward cuts in poses for when the camera switches angles, which we can't keep as XV2 skills tend to be viewed from all angles
    
3.  The skill needs to transition to and from the character's stance so it looks naturally incorporated

For perspective, this is the original animation from Legends:

<video width="800" height="480" controls>
  <source src="https://video.wixstatic.com/video/ba9dcd_340e489f71ed45c3b887d4a372f0ada9/1080p/mp4/file.mp4" type="video/mp4">
</video>


Compared to the Special Beam Cannon (Awakening) animation in Revamp:  

<video width="800" height="480" controls>
  <source src="https://video.wixstatic.com/video/ba9dcd_7ea759ca09cb4c1dab558b96592f317a/1080p/mp4/file.mp4" type="video/mp4">
</video>

___

There were also tweaks needed for the firing direction and activation speed, as the Legends skill accounts for a charge-up that is far longer than we were wanting for the skill.