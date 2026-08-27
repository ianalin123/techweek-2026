# Outreach drafts

Written 2026-08-26. **Nothing here has been sent.** Every draft is text only until you
read it and decide.

Who to ask and why is in `outreach-targets.md`. This file is the actual wording, plus
what we know about how to reach each one.

## Address status

Three states, and they decide whether a draft can become a Gmail draft.

- `verified` — the address is published on the org's own site and I read it there.
  Safe to send.
- `inferred` — it matches a pattern or came from a search snippet, and I could not find
  it on a primary page. **Do not send.** Confirm first, or use the general address.
- `none` — no public address. The route is a web form, a DM, or a warm intro.

| Target | Address | Status | Where it came from |
|---|---|---|---|
| USC ICT Mixed Reality Lab | `MxRLab@ict.usc.edu` | **verified** | `mxr.ict.usc.edu/contact/`, obfuscated in the page source and decoded |
| Metastage | `team@metastage.com` | **verified** | Metastage site |
| UCLA Design Media Arts | `dmainfo@arts.ucla.edu` | **verified** | `dma.ucla.edu` faculty page |
| ArtCenter, Jenny Rodenhouse | `jenny.rodenhouse@artcenter.edu` | inferred | search snippet only, ZoomInfo masks it, ArtCenter faculty page 404s |
| USC ICT, David Nelson | `nelson@ict.usc.edu` | inferred | ICT uses `Last@ict.usc.edu` most of the time, not confirmed for him |
| USC ICT, David Cobbins | `cobbins@ict.usc.edu` | inferred | same pattern, same caveat |
| Alex McDowell, USC WbML | — | none | `worldbuilding.usc.edu` refused connection |
| Caltech CD3 (Lombeyda, Djorgovski) | — | none | Caltech directory lists office and title, no email |
| LA ACM SIGGRAPH | — | none | officers named, no addresses, sign-up form only |
| Snap AR | — | none | no public loaner route found |
| Every company target | — | none | contact forms and DevRel, see the company section |

**Use the lab address, not the personal one.** For USC ICT the verified `MxRLab@` inbox
goes to the same small team (10 people, David Nelson and David Cobbins both on it), so
there is no reason to gamble on a guessed personal address. Same logic for UCLA.

## What I could not do

You said we could use the Hunter API since we used it for Field Lab reach-outs. **There
is no Hunter key anywhere on this machine.** I checked the Field Lab pipeline, and its
CRM rows have emails literally written as "TBD (Hunter/Apollo)", so Hunter was a manual
lookup you did in the browser, never something we integrated.

The two APIs that do exist are both unavailable:

- **Exa** returned `HTTP 402 Payment Required` on all 36 calls. Out of credits.
- **MillionVerifier** is what the Field Lab verifier actually uses, and there is no key
  set, so it returns `unverified` for everything.

So this ran on plain web lookups. That works fine for universities, since they publish
addresses. It does not work for companies, which is why the whole company section below
is forms and DMs rather than addresses. **Topping up Exa (or giving me a Hunter key)
would unblock the company half of this list**, and that is the half with the sponsor
money in it.

## Corrections to the target list

Three things the research reports got wrong or stale, now checked:

- **Eddo Stern is Chair of UCLA Design Media Arts**, not just the Game Lab director. The
  ask should be pitched at department level.
- **Jenny Rodenhouse is Associate Professor and Faculty Director of the Immersion Lab**,
  and Associate Chair of BS Interaction Design. The report said Assistant Professor.
- **Joan Collins is confirmed as LA ACM SIGGRAPH Chair for 2026 to 2027.** Vice-Chair is
  Larry Rosenthal, Secretary Samara Miramontes, Treasurer Dave Curlender, Membership
  Sharon Eisenberg. No published emails for any of them.

Also confirmed: the MxR team page lists David Nelson as Director and David Cobbins as
Creative Producer, so both names in the application are still current.

---

# Send first

## 1. The grant team reply (Fil)

