# Outreach drafts

Written 2026-08-26, addresses resolved 2026-08-27. **Nothing here has been sent.**

Nine emails are sitting in your Gmail drafts, ready to review and send. Sissi is cc'd on
all of them.

| Gmail draft | To | Also cc'd |
|---|---|---|
| Re: Your Tech Week 2026 event grant is approved! | `fil@tech-week.com` | `mchin@a16z.com` — threaded onto the real approval email |
| vision pro loaners for a spatial hackathon in la | `dnelson@ict.usc.edu`, `cobbins@ict.usc.edu` | `MxRLab@ict.usc.edu` |
| volumetric assets for a spatial hackathon in la | `team@metastage.com` | — |
| dma students at a spatial hackathon in la | `eddostern@arts.ucla.edu` | `dmainfo@arts.ucla.edu` |
| our worldbuild track, and whether you would speak | `alex@worldbuilding.institute` | — |
| immersion lab + a spatial hackathon in la | `jenny.rodenhouse@artcenter.edu` | — |
| caltech students at a spatial hackathon in la | `slombeyda@caltech.edu` | `gdjorgovski@caltech.edu` |
| speaking at a spatial hackathon in la | `nathan@refactorgames.com` | — |
| speaking at an interfaces hackathon in sf | `chloe@valencevibrations.com` | — |
| sponsoring two tech week hackathons | `wayne@convex.dev` | — |
| the shack15 slot again, without you having to run it | `nina.lopatina@mongodb.com` | `chuck.freedman@mongodb.com` |

Eight are MOLTEN or the grant team. Chloe Duckworth is the only INTERFACE-only draft,
because every other INTERFACE target is an a16z portfolio company and should go through
Fil first rather than cold. Convex and MongoDB are pitched on both events at once.

## Infrastructure sponsors, a different pitch

Convex and MongoDB are horizontal developer tools rather than thematic partners, which is
fine, because horizontal tools are who actually pay for hackathons. The pitch changes
accordingly. For a thematic partner like Metastage we argue relevance. For these two we
argue **reach**: roughly 200 student builders across two weekends, from Berkeley,
Stanford, USC, UCLA, ArtCenter, and Caltech, every team shipping a demo.

| Target | Best contact | Check | Why that person |
|---|---|---|---|
| **Convex** | `wayne@convex.dev` — Wayne Sutton, Community Manager | **valid** 100 | community owns hackathon sponsorship, and Convex runs its own hackathon series so the motion already exists |
| Convex, escalation | `jamie@convex.dev` (co-founder), `liz@convex.dev` (Marketing) | valid | if Wayne does not answer |
| **MongoDB** | `nina.lopatina@mongodb.com` — **Nina Lopatina, Staff AI Developer Advocate**, SF Bay Area | **valid** 98 | she built the **Build Lab at .local SF**, an agentic build environment for hackathon-style builders. Closest person at the company to what we are running |
| MongoDB, cc | `chuck.freedman@mongodb.com` — **Senior Director of Developer Relations** | **valid** 95 | the person who can approve spend. Hunter gives this title, not the "Head of Builder Relations" a search result claimed |
| MongoDB, alternates | `steffan.mejia@mongodb.com`, `shelby.carpenter@mongodb.com` — both Director of Developer Relations | **valid** 100 | if Nina and Chuck go quiet |
| MongoDB, event ops | `emily.mcbride@mongodb.com` — Manager, Strategic Event Operations | **valid** 91 | whoever actually books the event, once there is a yes |
| MongoDB, regional | `daniel.coupal@mongodb.com` — Developer Advocate, Santa Clara | **valid** 97 | US West regional contact |
| MongoDB, MOLTEN angle | `andrew.fenby@mongodb.com` — Head of Media and Gaming | **valid** 100 | the spatial and gaming fit if DevRel stalls |
| MongoDB, student angle | `raghu.viswanathan@mongodb.com` — VP of Education, `aaron.becker@mongodb.com` — Educational Technologist | **valid** 100 | fallback only, and it is the slower door |
| MongoDB, **skip** | `nicolas.raboy@mongodb.com` — Nic Raboy, leads DevRel **Content** | valid 98 | still at MongoDB, but content and Developer Center strategy is the wrong function for sponsorship |

**Convex has a specific technical argument.** Much of what people try to build at MOLTEN
is shared and spatial, meaning two or more people in one world at once. Realtime sync is
what kills those projects around hour 18, and that is precisely what Convex removes. That
is in the draft.

