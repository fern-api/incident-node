## 1.0.2 - 2026-01-16
* refactor: remove static User-Agent header from default headers
* Remove hardcoded User-Agent header from the base client configuration to allow for more flexible user agent management. This change eliminates the static version reference and enables dynamic user agent handling in the SDK.
* Key changes:
* Remove "User-Agent": "@fern-api/incidentio/1.0.1" from default headers object
* Maintain all other Fern SDK identification headers
* Simplify header configuration in BaseClient
* 🌿 Generated with Fern

## 0.0.19528 - 2026-01-13
* docs: update SDK branding from Fern to Incident.io
* Update the SDK documentation and headers to correctly reflect the Incident.io branding instead of generic Fern branding. This improves the developer experience by clearly identifying the service provider.
* Key changes:
* Update README title to "Incident.io TypeScript Library"
* Update description to reference Incident.io APIs instead of Fern APIs
* Remove User-Agent header containing SDK version information
* 🌿 Generated with Fern

