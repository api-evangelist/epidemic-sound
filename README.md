# Epidemic Sound (epidemic-sound)

Epidemic Sound is a Stockholm-based royalty-free music and sound effects licensing platform for video creators, businesses, and platforms. The catalog includes 55,000+ tracks across 390 genres, 250,000+ sound effects, stems and instrumental versions, all under an all-inclusive license covering mechanical, sync, and public performance rights worldwide. The Partner Content API ("Epidemic Sound Connect") exposes the full catalog and AI-powered soundtracking tools — Soundmatch, semantic search, similar-track/section lookup, image-based matching, beat detection, HLS streaming previews, AI voiceover generation, and track-versions adaptation — gated behind a partnership agreement.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/epidemic-sound/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Music, Sound Effects, Royalty-Free Music, Audio, Audio Licensing, Soundtracking, Sync Licensing, Creators, Video, AI Voiceover, Semantic Search, MCP

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Epidemic Sound Partner Content API

Single REST API exposing the full Epidemic Sound catalog — tracks, collections, moods, genres, sound effects, stems, beats, HLS previews, similar-track/section search, image-based and video-based matching, track-versions generation (beta), AI voiceovers (via the MCP tools), partner audio/image uploads, usage reporting, and safelisting licenses. Authenticates with ApiKey (`x-api-key`), Partner Token (bearer), or Epidemic Sound Connect OAuth. `/v0/` path prefix; European hosting; Fastly CDN delivery.

**Human URL:** [https://developers.epidemicsound.com/docs/](https://developers.epidemicsound.com/docs/)

**Base URL:** `https://partner-content-api.epidemicsound.com`

- [Documentation — Developer Portal](https://developers.epidemicsound.com/docs/)
- [Documentation — API Reference](https://developers.epidemicsound.com/docs/api-reference/)
- [Documentation — Guides](https://developers.epidemicsound.com/docs/guides)
- [SwaggerUI](https://partner-content-api.epidemicsound.com/swagger)
- [OpenAPI](openapi/epidemic-sound-partner-content-api-openapi.yml)
- [Naftiko Capability — Browse & Search](capabilities/browse-and-search.yaml)
- [Naftiko Capability — Tracks](capabilities/tracks.yaml)
- [Naftiko Capability — Sound Effects](capabilities/sound-effects.yaml)
- [Naftiko Capability — Assets](capabilities/assets.yaml)
- [Naftiko Capability — Safelisting](capabilities/safelisting.yaml)
- [Naftiko Capability — Reporting](capabilities/reporting.yaml)
- [Naftiko Capability — Authentication](capabilities/authentication.yaml)
- [Naftiko Capability — Users](capabilities/users.yaml)
- [Naftiko Capability — Beta](capabilities/beta.yaml)

## Common Properties

- [Website — epidemicsound.com](https://www.epidemicsound.com)
- [Portal — Music API for Developers & Platforms](https://www.epidemicsound.com/business/developers/)
- [Portal — Epidemic Sound Connect Developer Portal](https://developers.epidemicsound.com/)
- [Documentation — developers.epidemicsound.com/docs](https://developers.epidemicsound.com/docs/)
- [Documentation — Partner Content API Reference](https://developers.epidemicsound.com/docs/api-reference/)
- [Documentation — Guides](https://developers.epidemicsound.com/docs/guides)
- [GettingStarted](https://developers.epidemicsound.com/docs/get-started)
- [Authentication](https://developers.epidemicsound.com/docs/authentication)
- [SwaggerUI](https://partner-content-api.epidemicsound.com/swagger)
- [OpenAPI — spec.json](https://partner-content-api.epidemicsound.com/docs/spec.json)
- [MCP — Epidemic Sound MCP Server (Beta)](https://developers.epidemicsound.com/docs/mcp/)
- [Pricing](https://www.epidemicsound.com/pricing/)
- [Plans](plans/epidemic-sound-plans-pricing.yml)
- [RateLimits](rate-limits/epidemic-sound-rate-limits.yml)
- [FinOps](finops/epidemic-sound-finops.yml)
- [Blog](https://www.epidemicsound.com/blog/)
- [Blog — Learn how the Epidemic Sound API works](https://www.epidemicsound.com/blog/epidemic-sound-api/)
- [GitHubOrganization](https://github.com/epidemicsound)
- [SDK — Partner Content API Demo (iOS / Swift)](https://github.com/epidemicsound/partner-content-api-demo-ios)
- [SDK — Homebrew tap](https://github.com/epidemicsound/homebrew-epidemicsound)
- [Careers](https://www.epidemicsound.com/careers/)
- [About](https://www.epidemicsound.com/about/)
- [Contact](https://www.epidemicsound.com/contact/)
- [TermsOfService](https://www.epidemicsound.com/terms/)
- [PrivacyPolicy](https://www.epidemicsound.com/privacy-notice/)
- [LinkedIn](https://www.linkedin.com/company/epidemic-sound)
- [Twitter](https://twitter.com/epidemicsound)
- [YouTube](https://www.youtube.com/@EpidemicSound)
- [Instagram](https://www.instagram.com/epidemicsound/)
- [Facebook](https://www.facebook.com/epidemicsound)
- [TikTok](https://www.tiktok.com/@epidemicsound)
- [Apps — Desktop and mobile apps](https://www.epidemicsound.com/apps/)
- [Integrations](https://www.epidemicsound.com/integrations/)
- [Partners](https://www.epidemicsound.com/business/partners/)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Epidemic Sound Partner Content API](openapi/epidemic-sound-partner-content-api-openapi.yml)

### Capabilities (Naftiko)

- [Browse & Search](capabilities/browse-and-search.yaml)
- [Tracks](capabilities/tracks.yaml)
- [Sound Effects](capabilities/sound-effects.yaml)
- [Assets](capabilities/assets.yaml)
- [Safelisting](capabilities/safelisting.yaml)
- [Reporting](capabilities/reporting.yaml)
- [Authentication](capabilities/authentication.yaml)
- [Users](capabilities/users.yaml)
- [Beta](capabilities/beta.yaml)

### Commercial artifacts

- [Plans / Pricing](plans/epidemic-sound-plans-pricing.yml)
- [Rate Limits](rate-limits/epidemic-sound-rate-limits.yml)
- [FinOps Definition](finops/epidemic-sound-finops.yml)

## Notable Features

- 55,000+ royalty-free tracks across 390 genres; 250,000+ sound effects
- Stems and instrumental versions included; all-inclusive global licensing
- Semantic and BPM/mood/key/instrument-filtered search
- Soundmatch — video-frame analysis returning mood-matched recommendations
- Similar-track and similar-section discovery (audio- or track-id-based)
- Track-versions generation (beta) for duration-aware adaptation
- AI voiceover generation surfaced via the MCP server
- Three auth modes: ApiKey, Partner Token, Epidemic Sound Connect (OAuth 2.0)
- Official MCP server (Beta) at `https://www.epidemicsound.com/a/mcp-service/mcp`
- Audio delivery via Fastly CDN; API hosted in Europe
- No local catalog caching permitted; CORS domain whitelisting required for browser clients

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