**MongoDB is not a generic sponsor and I had this wrong at first.** They sponsor a lot of
hackathons, heavily in SF. Confirmed: an **Agentic Memory and Context Engineering
hackathon run for SF Tech Week**, a Build Fest mini-hackathon at MongoDB.local in SF on
Aug 13, a Jan 10 2026 hackathon at Shack15, and a **residency program whose flagship
partner is AGI House**. AGI House is Alexa's venue, so this is a warm route, not a cold
one. The single highest-value move here is asking Alexa for the intro before the email
goes out.

### What MongoDB is actually trying to do right now

This is the part that makes the ask fundable. Researched 2026-08-27.

**Their whole company is pointed at being the memory layer for AI agents.** They bought
Voyage AI (embedding and reranking models) for **$220M in Feb 2025**, and it is not a side
bet, it is the center of the messaging. Their own line is that Atlas is "the memory and
context layer that agents are built on." The argument is that agent memory is nested,
mutable JSON that you need to store, retrieve, update, and delete, and a document model
with native vector search does that in one system instead of stitching Pinecone plus Redis
plus Postgres together.

**Automated Embeddings went GA on August 13, 2026, two weeks ago.** Atlas now generates and
indexes embeddings on write. No embedding pipeline, no sync job. This is the single
freshest thing they have and they need proof it gets adopted.

**The pressure they are under.** CJ Desai replaced Dev Ittycheria as CEO on Nov 10, 2025,
so do not name-drop Ittycheria. On the Q4 call Desai said plainly that AI contributions to
revenue are still "nascent" and that enterprise agentic workloads are experimental rather
than revenue-generating. Analysts pushed on it. Their AI-native and startup go-to-market
was described as "a work in progress." That gap is the one a student hackathon fills.

**Where they are losing, which is the real lever.** Postgres with pgvector is eating the
"just use one database" argument, which used to be MongoDB's own argument. Postgres is well
ahead of MongoDB on DB-Engines and posted the largest year-over-year adoption jump in
Stack Overflow survey history while MongoDB went slightly negative. **Students are exactly
the cohort defaulting to Postgres**, because that is what gets taught. So a room of 200
students where the default agent-memory substrate is Atlas plus Voyage attacks precisely
where they are losing. That is worth real money to them in a way that a logo is not.

**The metric that matters.** Leadership quotes multi-feature attach on earnings calls:
45% of $100K+ ARR customers now use two or more platform features, up from 37%, driven by
vector and text search adoption. The recurring north-star phrase is "new workload
acquisition." So the deliverable is **new clusters running a second feature**, not free
tier signups. A track that requires Vector Search plus automated embeddings produces
exactly that artifact. Put this number in the deck, not the cold email.

**They already have the credit currency.** MongoDB for Startups hands out Atlas credits
*and* Voyage tokens, so nothing new has to be invented to give hackers something.

### Consequences for the ask

- **Lead with INTERFACE, not MOLTEN. I had this backwards.** MongoDB ran the Agentic
  Memory and Context Engineering hackathon at **Shack15 in SF on Oct 11 2025, explicitly
  for SF Tech Week**, via Cerebral Valley. INTERFACE is Oct 10 to 11 2026, the same slot
  one year later. I previously said INTERFACE would collide with something of theirs and
  we should lead with MOLTEN. That was wrong. They chose that slot deliberately and the
  precedent is the strongest card we have. The offer is their own slot back without them
  having to run the event.
- **Confirm they are not already running their own 2026 version.** They did a NYC
  hackathon on Sept 26 2026 and The Persistent Context Sprint at Build Fest, so the
  cadence is live. This is a question to ask on the call, not an assumption either way.
- **Route to DevRel, not Education.** They fund these out of developer relations.
- **Offer a track, not a logo.** Qualifying should require **Atlas Vector Search plus
  automated Voyage embeddings**. That is the artifact their DevRel person reports upward.
- **September 8 is leverage and it expires.** Both events go live on the official Tech
  Week calendar that day. Locking track sponsors before the traffic wave is a real reason
  for them to move now.
- **Their Q2 FY2027 earnings land Sept 1 2026.** Any figure quoted in a deck should be
  re-checked after that date.

### Do not pitch these, they are dead

**Atlas Device Sync, Atlas Device SDKs, App Services, Functions, Data API, and GraphQL all
hit end of life on Sept 30 2025.** Database Triggers survive, the rest is gone. The shared
chat recommended pitching "Atlas Device Sync and Triggers for syncing heavy assets in
spatial computing," and half of that names a product MongoDB shut down. Data Federation and
Online Archive still exist but get no marketing air and are effectively maintenance mode.

