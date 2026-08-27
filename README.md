# Tech Week 2026

Planning for the two a16z Tech Week hackathons hosted by Iana Lin and Sissi Wang.

**Private repo.** It holds contact details, sponsor conversations, and commitments.
Do not make it public — git history keeps everything ever committed. If a public
artifact is needed, copy content into a separate repo.

## The two events

Both are 24-hour hackathons with the same shape: Saturday 9am check-in through Sunday
3:30pm close, 30.5 hours on site, 23.5 hours of hacking.

| | INTERFACE | MOLTEN |
|---|---|---|
| Full title | INTERFACE: Hack the Space Between | MOLTEN: a 24-hour hackathon for spatial creation |
| City | San Francisco | Los Angeles |
| Dates | Oct 10–11, 2026 | Oct 17–18, 2026 |
| Theme | How humans interface with machines | Spatial creation tooling |
| Tracks | NEURAL, VOICE, TOUCH, VISION, OPEN | WORLDBUILD, NAVIGATE, CAPTURE, INHABIT, OPEN |
| Capacity | 80–120 hackers + 15–20 mentors/judges/volunteers | 100–120 hackers + 20 mentors/judges/volunteers |
| Submitted by | Sissi (sissiwang618@gmail.com) | Iana |
| Grant | **Up to $5K, approved 2026-08-12** | Up to $5K, approved 2026-08-20 |
| Calendar status | Submitted 2026-08-26, in review | Approved for #LATechWeek 2026-08-21 |
| Venue | Not secured | Not secured |

**The two grants are separate and stack to $10K.** INTERFACE's approval went to Sissi's
personal address on 2026-08-12, which is why it looked unconfirmed for a while. Both are
reimbursement — we pay first and submit receipts.

The approved text for each event, including the full schedule, is in
`events/<city>/brief.md` and `events/<city>/runbook.md`. Those are the source of truth.
The one-pagers are downstream and currently disagree with them in places.

## Timeline

| Date | What |
|---|---|
| 2026-09-08 | **Tech Week calendar launches.** Post on LinkedIn and X that day. |
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
- **Partiful only**, created via `partiful.com/create?techweek=true`. Events may not be
  listed on other platforms. **Reply to Fil once the Partiful page is created and the
  event submitted** — he asked for this on both events and is still waiting.
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

- **Apple Vision Pro as the MOLTEN grand prize, stated as "secured."** It is not. See
  open questions.
- A MOLTEN hardware bench "in confirmation" from USC ICT, Snap, and Meta. None contacted.
- A pre-event onboarding kit for MOLTEN. Does not exist.
- Three parallel onboarding workshops at each event. No leads, no materials.
- ~15 EEG headsets and ~10 haptic kits for the INTERFACE hardware tracks. We own none.

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
events/sf/brief.md            INTERFACE as submitted and approved
events/sf/runbook.md          INTERFACE day-of schedule
events/la/brief.md            MOLTEN as submitted and approved
events/la/runbook.md          MOLTEN day-of schedule
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
- `brief.md` holds approved text. If a one-pager disagrees with it, the one-pager is
  wrong.

## Open questions

- **The Vision Pro grand prize is not secured.** Both the sponsor one-pager and the
  approved MOLTEN application call it secured. Meeting notes from 2026-08-12 say a
  contact of Sissi's was still negotiating at-cost bulk pricing with Apple, and no
  confirmation exists. This one was claimed to a16z, not just to sponsors.
- **Does a Partiful page exist for either event?** Fil asked both of us to reply once
  it was up. Nothing in the mail suggests we did. Sept 8 is the hard date.
- **INTERFACE was submitted 5 days after the stated deadline.** Fil's emails set
  Friday 2026-08-21 for Partiful and submission. MOLTEN made it. INTERFACE went in on
  2026-08-26 and is still in review — Tracy said 2–3 business days, up to a week around
  submission periods.
- **The venue budget does not close.** SF Tech quoted roughly $20K for 30–38 hours
  against a $5K reimbursement. Either a venue sponsor covers it, or the event moves to
  Berkeley or another free space.
- **Neither event has a venue, and that gates everything else.** Alexa's advice was to
  lock a venue before scaling sponsor outreach, and a named speaker before that.
- **The MOLTEN venue one-pager asks for the wrong hours** — Sat 12pm to Sun 12pm,
  6.5 hours short of the approved schedule. Fix before sending again.
- INTERFACE has no one-pagers.
- LA Hacks (UCLA) is running an AI hackathon that collides with the MOLTEN date.
