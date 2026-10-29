# Epidemic Sound

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Epidemic Sound is a Stockholm-based royalty-free music and sound effects licensing platform for video creators, businesses, and platforms. The catalog includes 55,000+ tracks across 390 genres, 250,000+ sound effects, stems and instrumental versions, all under an all-inclusive license that covers mechanical, sync, and public performance rights globally. The Partner Content API ("Epidemic Sound Connect") exposes the full catalog and Epidemic Sound's AI-powered soundtracking tools — Soundmatch (video-to-music recommendation), semantic search, similar-track and similar-section lookup, image-based matching, beat detection, HLS streaming previews, AI voiceover generation, and the new track-versions endpoint that adapts a recording to a target duration while preserving musical structure. An official Model Context Protocol (MCP) server (beta) makes the same catalog and tools available to AI agents at https://www.epidemicsound.com/a/mcp-service/mcp. Access to the Partner API is gated behind a partnership agreement; once signed, partner engineers receive credentials via the Developer Portal and authenticate using API Key, Partner Token, or Epidemic Sound Connect (OAuth 2.0).

**Areas:** Music · Sound Effects · Royalty-Free Music · Audio · Audio Licensing · Soundtracking · Sync Licensing · Creators · Video · AI Voiceover · Semantic Search · MCP

## Epidemic Sound on APIs.io

Everything profiled for Epidemic Sound is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/epidemic-sound/](https://apis.io/providers/epidemic-sound/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Epidemic Sound Assets API](https://apis.io/apis/epidemic-sound/epidemic-sound-assets-api/) — These endpoints allows your application to upload assets such as images or audio.
- [Epidemic Sound Authentication API](https://apis.io/apis/epidemic-sound/epidemic-sound-authentication-api/) — Endpoints for user authentication.
- [Epidemic Sound Beta API](https://apis.io/apis/epidemic-sound/epidemic-sound-beta-api/) — These endpoints are in beta.
- [Epidemic Sound Browse & search API](https://apis.io/apis/epidemic-sound/epidemic-sound-browse-search-api/) — These endpoints will allow you to explore the Epidemic Sound library. You can display tracks grouped in curated playlists, moods or genres or use search to…
- [Epidemic Sound Reporting API](https://apis.io/apis/epidemic-sound/epidemic-sound-reporting-api/) — These endpoints will allow you to report how tracks are used in your application.
- [Epidemic Sound Safelisting API](https://apis.io/apis/epidemic-sound/epidemic-sound-safelisting-api/) — Endpoints for managing safelisting licenses. Allows partners to create, list, update, and delete licenses for channels and videos on behalf of their end users.
- [Epidemic Sound Effects API](https://apis.io/apis/epidemic-sound/epidemic-sound-sound-effects-api/) — Endpoints to get sound effect specific information. These endpoints allow you to build a UI to browse and search for sound effects.
- [Epidemic Sound Tracks API](https://apis.io/apis/epidemic-sound/epidemic-sound-tracks-api/) — Endpoints to get track specific information.
- [Epidemic Sound Users API](https://apis.io/apis/epidemic-sound/epidemic-sound-users-api/) — These endpoints allows your application to get user specific information such as liked sounds.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [epidemic-sound](https://apis.io/servers/epidemic-sound/epidemic-sound/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Epidemic Sound Agentic Access](https://apis.io/agentic-access/epidemic-sound/epidemic-sound-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [Partner Content Assets API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-assets-api/)
- [Partner Content Assets Authentication API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-authentication-api/)
- [Partner Content Assets Beta API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-beta-api/)
- [Partner Content Assets Browse & search API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-browse-search-api/)
- [Partner Content API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-partner-content-api/)
- [Partner Content Assets Reporting API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-reporting-api/)
- [Partner Content Assets Safelisting API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-safelisting-api/)
- [Partner Content Assets Sound effects API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-sound-effects-api/)
- [Partner Content Assets Tracks API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-tracks-api/)
- [Partner Content Assets Users API](https://apis.io/collections/epidemic-sound/open-epidemic-sound-users-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Epidemic Sound Authentication](https://apis.io/security/epidemic-sound/epidemic-sound-authentication/)
- [Epidemic Sound Domain Security](https://apis.io/security/epidemic-sound/epidemic-sound-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Epidemic Sound Scopes](https://apis.io/scopes/epidemic-sound/epidemic-sound-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Epidemic Sound Plans Pricing](https://apis.io/plans/epidemic-sound/epidemic-sound-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Epidemic Sound Rate Limits](https://apis.io/rate-limits/epidemic-sound/epidemic-sound-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Epidemic Sound Finops](https://apis.io/finops/epidemic-sound/epidemic-sound-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.epidemicsound.com)
- [Documentation](https://developers.epidemicsound.com/docs/)
- [Getting started](https://developers.epidemicsound.com/docs/get-started)
- [Pricing](https://www.epidemicsound.com/pricing/)
- [Blog](https://www.epidemicsound.com/blog/)
- [Terms of service](https://www.epidemicsound.com/terms/)
- [Privacy policy](https://www.epidemicsound.com/privacy-notice/)
- [GitHub](https://github.com/epidemicsound)

## API Evangelist rating

**Kin Score 36.6** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 50.9 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 52.4 |
| Access clarity | 26.3 |

**Agent readiness 52.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/epidemic-sound/](https://apis.io/providers/epidemic-sound/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Epidemic Sound: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/epidemic-sound/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
