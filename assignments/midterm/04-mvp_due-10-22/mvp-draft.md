# SummerNest: MVP Design (Draft, due Oct 22)

Drafted with Claude (AI) from the team's decisions on 10/19. Items marked [decide] are open for the team.

Assignment asks for three things:
1. Define the MVP
2. Rationale for design choices
3. Link MVP requirements to the riskiest assumptions from the business case

Riskiest assumptions (from our 10/15 business case):
- **R1** Users will pay $29 when Facebook and RedNote are free
- **R2** Enough matching listings exist for the right dates (supply-demand overlap)
- **R3** We can reach relocating interns cheaply in a short window

## Slide 1: Our MVP

**MVP:** a web app where verified students in Seattle and the SF Bay Area list their room for free, find a room by date, and pay $29/year to see full listings and chat.

### Requirements, in priority order

**Must have**

| # | Requirement | Details | Linked to |
|---|---|---|---|
| 1 | Room verification | Host uploads a photo holding their ID inside the room, plus 5 photos from different angles. Our team reviews by hand. Pass gives a "Room verified ✓" badge | R1: verified rooms are what users pay for when free boards exist |
| 2 | Free listing | City, dates, rent, room type, short summary, photos. Optional: "I'm also looking for a room in ___" | R2: free posting grows supply; the extra field captures overlap |
| 3 | Search by city and dates | Filter by city, date range, max rent. Free preview: summary, 1 cover photo, verified badge | R2 |
| 4 | $29/year membership | Unlocks all photos, full details, and chat. One fee covers both host and renter | R1 |
| 5 | Member chat | Only members can send or reply. Listing shows "Host replies on SummerNest" if the host is a member. Non-member hosts see "You have N messages. Join to reply" | R1 |
| 6 | School email sign-up | .edu email from the 6 pilot schools | R3: reach users through schools, no paid identity checks |

**Later:** LinkedIn or ID check for non-students, reviews after a stay, auto-matching, more cities, mobile app

## Slide 2: Why we designed it this way

| Design choice | Rationale | Linked to |
|---|---|---|
| Start with one city pair: Seattle ↔ SF Bay Area | Overlap only works between two cities: a student leaving Seattle for SF lists their Seattle room and searches in SF. One pair builds enough listings faster than 4 cities | R2 |
| Free to post, pay to contact | Supply comes first. Users pay at the moment they want something: a renter who found a room, or a host with messages waiting | R1, R2 |
| One free cover photo + verified badge | Renters can see the room is real before paying, which solves "can't see the room" | R1 |
| Verify the room, not only the person | School email proves who someone is. The ID-in-room photo proves they are in that room now | R1 |
| Manual review, no automated verification | Cheapest way to offer verification at launch. Automate only if users value it | R1 |
| School email sign-up, 6 schools | Campus channels are cheap to reach, and .edu email verifies students for free | R3 |

[decide] Add a rough wireframe of the listing card on slide 1, or save it for the final report?

## Sources

- SummerNest Business Case slides, Oct 15, 2026.
- AI citation (MLA), same format as the 10/8 slides.