**This makes Convex and MongoDB complementary rather than competing asks.** MongoDB
deliberately exited realtime device sync. So the hour-18 realtime sync problem is Convex,
and persistence, retrieval, and agent memory is MongoDB. Both events can take both.

**Open question for Iana: what tier are we asking for?** A track sponsor ask is normally
somewhere around $3K to $5K. I left the number out of the draft deliberately, because the
a16z grant is already $5K per event and reimbursement-based, and I do not know what you
and Sissi want the sponsor tiers to be. The draft offers a call and a "full sponsorship
breakdown" instead. That breakdown does not exist yet.

**A hook I left out on purpose.** Nina Lopatina did a neuroscience PhD and a Berkeley
postdoc applying machine learning to neural data before moving into DevRel. Given the EEG
work that is a real point of contact, but I think naming it in a cold email reads as
having researched her too closely. Better saved for the call, if there is one.

`MongoDB for Startups` is still not the route. It is for companies under seven years old
at Series A or earlier, so it does not apply to us as an event.

**Two claims from the shared chat I would not act on.** It says MongoDB funnels student
hackathon support through Major League Hacking and that MLH is the reliable path. Their
own events contradict that, and joining an MLH season means an application, their
branding, and their rules, which is a lot to take on for October. The genuinely useful
piece of that thread is free either way: the **GitHub Student Developer Pack already
bundles $50 of Atlas credits**, so hackers can have credits regardless of whether MongoDB
ever replies. Worth putting in the participant guide, and it means the event is not
blocked on this yes.

**`community@convex.dev` and `hackathons@convex.dev` do not exist** — both came back
invalid, so do not guess generic inboxes there.

Who to ask and why is in `outreach-targets.md`. This file is the actual wording, plus
what we know about how to reach each one.

## Addresses

