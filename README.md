# Defconbots 2014 - Tower Defense - Rules

These are the official rules for the defconbots 2014, tower defense, competition. These rules are in development and subject to change but will be finalized by May-2014.

If you have questions or comments about the rules create an issue in this repository.

## Spirit of the Contest

 * Build an autonomous robot with an aiming mechanism and a laser
 * Write software for the robot to accurately aim and shoot the laser at moving and illuminated targets

Robots that go against the spirit of the contest will be disqualified. Examples of this would be a robot that randomly sweeps the laser across the Arena or is secretly remote controlled.

## Robot

### Physical

 * Must fit within 1 x 1 x 1 meter cube
 * Must be easy to move and stage for competition quickly (< 5 minutes)

### Software

 * Autonomous (no remote control)
 * Laser should be pulsed on for 500ms with a 1500ms delay between shots.

### Shooting Device

 * One(1) Red laser, Specifically: https://www.sparkfun.com/products/8654 or https://www.sparkfun.com/products/594
You can get the laser somewhere else but it must be the same model
 * If a mirror is used to direct your laser it must not distort your laser beam (cannot be concave or convex)
 * The robot should only emit one laser beam (beam-splitters may be used internally but the robot may not emit multiple beams)

# Competition Mechanics

## Arena
 
 * 5 x 10 meters
 * Ground will be flat-black color (blackout cloth)
 * TBD alignment targets
   * Location (TBD)

## Targets

 * 5 targets
 * 0.1 - 0.5 meter off the ground (TBD)
 * 0.1 - 1 meters apart (TBD)
 * Fixed speed of (TBD - approximately 0.15 m/s)
 * Spherical shape
 * 40mm diameter (table-tennis ball)
 * White surface color
 * Illuminated blue (470nm) when active

## Waves

 * Each wave starts at a specific point (TBD) on the track
 * Initially all targets are illuminated and "alive"
 * A "hit" on a target is with laser for >300ms (Specific laser above!) while illuminated
 * Once a target is hit illumination will stop for one(1) second
 * Wave #1 will require one(1) hit on each target
 * Wave #n(where n is the wave number) will require n hits on each target
 * Once n hits have been completed the target illumination will stop until the end of the wave
 * At the end of the wave there may be up to one(1) minute of delay before the next wave starts
 * If there is a problem with the track or targets during a wave the event coordinators reserve the right to halt the wave and restart it (we will try our best to never let this happen!)

## How to win

 * Your score is:
   * Number of waves you complete (higher is better)
   * Number of targets remaining as the first tiebreaker (lower is better)
   * Total hitpoints remaining as the second tiebreaker (lower is better)
 * Qualification
   * Contestants are able to qualify on a first-come, first-serve basis
   * Contestants have 15 minutes to set up their robot. When the contestant is ready, the first wave will start
   * If a wave is completed, then the next wave will start. Otherwise the contestant has the ability to tweak their robot and retry the wave
   * After 3 failed waves, the contestants turn is over, and their score will be recorded on a leaderboard
   * If available, contestants are able to try to qualify again at a later time, but people who haven't qualified have first priority
 * Finals
   * After the qualification round is completed, the finals round will start
   * The top 4 contestants in the qualification round proceed to the finals
   * In order from fourth place to first place, each contestant will take a turn in order
   * Contestants have 15 minutes to set up their robot. When the contestant is ready, the first wave will start
   * If a wave is completed, then the next wave will start
   * After a failed wave, their turn is over, and their score will be recorded
 * The final ranking will be determined by the finals times for the people that were in first through fourth, followed by the runners up in order of their qualification score.
