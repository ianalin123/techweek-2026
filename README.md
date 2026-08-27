# Tech Week 2026

Planning for the two a16z Tech Week hackathons hosted by Iana Lin and Sissi Wang.

**Private repo.** It holds contact details, sponsor conversations, and commitments.
Do not make it public — git history keeps everything ever committed. If a public
artifact is needed, copy content into a separate repo.

## The two events

| | INTERFACE | MOLTEN |
|---|---|---|
| City | San Francisco | Los Angeles |
| Dates | Oct 10–11, 2026 | Oct 17–18, 2026 (24 hours) |
| Theme | How humans interface with machines | Spatial creation tooling |
| Tracks | Neural, Voice, Touch, Vision, Open | WORLDBUILD, NAVIGATE, CAPTURE, INHABIT, OPEN |
| Capacity | 120 hackers | 100–120 hackers + ~20 mentors/judges/volunteers |
| Tech Week status | Submitted 2026-08-26, in review | Approved for #LATechWeek 2026-08-21 |
| Grant | Not yet confirmed | Up to $5K reimbursement, approved 2026-08-20 |
| Venue | Not secured | Not secured |

## Obligations from the a16z grant

These come from Fil's approval email (2026-08-20) and apply to any approved event.

- **Reimbursement, not upfront cash.** Pay for the event yourself, submit receipts to
  the Tech Week finance team. Up to $5K.
- **Partiful only.** The event page must be on Partiful. Events may not be listed on
  other platforms.
- **Calendar launches Sept 8.** Post about the event on LinkedIn and X that day.
  Instagram, Snap, and newsletters encouraged.
- **Audience:** at least 80% current students or grads within 2–3 years, technical
  backgrounds.
- **Capacity:** aim for 100+ attendees; approve 2–3x capacity to absorb drop-off.

## Promised in the MOLTEN sponsor one-pager

Tracked here until there is enough volume to justify a separate `commitments.md`.

- Apple Vision Pro as grand prize — **claimed as secured, actually unconfirmed.** See
  the open questions below.
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
events/sf/                    INTERFACE
events/la/one-pagers/         MOLTEN venue and sponsor one-pagers
```

Files not yet created because they have no content: `commitments.md`, `budget.md`,
`decisions.md`, `timeline.md`, per-event `brief.md`, `venue.md`, and `runbook.md`.
Add them when there is something real to put in.

## Conventions

- Commit directly to `main`. Conventional commits, `docs:` for planning content.
- Pull before editing `people.md` — the file both of us touch most.
- Draft in Google Docs while co-editing live; land it here once it settles.
- Never commit signed contracts, the grant agreement, or API keys. Link to Drive.

## Open questions

- **MOLTEN venue hours are inconsistent.** The venue one-pager asks for Sat 12pm →
  Sun 12pm. The schedule submitted to Tech Week runs Sat 9am check-in → Sun 3:30pm
  close. The venue ask is roughly 6.5 hours short of the actual event.
- **The Vision Pro grand prize is not secured.** The sponsor one-pager says "Vision Pro
  locked in as the grand prize." Meeting notes from 2026-08-12 say a contact of Sissi's
  was still negotiating bulk at-cost pricing with Apple, and no confirmation exists.
  Do not send the one-pager again until this resolves.
- **The venue budget does not close.** SF Tech quoted roughly $20K for 30–38 hours
  against a $5K reimbursement. Either a venue sponsor covers it, or the event moves to
  Berkeley or another free space.
- **Neither event has a venue, and that gates everything else.** Alexa's advice was to
  lock a venue before scaling sponsor outreach, and a named speaker before that.
- INTERFACE has no one-pagers yet and no separate grant confirmation.
- LA Hacks (UCLA) is running an AI hackathon that collides with the MOLTEN date.