This one is not optional and it is overdue. Fil asked for a reply once the Partiful page
existed. Both pages are live. This is also the only route to a16z portfolio companies,
so every portco ask below is blocked behind it.

**To:** Fil (the a16z Tech Week grant thread)
**Subject:** re: Tech Week grant, both events are live

> Hi Fil,
>
> Both events are live on Partiful and submitted to the calendar.
>
> INTERFACE: Hack the Space Between, San Francisco, October 10 to 11.
> https://partiful.com/e/AkfcAYRQeMprRyPklVKe
>
> MOLTEN, a 24 hour hackathon for spatial creation, Los Angeles, October 17 to 18.
> https://partiful.com/e/AgP5K9z8FR9TTWVMJIVC
>
> One ask while I have you. We would love to have a portfolio company speak or judge at
> either one, and a few look like clean fits:
>
> For INTERFACE, ElevenLabs (they co-hosted a worldwide hackathon with a16z across seven
> cities), Sesame AI, Luma AI, and Cursor.
>
> For MOLTEN, World Labs and Luma AI, plus the spatial companies from Speedrun SR001 to
> SR004. I checked and the current SR007 cohort does not have anything spatial in it, so
> the earlier cohorts are the right place to look.
>
> Happy to take any of these as a speaker, a judge, or a sponsor, whichever is easiest on
> your side. Thanks so much!
>
> Iana

**Why it names companies:** the grant team routes better when the ask is specific. A
generic "can we have a speaker" is easy to deprioritize.

## 2. USC ICT Mixed Reality Lab

**The most overdue email on the list.** We already named USC ICT in the approved a16z
application as a hardware source and have never contacted them.

**To:** `MxRLab@ict.usc.edu` — **verified**
**cc:** sissiwang@berkeley.edu
**Subject:** vision pro loaners for a spatial hackathon in la, october 17 to 18

> Hi David and team,
>
> I'm Iana, an electrical engineering and computer science student at UC Berkeley. My
> cofounder Sissi and I are running MOLTEN, a 24 hour hackathon for spatial creation in
> Los Angeles on October 17 to 18. It is part of LA Tech Week and funded by an a16z
> grant. We are expecting 100 to 120 students building across five tracks: world
> building, navigation, capture, inhabiting, and open.
>
> We named the MxR Lab in our application as the place we hoped to work with, so I wanted
> to actually write to you rather than leave that as a hope.
>
> Three things we would love, and any one of them alone would help:
>
> 1. Vision Pro or other headset loaners for the weekend. Hardware is the real
>    constraint on what students can build in 24 hours.
> 2. You or David Cobbins as a judge on the Sunday.
> 3. A mentor or two on Saturday afternoon while teams are still choosing scope.
>
> I'm genuinely keen to hear about the lab's work either way. The through line from
> Project Holodeck to what MxR does now is a big part of why we are running this in LA
> and not somewhere else.
>
> Would you be up for a quick call in the next week or two?
>
> Thanks so much in advance,
> Iana Lin

**Note:** ask for hardware first. It is the thing only they can give us, and the judge
and mentor asks are cheap add-ons that make a yes easier to partially grant.

## 3. Metastage

**To:** `team@metastage.com` — **verified**
**cc:** sissiwang@berkeley.edu
**Subject:** volumetric assets for a spatial hackathon in la

> Hi Christina,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and backed by an a16z grant. Around 100 to 120 students, five tracks, one of which
> is capture.
>
> The ask is small and I think it costs you almost nothing. Would you be willing to let
> us hand teams a few pre-captured volumetric performances to build on? In 24 hours
> nobody can capture and build, so having real holograms on hand is the difference
> between the capture track being theoretical and being something people actually ship.
> Every demo made with them would be built on Metastage capture and shown to a room of
> students and judges.
>
> We would also love you as a judge on the Sunday if the date works.
>
> Thanks so much in advance,
> Iana Lin

**Why this framing:** giving us existing assets is nearly free for them, and the
distribution argument is real. Lead with the cheap ask.

## 4. UCLA Design Media Arts

