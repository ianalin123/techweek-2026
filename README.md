# Tech Week 2026

Planning for the two a16z Tech Week hackathons hosted by Iana Lin and Sissi Wang.

**Private repo.** It holds contact details, sponsor conversations, and commitments.
Do not make it public — git history keeps everything ever committed. If a public
artifact is needed, copy content into a separate repo.

## The two events

Both are 24-hour hackathons with the same shape, 30.5 hours on site and 23.5 hours of
hacking. INTERFACE runs Saturday 9am check-in to Sunday 3:30pm close. **MOLTEN moved to
Friday–Saturday on 2026-08-28**, so it runs Friday 9am to Saturday 3:30pm.

| | INTERFACE | MOLTEN |
|---|---|---|
| Full title | INTERFACE: Hack the Space Between | MOLTEN: a 24-hour hackathon for spatial creation |
| City | San Francisco | Los Angeles |
| Dates | Sat–Sun Oct 10–11, 2026 | Fri–Sat Oct 16–17, 2026 |
| Theme | How humans interface with machines | Spatial creation tooling |
| Tracks | NEURAL, VOICE, TOUCH, VISION, OPEN | WORLDBUILD, NAVIGATE, CAPTURE, INHABIT, OPEN |
| Capacity | ~120 hackers + 15–20 mentors/judges/volunteers | ~120 hackers + 20 mentors/judges/volunteers |
| Submitted by | Sissi (sissiwang618@gmail.com) | Iana |
| Grant | **Up to $5K, approved 2026-08-12** | Up to $5K, approved 2026-08-20 |
| Calendar status | Submitted 2026-08-26, in review | Approved for #LATechWeek 2026-08-21 |
| Partiful | [live](https://partiful.com/e/AkfcAYRQeMprRyPklVKe) | [live](https://partiful.com/e/AgP5K9z8FR9TTWVMJIVC) |
| Venue | Not secured | Not secured |

**The two grants are separate and stack to $10K.** INTERFACE's approval went to Sissi's
personal address on 2026-08-12, which is why it looked unconfirmed for a while. Both are
reimbursement — we pay first and submit receipts.

The approved text for each event, including the full schedule, is in
`events/<city>/brief.md` and `events/<city>/runbook.md`. Those record what a16z approved
— they are history, not a spec. **The Partiful page and the one-pagers are canonical**
when they disagree, except where a one-pager asks a venue for less time than the event
actually runs. See `decisions.md`.

## Timeline

| Date | What |
|---|---|
| 2026-09-08 | **Tech Week calendar launches.** Post on LinkedIn and X that day. |
| 2026-10-02 | INTERFACE sponsorship locks (stated on the one-pager) |
| 2026-09-19 | Living Internet build day — open volunteer slots for our team (via Alexa) |
| 2026-10-05 | SF Tech Week begins |
| 2026-10-10 to 10-11 | INTERFACE |
| 2026-10-12 | LA Tech Week begins |
| 2026-10-17 to 10-18 | MOLTEN |

**Sept 8 is the operative deadline, not October.** A Partiful page has to exist and the
event has to be live before the calendar launches.

## Obligations from the a16z grant

From Fil's two approval emails. Identical terms on both events.

- **Reimbursement, not upfront cash.** Pay for the event yourself, submit receipts to
  the Tech Week finance team. Up to $5K each.
- **Partiful only**, created via `partiful.com/create?techweek=true`. Both pages are live.
  Fil confirmed on 2026-08-31 that **Partiful is the only approved registration platform
  and all RSVPs must be collected there.** Other tools are fine for organizing internally,
  but attendees may not be directed to register on Luma or anywhere else. This is a grant
  condition, so the idea of running parallel Luma sign-ups is dead.
- **The grant team does not make portfolio introductions.** Fil declined on 2026-08-31 —
  the team is small and at capacity. He encouraged cold outreach and noted that naming
  Tech Week in the email helps get replies. There is no warm a16z route.
- **Calendar launches Sept 8.** Post about the event on LinkedIn and X that day.
  Instagram, Snap, and newsletters encouraged. Handles: X `@techweek_`, LinkedIn
  "Tech Week by a16z", Instagram `@techweeka16z`.
- **Audience:** at least 80% current students or grads within 2–3 years, technical
  backgrounds.
- **Capacity:** aim for 100+ attendees; approve 2–3x capacity to absorb drop-off.
- Host FAQ and guide: `hosts.tech-week.com/faq`, `hosts.tech-week.com/guide`.
  Event tracking: `hosts.tech-week.com/my-events`.

## What we have promised

Tracked here until there is enough volume to justify a separate `commitments.md`.

Promised to Tech Week and a16z **in the approved applications** — these are the binding
ones:

- **Apple Vision Pro as the MOLTEN grand prize.** Secured, confirmed by Iana 2026-08-28.
- A MOLTEN hardware bench "in confirmation" from USC ICT, Snap, and Meta. None contacted.
- A pre-event onboarding kit for MOLTEN. Does not exist.
- Three parallel onboarding workshops at each event. No leads, no materials.
- ~15 EEG headsets and ~10 haptic kits for the INTERFACE hardware tracks. We own none.
  The plan is to buy them or find another route **after** sponsors land, so the two
  hardware tracks are downstream of sponsor outcomes.

Promised in the MOLTEN sponsor one-pager:

- Opt-in attendee resume book for sponsors — requires a consent field in the application
- Logo placement on site, Partiful, and Notion
- Post-event write-up featuring track winners
- Live product demo slot in front of attendees
- Full COI naming the venue as additional insured
- Cleanup crew Sunday afternoon, catering handled by organizers

## Repo layout

Cross-cutting registries live at the top level. Event-specific material lives under
`events/<city>/`. Rule of thumb: if it names a venue or a date, it is event-specific.

```
README.md                     this file
people.md                     everyone contacted, per-event status
outreach-targets.md           ranked ask list: who to approach, for what, and how sure we are
outreach-drafts.md            the actual email text for each ask, with contact status
events/sf/brief.md            INTERFACE as submitted and approved
events/sf/runbook.md          INTERFACE day-of schedule
events/la/brief.md            MOLTEN as submitted and approved
events/la/runbook.md          MOLTEN day-of schedule
events/sf/one-pagers/         INTERFACE combined venue and sponsor one-pager
events/la/one-pagers/         MOLTEN venue and sponsor one-pagers
decisions.md                  choices we are not relitigating, and operating advice
```

Files not yet created because they have no content: `budget.md` and per-event
`venue.md`. Add them when there is something real to put in.

## Conventions

- Commit directly to `main`. Conventional commits, `docs:` for planning content.
- Pull before editing `people.md` — the file both of us touch most.
- Draft in Google Docs while co-editing live; land it here once it settles.
- Never commit signed contracts, the grant agreement, or API keys. Link to Drive.
- **The Partiful page and the one-pagers are canonical.** `brief.md` records what a16z
  approved; it is history, not a spec. Details are allowed to drift from it — timing
  especially. The binding grant condition is the audience, not the agenda.

## Open questions

- **Should MOLTEN drop to one day?** Under discussion. It would ease the hardest part of
  the venue search, but the event is named and calendared as a 24-hour hackathon and the
  overnight is load-bearing in the pitch. Details in `events/la/brief.md`.
- **The MOLTEN venue ask is narrower than the published event** — the one-pager asks for
  a noon-to-noon window while Partiful runs 2.5 hours past that. A venue could say yes to
  the one-pager and still not cover the event. The INTERFACE one-pager has the opposite
  and correct shape: the ask is wider than the event.
- **The MOLTEN date change is not yet reflected on Partiful.** The page still shows
  Oct 17–18. **Fil approved the move to Oct 16–17 on 2026-08-31 on the single condition
  that Partiful is updated to match**, so this is now the one outstanding grant condition
  and it has to be done before the September 8 calendar launch.
- **INTERFACE was submitted 5 days after the stated deadline.** Fil's emails set
  Friday 2026-08-21 for Partiful and submission. MOLTEN made it. INTERFACE went in on
  2026-08-26 and is still in review — Tracy said 2–3 business days, up to a week around
  submission periods.
- **The venue budget does not close.** SF Tech quoted roughly $20K for 30–38 hours
  against a $5K reimbursement. Either a venue sponsor covers it, or the event moves to
  Berkeley or another free space.
- **Neither event has a venue, and that gates everything else.** Alexa's advice was to
  lock a venue before scaling sponsor outreach, and a named speaker before that.
- **No speaker is locked for either event.** Targets are researched and ranked in
  `outreach-targets.md`; none have been contacted. NEURAL is the thinnest track — Echo
  Neurotechnologies is the only serious a16z BCI company, and it is also the track with
  no hardware committed.
- **The a16z portfolio does not solve the MOLTEN hardware bench.** No portfolio company
  manufactures a spatial headset. USC ICT, Snap, and Meta still have to be asked
  directly; the portfolio only offers warm routes in.
- **The MOLTEN venue one-pager asks for the wrong hours** — Sat 12pm to Sun 12pm,
  6.5 hours short of the approved schedule. Fix before sending again.
- INTERFACE has no one-pagers.
- LA Hacks (UCLA) is running an AI hackathon that collides with the MOLTEN date.
