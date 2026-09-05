# Active Production Settings — Universal Client

Reusable production configuration referenced by CLAUDE.md's HeyGen Avatar & Voice Configuration and Default Configuration sections. Client-supplied values only — nothing here is inferred or fabricated.

## Active HeyGen Configuration

- **Active HeyGen Avatar ID:** `6c798d11f6b4414d8d1c961e0e4cb306`
- **Active HeyGen Voice ID:** `e659bdb260254a42829d5427e1f3a891`

Both supplied directly by the client. Apply to all episode packages until the client changes them.

## Active Persona

- **Voice profile:** `BVID-EPR-DIRECT-WARM-STRATEGIC-v1.0` (see `personas/Voice.md`)

## Current Batch

- **Topic:** Scholarships
- **Batch quantity:** 20 episodes
- **Episode duration:** 10 minutes (~1,500 spoken words each)
- **Audience:** College-bound high school students and their parents/guardians researching how to pay for higher education
- **Publishing cadence:** 3 episodes/week (Sun/Wed/Fri), starting Sunday
- **Batch progress:** Episodes 1–2 complete

## Multi-Platform Social Publishing — Tooling Options

Reference notes for the "Social publishing" section of `CLAUDE.md` (Facebook, Instagram, LinkedIn).

- **For hands-on personal use** (a person clicks "post"): **Buffer** — clean scheduling across Facebook, Instagram, and LinkedIn, solid free tier. **Metricool** is a strong alternative if analytics should be bundled in too.
- **For building it into the app itself** (an API the app's own "Publish" button calls): **Ayrshare** — a single API built specifically for developers embedding multi-platform publishing into their own SaaS product, rather than a tool end-users log into separately. Using it would replace the spec's "guided step-by-step connection form" with one API integration instead of three separate platform OAuth flows to build and maintain.

Decision on which path to use for this app is still open as of this note.