**To:** `dmainfo@arts.ucla.edu` — **verified**, ask them to forward to Eddo Stern
**cc:** sissiwang@berkeley.edu
**Subject:** dma students at a spatial hackathon in la, october 17 to 18

> Hi,
>
> Could you please pass this to Eddo Stern, or point me to the right person?
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18. It is part of LA
> Tech Week and funded by an a16z grant, and we are expecting 100 to 120 people.
>
> We are trying hard not to make this an all engineers room. The pitch to DMA students is
> straightforward: come with an idea and a visual sensibility and we will pair you with
> people who can build it in a day. The tracks are world building, navigation, capture,
> inhabiting, and open, so a lot of it is closer to DMA work than to a normal hackathon.
>
> Two asks:
>
> 1. Would you be willing to share the event with DMA students? Here is the page:
>    https://partiful.com/e/AgP5K9z8FR9TTWVMJIVC
> 2. Would any DMA faculty be interested in judging on the Sunday? Having someone from
>    the art and design side on the panel changes what teams decide to build.
>
> Thanks so much in advance,
> Iana Lin

---

# Blocked on an address

Drafts are ready. Each needs a route before it can go out.

## 5. ArtCenter Immersion Lab, Jenny Rodenhouse

**Route:** `jenny.rodenhouse@artcenter.edu` is **inferred, do not send yet.** Her site is
`jennyrodenhouse.com` and she is active publicly, so LinkedIn or her own site contact
form is the safer first touch. ArtCenter's main line can also route you.

**Subject:** immersion lab + a spatial hackathon in la, october 17 to 18

> Hi Jenny,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and funded by an a16z grant. ArtCenter is one of the schools we most want in the
> room.
>
> I read about how you have folded VR and AR into the Interaction Design curriculum
> rather than treating it as a separate elective, and that is close to what we are trying
> to do in a weekend. Our five tracks are world building, navigation, capture,
> inhabiting, and open.
>
> Two asks. Would you be open to the Immersion Lab as a community partner, meaning we
> share the event with your students and credit the lab? And if the lab has headsets or
> mocap that could travel for a weekend, that would change what teams can attempt.
>
> I know Caltech's Center for Data Driven Discovery has worked with you before, and we
> are reaching out to them too, so there may be a version of this where both labs are
> involved.
>
> Would you be up for a quick call?
>
> Thanks so much in advance,
> Iana Lin

## 6. Caltech CD3

**Route:** no published emails. Santiago Lombeyda is Senior Computational Scientist at
CDDD, office 209 Powell-Booth. George Djorgovski directs it. Caltech's directory has
office and phone but no address. Try the CD3 site contact form, or approach them jointly
with Jenny Rodenhouse since they already collaborate.

**Subject:** caltech students at a spatial hackathon in la

> Hi Santiago,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and funded by an a16z grant.
>
> I'm keen to talk because the Data to Discovery work is the clearest example I know of
> the thing we are trying to get students to do in 24 hours, which is take data that has
> no natural shape and give it one you can walk around in. Our world building and
> navigate tracks are basically that problem.
>
> Two asks. Would you share the event with Caltech students? And would you or George be
> interested in judging on the Sunday?
>
> Thanks so much in advance,
> Iana Lin

## 7. USC World Building Media Lab, Alex McDowell

**Route:** `worldbuilding.usc.edu` refused connection when I tried it. Try
`worldbuilding.institute`, or route through USC ICT once that thread is open, since both
are USC and MxR will know him.

**Subject:** our worldbuild track, and whether you would speak

> Hi Alex,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and funded by an a16z grant. Around 100 to 120 students.
>
> One of our five tracks is called WORLDBUILD, which is a fairly direct borrowing from
> your work, so it felt wrong not to write to you.
>
> We would love you to open the event on the Saturday morning. Most of the room will be
> engineers who have never been asked to think about a world before they think about a
> demo, and 20 minutes from you at the start would change what gets built. Judging on the
> Sunday would be just as welcome if that is easier.
>
> Thanks so much in advance,
> Iana Lin

