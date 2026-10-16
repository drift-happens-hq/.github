# Drift Happens

**How robots actually work, and why they don't.**

This is the code behind the `youtube link`. Each season builds a working robot from zero, one piece per episode, and every episode includes the moment it breaks and how to fix it.

Everything you see on screen lives here, including the code that draws the animations. If it's in a video, you can run it.

## Who this is for

- Junior robotics engineers who want to see how the pieces of a real autonomy stack fit together.
- Software engineers curious about robotics who want something they can actually run.
- Anyone who has watched a robot do something baffling and wondered why.

You need some Python. You don't need a robotics background; terms are defined as they come up and the math is walked through one step at a time.

## Season 1: Build a Field Robot From Zero

A small autonomous robot that drives down a crop field, built in plain Python with a 2D simulator. No ROS, no special hardware, nothing to install beyond a few common packages.

| Episode | What we build | What breaks | Status |
| --- | --- | --- | --- |
| 1 | The whole robot in one picture | A robot with only a planner | Coming soon |
| 2 | A simulator | A timestep too large teleports the robot | Coming soon |
| 3 | Fake sensors with real noise | Perfect sensors hide every bug | Coming soon |
| 4 | Odometry | Wheel slip on mud | Coming soon |
| 5 | The Kalman filter, part 1 | An overconfident filter ignores good data | Coming soon |
| 6 | The Kalman filter, part 2 | A GPS jump drags the robot into the next row | Coming soon |
| 7 | Following a path | Lookahead too short wobbles, too long cuts corners | Coming soon |
| 8 | Planning around obstacles | A valid path the robot can't physically drive | Coming soon |
| 9 | Deciding what to do | Stuck between two states forever | Coming soon |
| 10 | The full stack, end to end | Every bug from the season, revisited | Coming soon |

Season 2 takes the same robot into ROS 2.

## How the code is organised

- One repository per season, starting with [`season-1-field-robot`](https://github.com/drift-happens/season-1-field-robot).
- One folder per episode, each with its own README linking to the video.
- Every episode is a git tag (`ep-01`, `ep-02`, and so on), so you can check out exactly the code shown in that video:

```bash
git clone https://github.com/drift-happens/season-1-field-robot.git
cd season-1-field-robot
git checkout ep-04
```

## Follow along

- **YouTube:** `youtube link` for the full episodes.
- **LinkedIn:** `LinkedIn profile link` posts each episode's story and the bug behind it. Look for #DriftHappens.
- **Issues and discussions:** found a bug, or have a question about an episode? Open an issue on that season's repo. Bugs are on-brand here.

## License

Code is released under the MIT License. Video content belongs to the Drift Happens channel.
