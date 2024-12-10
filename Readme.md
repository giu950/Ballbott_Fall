# A Reinforcement Learning method to minimize the damage on a falling Ballbot

As robots become ever more popular in various fields and require flexibility in unexpected situations,
reducing damage to their body becomes ever more relevant. This paper presents our preliminary results on
fall damage reduction on a commercial Ballbot, Miroki. While various approaches have been proposed for
damage reduction for humanoid and animal-like robots, no previous works have addressed this challenge
on Ballbots. To this aim, we implemented a deep RL framework and tested it on the Isaac Gym simulator.
Compared to the free fall case, the learned control strategy manages to reduce the damage on the Ballbot
by 52%, by controlling the arms of the robot during the fall.
***
In this repository, we provide additional visual material, including videos and images, to compare how Miroki falls with the trained policy versus without any policy.

[Miroki_best_policy.webm](https://github.com/giu950/Ballbott_Fall/assets/124883359/1f18bafb-56ec-4bb9-bafc-605bb5f0de5e)
[Miroki_free.webm](https://github.com/giu950/Ballbott_Fall/assets/124883359/12d64b6e-8b82-4896-87c5-9ee01eac50f4)
![contact_norm_nl](https://github.com/giu950/Ballbott_Fall/assets/124883359/ee3187f3-47b2-47b5-9444-5e81dd3db4ce)
![heatmap_body](https://github.com/giu950/Ballbott_Fall/assets/124883359/7345b691-e373-43d3-9c03-ac8378fe1908)
![heatmap_joints](https://github.com/giu950/Ballbott_Fall/assets/124883359/c09fb8ad-43d6-43d8-b1b0-a01b922cc233)