## 8. LA ACM SIGGRAPH

**Route:** officers are named but no emails are published. There is an announcements
sign-up form on `lasiggraph.org/contact-us`. Larry Rosenthal (Vice-Chair) is publicly
active and may be the easier first contact.

**Subject:** sharing a spatial hackathon with the la chapter

> Hi Joan,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and funded by an a16z grant.
>
> The chapter's list is close to exactly the audience we want, both the students and the
> working CG people. Would the chapter be open to sharing it as a community partner? We
> would credit LA ACM SIGGRAPH on the event page and in the room.
>
> We would also welcome chapter members as mentors or judges if anyone is interested.
>
> Here is the page: https://partiful.com/e/AgP5K9z8FR9TTWVMJIVC
>
> Thanks so much in advance,
> Iana Lin

## 9. Snap AR

**Route:** unresolved. There is no public Spectacles loaner request for organizers that I
could find. What exists is the Spectacles Community Challenge and a $99/month developer
program. Snap did provide loaners to MIT Reality Hack and to Reality Hack at AWE, so the
route exists privately. Best angles: the developer relations team via
`developers.snap.com`, or the USC Iovine and Young students who won ImmerseGT on
Spectacles, since Snap already knows that group.

**Subject:** spectacles loaners for a spatial hackathon in la, october 17 to 18

> Hi,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running MOLTEN,
> a 24 hour hackathon for spatial creation in LA on October 17 to 18, part of LA Tech
> Week and funded by an a16z grant. We expect 100 to 120 students.
>
> I know Snap has loaned Spectacles to student hackathons before, including Reality Hack,
> so I wanted to ask whether that is possible for ours. Hardware is the single biggest
> limit on what teams can attempt in 24 hours, and Spectacles would open up our navigate
> and inhabit tracks in a way nothing else we can get would.
>
> If loaners are not possible, we would still love someone from the developer relations
> team to run a Lens Studio session on the Saturday, and to judge on the Sunday.
>
> Thanks so much in advance,
> Iana Lin

---

# INTERFACE, San Francisco, October 10 to 11

Every a16z portfolio company here should go through the grant team first (draft 1), not
cold. These are the direct versions to use if the grant route stalls or if they are not
portfolio companies.

## 10. ElevenLabs (VOICE)

Highest probability yes on the whole list. a16z co-led their Series C and co-hosted their
worldwide hackathon with a16z across seven cities, so the pattern already exists.

**Route:** through the grant team first. Direct fallback is their developer relations
team.

**Subject:** api credits for an interfaces hackathon in sf, october 10 to 11

> Hi,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running
> INTERFACE: Hack the Space Between, a 24 hour hackathon in San Francisco on October 10
> to 11, part of SF Tech Week and funded by an a16z grant. Around 80 to 120 hackers
> across five tracks, one of which is voice.
>
> I saw you ran a worldwide hackathon with a16z across seven cities, so this is probably
> a familiar shape. We would love API credits for the weekend, and a sponsorship if that
> is on the table. Someone from your team as a judge would be even better, since the
> voice track will be the busiest one.
>
> Thanks so much in advance,
> Iana Lin

## 11. Cartesia (VOICE)

Not a16z (Index and Kleiner led), so this is a direct ask. They ran their own SF voice
agent hackathon with $20K in prizes, so they already spend on this.

**Subject:** voice track sponsorship for an sf hackathon, october 10 to 11

> Hi,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running
> INTERFACE: Hack the Space Between, a 24 hour hackathon in San Francisco on October 10
> to 11, part of SF Tech Week. Around 80 to 120 hackers, and voice is one of our five
> tracks.
>
> I saw you ran your own voice agent hackathon in SF with $20K in prizes, so you already
> know this audience. We would love Cartesia to sponsor the voice track, and to have
> someone speak about what actually makes realtime voice feel fast. That is the exact
> thing our hackers will spend the weekend fighting, so it would land.
>
> Thanks so much in advance,
> Iana Lin

## 12. Sesame AI (speaker, VOICE and VISION)

