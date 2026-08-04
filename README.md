# Epidemic Sound (epidemic-sound)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Epidemic Sound is a Stockholm-based royalty-free music and sound effects licensing platform for video creators, businesses, and platforms. The catalog includes 55,000+ tracks across 390 genres, 250,000+ sound effects, stems and instrumental versions, all under an all-inclusive license that covers mechanical, sync, and public performance rights globally. The Partner Content API ("Epidemic Sound Connect") exposes the full catalog and Epidemic Sound's AI-powered soundtracking tools — Soundmatch (video-to-music recommendation), semantic search, similar-track and similar-section lookup, image-based matching, beat detection, HLS streaming previews, AI voiceover generation, and the new track-versions endpoint that adapts a recording to a target duration while preserving musical structure. An official Model Context Protocol (MCP) server (beta) makes the same catalog and tools available to AI agents at https://www.epidemicsound.com/a/mcp-service/mcp. Access to the Partner API is gated behind a partnership agreement; once signed, partner engineers receive credentials via the Developer Portal and authenticate using API Key, Partner Token, or Epidemic Sound Connect (OAuth 2.0).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/epidemic-sound/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/epidemic-sound/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Music
- Sound Effects
- Royalty-Free Music
- Audio
- Audio Licensing
- Soundtracking
- Sync Licensing
- Creators
- Video
- AI Voiceover
- Semantic Search
- MCP

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Epidemic Sound Partner Content API

Single REST API exposing the entire Epidemic Sound catalog — tracks, collections, moods, genres, sound effects, stems, beats, HLS previews, similar-track/section search, image-based and video-based matching, track-versions generation (beta), AI voiceovers (via the MCP tools), partner audio/image uploads, usage reporting, and safelisting licenses for end-user channels. Authenticates with ApiKey (`x-api-key`), Partner Token (bearer), or Epidemic Sound Connect OAuth (user-scoped). Versioned with `/v0/` path prefix. Hosted in Europe; audio delivered via Fastly's global CDN. No local caching of metadata or collections is permitted by the partner terms.

- **Human URL:** [https://developers.epidemicsound.com/docs/](https://developers.epidemicsound.com/docs/)
- **Base URL:** `https://partner-content-api.epidemicsound.com`

#### Tags

- Music
- Sound Effects
- Tracks
- Search
- Soundtracking
- Voiceover
- Licensing

#### Properties

- [Documentation](https://developers.epidemicsound.com/docs/)
- [Documentation](https://developers.epidemicsound.com/docs/api-reference/)
- [Documentation](https://developers.epidemicsound.com/docs/guides)
- [Swagger U I](https://partner-content-api.epidemicsound.com/swagger)
- [OpenAPI](openapi/epidemic-sound-partner-content-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/epidemic-sound-partner-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epidemic-sound-partner-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.epidemicsound.com)
- [Portal](https://www.epidemicsound.com/business/developers/)
- [Portal](https://developers.epidemicsound.com/)
- [Documentation](https://developers.epidemicsound.com/docs/)
- [Documentation](https://developers.epidemicsound.com/docs/api-reference/)
- [Documentation](https://developers.epidemicsound.com/docs/guides)
- [Getting Started](https://developers.epidemicsound.com/docs/get-started)
- [Authentication](https://developers.epidemicsound.com/docs/authentication)
- [Swagger U I](https://partner-content-api.epidemicsound.com/swagger)
- [OpenAPI](https://partner-content-api.epidemicsound.com/docs/spec.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [M C P](https://developers.epidemicsound.com/docs/mcp/)
- [Pricing](https://www.epidemicsound.com/pricing/)
- [Plans](plans/epidemic-sound-plans-pricing.yml)
- [Rate Limits](rate-limits/epidemic-sound-rate-limits.yml)
- [Fin Ops](finops/epidemic-sound-finops.yml)
- [Blog](https://www.epidemicsound.com/blog/)
- [Blog](https://www.epidemicsound.com/blog/epidemic-sound-api/)
- [Careers](https://www.epidemicsound.com/careers/)
- [About](https://www.epidemicsound.com/about/)
- [Contact](https://www.epidemicsound.com/contact/)
- [Terms of Service](https://www.epidemicsound.com/terms/)
- [Privacy Policy](https://www.epidemicsound.com/privacy-notice/)
- [GitHub Organization](https://github.com/epidemicsound)
- [SDK](https://github.com/epidemicsound/partner-content-api-demo-ios)
- [SDK](https://github.com/epidemicsound/homebrew-epidemicsound)
- [LinkedIn](https://www.linkedin.com/company/epidemic-sound)
- [Twitter](https://twitter.com/epidemicsound)
- [YouTube](https://www.youtube.com/@EpidemicSound)
- [Instagram](https://www.instagram.com/epidemicsound/)
- [Facebook](https://www.facebook.com/epidemicsound)
- [Tik Tok](https://www.tiktok.com/@epidemicsound)
- [Apps](https://www.epidemicsound.com/apps/)
- [Integrations](https://www.epidemicsound.com/integrations/)
- [Partners](https://www.epidemicsound.com/business/partners/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
