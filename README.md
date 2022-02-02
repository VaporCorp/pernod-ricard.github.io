## OpenBar

Initiate to promote Open Source and Open Data at Pernod Ricard.

## API

### HSTS Analyze
- Description: Simplifies the analysis of HTTP Strict-Transport-Security on any website. Provides a score and various informations in regards to HSTS.
- Repository: [https://github.com/pernod-ricard/HSTS-Analyzer](https://github.com/pernod-ricard/HSTS-Analyzer)
- Endpoint: [https://api.openbar.pernod-ricard.io](https://api.openbar.pernod-ricard.io/v1/hsts/analyze/?url=https%3A%2F%2Fpernod-ricard.com)

### DrHeader
- DrHeader is an FOSS tool (not made by Pernod Ricard) that we like. As part of our OpenBar initiative, we decided to host an instance for everyone to (fair) use.
- Repository: [https://github.com/Santandersecurityresearch/DrHeader](https://github.com/Santandersecurityresearch/DrHeader)
- Endpoint: https://api.openbar.pernod-ricard.io/v1/dr-header/[http|https]/{domain}
- Examples:
  - For pernod-ricard.com (https) [https://api.openbar.pernod-ricard.io/v1/dr-header/https/pernod-ricard.com](https://api.openbar.pernod-ricard.io/v1/dr-header/https/pernod-ricard.com)
  - For pernod-ricard.io (https) [https://api.openbar.pernod-ricard.io/v1/dr-header/https/developer.pernod-ricard.io](https://api.openbar.pernod-ricard.io/v1/dr-header/https/developer.pernod-ricard.io)
  - For google.com (http) [https://api.openbar.pernod-ricard.io/v1/dr-header/http/google.com](https://api.openbar.pernod-ricard.io/v1/dr-header/http/google.com)
  - For google.com (https) [https://api.openbar.pernod-ricard.io/v1/dr-header/https/google.com](https://api.openbar.pernod-ricard.io/v1/dr-header/https/google.com)
