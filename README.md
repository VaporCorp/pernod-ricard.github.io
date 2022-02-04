# OpenBar

Pernod Ricard initiative to promote Open Source and Open Data.

## Initiatives

### HSTS Analyzer
Simplifies the analysis of HTTP Strict-Transport-Security on any website. Provides a score and various informations in regards to HSTS.
- Repository: <https://github.com/pernod-ricard/HSTS-Analyzer>
- API: <https://api.openbar.pernod-ricard.io/v1/hsts/analyze/?url={url}>  
Example: https://api.openbar.pernod-ricard.io/v1/hsts/analyze/?url=https%3A%2F%2Fpernod-ricard.com
- Web App: https://hsts-analyzer.openbar.pernod-ricard.io

### DrHeader
DrHeader is an FOSS tool (not made by Pernod Ricard) that we like. As part of our OpenBar initiative, we decided to host an instance for everyone to (fair) use.
- Repository: https://github.com/Santandersecurityresearch/DrHeader
- API: <https://api.openbar.pernod-ricard.io/v1/dr-header/[http|https]/{domain}>  
Examples:
  - For pernod-ricard.com (https): https://api.openbar.pernod-ricard.io/v1/dr-header/https/pernod-ricard.com
  - For pernod-ricard.io (https): https://api.openbar.pernod-ricard.io/v1/dr-header/https/developer.pernod-ricard.io
  - For google.com (http): https://api.openbar.pernod-ricard.io/v1/dr-header/http/google.com
  - For google.com (https): https://api.openbar.pernod-ricard.io/v1/dr-header/https/google.com