Resolved with Hunter on 2026-08-27 (Sissi's account, `credentials/enrich_keys.env`).
Raw output is in `~/Desktop/projects/techweek-research/hunter_contacts.json`.

Two states worth keeping apart:

- `valid` — Hunter confirmed the mailbox exists. Send freely.
- `accept_all` — the domain accepts all mail, so the mailbox cannot be proven either
  way. Normal for universities. Plausible, not confirmed. Fine to send, just do not be
  surprised by a bounce.

### People

| Target | Address | Check | Score |
|---|---|---|---|
| **Alex McDowell**, World Building | `alex@worldbuilding.institute` | **valid** | 83 |
| **Eddo Stern**, UCLA DMA Chair | `eddostern@arts.ucla.edu` | **valid** | 99 |
| **Tracy Fullerton**, USC Game Innovation Lab | `tfullerton@cinema.usc.edu` | **valid** | 98 |
| **Nathan Burba**, Refactor Games | `nathan@refactorgames.com` | **valid** | 85 |
| **Chloe Duckworth**, Valence Vibrations | `chloe@valencevibrations.com` | **valid** | 82 |
| **David Cobbins**, USC ICT MxR | `cobbins@ict.usc.edu` | accept_all | 83 |
| **David Nelson**, USC ICT MxR | `dnelson@ict.usc.edu` | accept_all | 82 |
| **Santiago Lombeyda**, Caltech CD3 | `slombeyda@caltech.edu` | accept_all | 85 |
| **George Djorgovski**, Caltech CD3 | `gdjorgovski@caltech.edu` | accept_all | 81 |
| **Jenny Rodenhouse**, ArtCenter | `jenny.rodenhouse@artcenter.edu` | accept_all | 81 |
| USC ICT MxR lab inbox | `MxRLab@ict.usc.edu` | accept_all | 74 |
| Metastage general | `team@metastage.com` | **valid** | 100 |
| UCLA DMA department | `dmainfo@arts.ucla.edu` | **valid** | 100 |

**My hand-inferred guess was wrong.** I had written `nelson@ict.usc.edu`; the real one is
`dnelson@`. That is the whole argument for not sending inferred addresses.

Still unresolved: **Christina Heller** (Metastage has only `team@` and `support@`, so use
`team@`), **Steve Anderson** (nothing at any UCLA domain), and **LA ACM SIGGRAPH** (no
mail server we can query, so the sign-up form or Larry Rosenthal remain the route).

### Companies

Pick the person, not the generic inbox. a16z portfolio companies should still go through
Fil first, so these are the fallback if the grant route stalls.

| Company | Best contact | Why that person |
|---|---|---|
| **ElevenLabs** | `yanek@elevenlabs.io` (GTM Director), `matt@` (Dir. GTM) | hackathon sponsorship sits with GTM, not eng |
| **Deepgram** | `yannick.daly@deepgram.com` (**Partner Manager**) | literally the credits-and-partnerships role |
| **Vercel** | `christian.elton@vercel.com` (**Director of Startups**) | the startup-programs door, exactly our ask |
| **World Labs** | `mala@worldlabs.ai` (COO), `ben@` / `jjohnson@` (co-founders) | small team, no DevRel layer yet |
| **Luma AI** | `adriantovalin@lumalabs.ai` (Dir. Strategy & Ops), `amit@` (CEO) | ops owns event partnerships |
| **Cartesia** | `karan@cartesia.ai` (CEO), `brandon@` (co-founder) | they ran their own hackathon, so founders are close to it |
| **Roboflow** | `nick@roboflow.com` (Head of Field Engineering) | field engineering is who they send to mentor |
| **Hume AI** | `jeremy@hume.ai` (Head of Product), `alan@` (CEO) | — |
| **Meshy** | `ethan@meshy.ai` (CEO) | — |
| **Inworld** | `kylan@inworld.ai` (CEO), `michael@` (CTO) | — |
| **Uthana** | `henry@uthana.com` (Head of Operations) | tiny team, ops is the door |
| **Arcturus** | `steve.sullivan@arcturus.studio` (CEO) | VP BizDev scored only 42, so go to the CEO |
| **Cursor / Anysphere** | `adam@cursor.com` (Cofounder), `michaelt@anysphere.co` (CEO) | no partnerships role exists publicly |
| **Ultraleap** | `tom.carter@ultraleap.com` (CEO), `brett.sollers@` (Dir. Sales) | the TOUCH hardware fallback |
| **Polycam** | `contact@polycam.ai` | no individuals published |
| **Sesame AI** | `press@sesame.com` / `info@sesame.com` | **no individuals at all**, so the grant team route matters most here |
| **Snap** | `nshah@snap.com` (Dir. Research), `russ@` (VP Comms) | still no DevRel or loaner contact, see below |

**XDOF returned nothing at `xdof.ai`** — no mail server, no pattern, no addresses. That
is a third strike against it (unconfirmed a16z claim, uncorroborated by two reports, and
now no findable domain). Treat it as not real until proven otherwise.

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

# Now unblocked (Hunter resolved the addresses)

Drafts are ready. Each needs a route before it can go out.

## 5. ArtCenter Immersion Lab, Jenny Rodenhouse

**To:** `jenny.rodenhouse@artcenter.edu` — Hunter found the same address independently,
`accept_all` at score 81. In Gmail drafts.
**cc:** sissiwang@berkeley.edu

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

**To:** `slombeyda@caltech.edu`, cc `gdjorgovski@caltech.edu` — both `accept_all`.
In Gmail drafts. They already collaborate with Jenny Rodenhouse, so if she replies first
it is worth mentioning her by name here.

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

**To:** `alex@worldbuilding.institute` — **valid**, confirmed mailbox, listed as Director.
In Gmail drafts. This is the World Building Institute rather than the USC address, which
is if anything the better door since it is his own organisation.
**cc:** sissiwang@berkeley.edu

**Also now reachable:** `tfullerton@cinema.usc.edu` (**valid**, score 98) for Tracy
Fullerton at the USC Game Innovation Lab, who was on the target list but had no route.

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

**Route: still the weakest one.** Hunter surfaces `nshah@snap.com` (Director of Research)
and `russ@snap.com` (VP Communications) but no developer relations or partnerships role,
and there is no public Spectacles loaner request for organizers. Snap did loan to MIT
Reality Hack and to Reality Hack at AWE, so the route exists privately. Best angles are
still the USC Iovine and Young students who won ImmerseGT on Spectacles, since Snap
already knows that group, or asking USC ICT for the introduction once that thread is
warm. **Do not cold-email the Director of Research about hardware loans.**

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
4. **Once Fil replies**, fire the company asks at the named people in the table above
   rather than at generic inboxes. Deepgram's Partner Manager and Vercel's Director of
   Startups are the two clearest doors on the list.
5. **Drop XDOF** unless someone can produce a primary source. No a16z confirmation, no
   corroboration across reports, and no findable mail domain. Same for SLNG.ai.
6. **Snap still has no route.** It is the only remaining hardware ask with nobody to
   email, so it probably has to come as an introduction from USC ICT.
