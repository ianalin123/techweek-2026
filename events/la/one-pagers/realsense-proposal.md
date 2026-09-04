# MOLTEN — proposal for RealSense

Drafted 2026-09-02 after the RealSense call (Chris Matthieu, Mike Nielsen, Penny Malsch).
Companion to the INTERFACE Vision Track proposal. Research basis: call transcript +
`research/` RealSense notes.

**Internal notes, do not send:**
- Chris proposed the NorCal/SoCal split himself on the call — "we can totally split it,
  it gives us a chance to do different cameras and different applications." This document
  is his idea handed back to him. Lead with that.
- He asked twice whether "volumetric" meant dimensional weighing of boxes. Answer it in
  the first paragraph or he will keep re-anchoring on logistics.
- Their real blocker is inventory, not interest — "we sell so many cameras that we're out
  right now." Never make LA an all-or-nothing ask.
- Chris is Bay-based and volunteered to attend SF in person. LA is a travel ask; do not
  assume it. Ask, offer remote-support fallback.
- Cash was never discussed on the call, and Chris probed toward hardware-instead-of-cash.
  Keep the LA cash ask soft or absent until SF closes.
- Art of Fiction: Chris named them unprompted as an LA-based RealSense customer doing 3D
  reconstruction of virtual spaces. Live judge/speaker lead — ask him for the intro.

---

## The one-line bridge

INTERFACE is perception for machines that move. MOLTEN is perception for spaces people
inhabit. Same sensor stack, pointed at a room instead of a warehouse.

## What "volumetric" means here

Not dimensional weighing. Not palletized boxes. MOLTEN is 3D reconstruction and spatial
asset generation — scanning a real space or a real body and turning it into something
someone can move through, edit, or inhabit. The closest reference point in RealSense's own
customer base is Art of Fiction: reconstruct a space, then teleport into it.

## The event

- Official a16z Tech Week event, grant-funded, on the #LATechWeek calendar
- Friday–Saturday, Oct 16–17, 2026 · 24-hour build · 120 hackers
- Venue: xTribe, Inglewood
- 80%+ current students or grads within 2–3 years (a grant condition)
- USC and UCLA core, Berkeley pipeline, LA XR studio alumni
- More creator-oriented than SF: designers and technical artists alongside engineers
- Grand prize: Apple Vision Pro. Demo showcase Saturday with an invited audience
- Six days after INTERFACE

## Why RealSense is infrastructure here, not just a sponsor

Every MOLTEN submission must satisfy two hard rules: ship a spatial output, and use **at
least two body-input modalities**.

A single depth camera satisfies the second rule on its own — skeleton, hand and finger
articulation, and head pose from one device. No other sponsor at this event can say that.
For a meaningful share of the room, RealSense is not the track prize; it is how the
project qualifies at all.

## Tracks

Five tracks: WORLDBUILD, NAVIGATE, CAPTURE, INHABIT, OPEN.

**CAPTURE is the RealSense track** — scanning, reconstruction, spatial memory. It is the
product description restated as a hackathon category.

How the others pull on depth:

- **WORLDBUILD** — scan a real space, then generate on top of it. Depth gives generative
  3D tools a ground-truth substrate instead of a hallucinated one.
- **NAVIGATE** — occlusion-correct movement through spatial content; real geometry as the
  constraint on a virtual camera.
- **INHABIT** — skeleton and hand tracking driving avatars and shared presence. The facial
  authentication camera is the sharpest fit in the event: the scene knows who walked in.
- **OPEN** — volumetric capture of bodies, garments, and objects. Chris flagged shoes and
  clothing; there is a real LA crowd for exactly that.

## The ask

**Named CAPTURE track sponsor**, and a camera allocation distinct from SF's.

Where SF wants short-range navigation and manipulation, LA wants reconstruction quality
and range. The D455 class and the alternating dual-RGB build are the interesting units
here, plus at least one facial authentication camera for INHABIT.

Two shapes, and they combine:

1. **Per-team cameras** — 8 to 12 units distributed to CAPTURE teams and any team that
   needs a second body-input modality.
2. **A shared volumetric capture rig** — 3 to 4 synchronized cameras set up as a station
   any team can book. This is how volumetric capture actually works in production, it is
   the most demo-able thing on the floor, and it turns a hardware donation into a
   landmark rather than a giveaway. If only one shape is possible, choose this one.

**The logistics argument:** INTERFACE is Oct 10–11, MOLTEN is Oct 16–17. One shipment
covers both weekends. SF cameras can be redeployed to LA with six days in between. Two
events, two audiences, one hardware commitment.

## What RealSense gets

- Named RealSense CAPTURE track
- Logo across event materials, Partiful, and social promotion
- Stage time before the build clock starts — the camera lineup and Perception Studio
- On-site table for the 24 hours
- Opt-in attendee resume book
- Post-event write-up featuring CAPTURE winners and what they built
- A written feedback report from every team that used a RealSense camera: what worked,
  what broke, what they tried to build and couldn't
- Beta distribution for the university certification program to a second cohort

## On attendance

Chris is Bay Area based, so LA is a genuine travel ask rather than a 45-minute drive.
Ask whether anyone from the team is LA-adjacent that weekend. If not, the fallback is
a shipped kit plus a Discord channel with a RealSense engineer on call during build
hours — worth naming explicitly so distance doesn't become the reason for a no.

## Timing

Same clock as SF. Go/no-go plus logo files by **Friday Sept 4**, Monday Sept 7 at the
latest, for the Tech Week calendar launch Sept 8. Camera models and counts can follow
the week after — their inventory question should not gate the branding.

Chris's own words on LA: "it's only the following week, so it's not like we got a whole
lot of time."

## Status

- 2026-09-02: call held. Stance was "we're in, we just don't know how we're in."
- SF proposal drafted for Sissi to send. LA details promised on the call and still owed.
- Open: camera models and counts, LA attendance, whether any cash is in scope,
  Art of Fiction intro.
