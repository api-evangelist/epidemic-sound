# Epidemic Sound (epidemic-sound)

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