The best pure keynote ask for the interface theme. a16z led the Series A, so route
through the grant team.

**Subject:** speaking at an interfaces hackathon in sf, october 10 to 11

> Hi,
>
> I'm Iana, an EECS student at UC Berkeley. My cofounder Sissi and I are running
> INTERFACE: Hack the Space Between, a 24 hour hackathon in San Francisco on October 10
> to 11, part of SF Tech Week and funded by an a16z grant.
>
> The whole event is about how humans interface with machines, and audio first glasses
> are the most interesting live answer to that question right now. We would love someone
> from Sesame to open the Saturday. Our tracks are neural, voice, touch, vision, and
> open, and Sesame sits across two of them.
>
> Thanks so much in advance,
> Iana Lin

## 13. Remaining INTERFACE targets

Same shape, so I have not written each one out. Swap the specific sentence:

| Target | Ask | The one specific sentence |
|---|---|---|
| **Cursor / Anysphere** | judge | they recruit hard at Berkeley and Stanford, and the room is exactly that population |
| **Luma AI** | sponsor + speaker | they host and sponsor hackathons at AGI House, which is Alexa's venue, so try the warm route through her first |
| **Vercel** | sponsor + judge | Guillermo Rauch judges hackathons, and they sponsor constantly |
| **Roboflow** | sponsor + mentors | they send people to mentor in person at collegiate hackathons |
| **Hume AI** | sponsor + credits | they have sponsored Cal Hacks, so there is a Berkeley relationship to trace |
| **Deepgram** | credits | self serve free tier, so this is a low friction yes |
| **XDOF** | speaker | **verify the a16z claim first.** Founded by Berkeley PhD researchers, which is the real hook |
| **Chloe Duckworth, Valence Vibrations** | speaker | she started the company out of a hackathon as a USC student, and emotion AI into haptics bridges voice and touch |

**TOUCH is still the weak track.** Only XDOF and Ultraleap surfaced. If XDOF does not
check out, Ultraleap is the hardware fallback rather than a speaker.

---

# MOLTEN companies, October 17 to 18

No addresses for any of these, which is the Exa problem. All routes are contact forms,
DevRel, or DMs.

| Target | Ask | The one specific sentence |
|---|---|---|
| **World Labs** | API partner + speaker | the World API generates explorable 3D worlds from text or images with a $5 credit minimum, which is the most powerful thing we could put in front of the worldbuild track. a16z backed, so go through the grant team |
| **Luma AI** | speaker + API | one relationship covers both events, so ask once and cover SF and LA |
| **Refactor Games** | speaker | Nathan Burba ran Project Holodeck at the USC MxR Lab and was Survios' founding CEO, so he is on theme and also a warm path into MxR |
| **AvatarOS** | speaker | Isaac Bratzel built Lil Miquela, which the media arts half of the room already knows |
| **Uthana** | API + sponsor | LA, foundation models for human motion, and they are hiring, which usually means they want the room |
| **Polycam** | sponsor | mobile capture and splatting with strong iOS and Vision Pro support, and confirmed not a16z, so ask directly |
| **Meshy** | sponsor | text to 3D with a free tier and a recent large raise, so there is DevRel budget |
| **Inworld AI** | API partner | low latency realtime API for AI characters, a direct fit for the inhabit track |
| **Arcturus** | sponsor | volumetric video editing, reportedly a16z and Epic backed, so verify before routing |

---

# What I would do first

1. **Send the Fil reply.** It is overdue on its own terms and it unblocks every a16z
   portfolio ask below it.
2. **Send the USC ICT email.** Verified address, we already named them in the
   application, and they are the only real answer to the hardware bench.
3. **Send Metastage and UCLA.** Both verified, both cheap asks.
4. **Top up Exa or find a Hunter key.** Nine company targets are sitting here with
   finished drafts and no address, and that is where the sponsor money is.
5. **Verify XDOF** before anyone emails them, and do not email SLNG.ai at all until
   someone can corroborate it exists as described.
