# Start here

1. Extract the archive and upload the contents of enterprise-architecture/ to your repository root. Do not upload the ZIP itself as your documentation.
2. Include .github/ if you want the pull request template.
3. Copy a template from reference/templates/ only when you have a subject to document.
4. Put it in the appropriate domain and fill it in as ordinary Markdown.

| Subject | Location |
| --- | --- |
| Department, process, or business capability | business-architecture/ |
| Shared meaning of product, inventory, or order | data-architecture/data-entities/ |
| A system | application-architecture/applications/ |
| Data moving between systems | application-architecture/integrations/ |
| Runtime, network, or technical service | technology-architecture/ |
| Why a significant choice was made | governance/decisions/ |
| Proposed redesign or improvement | change/initiatives/ |

## Keep an integration together

Create application-architecture/integrations/your-integration/README.md. Put purpose, scope, source and target, timing, field mappings, diagrams, failures, monitoring, and recovery in that document. Add supporting files beside it only as needed. Link the application and shared data records; do not copy their definitions.

## Current and proposed

Domain folders describe the current architecture. An initiative holds proposed changes and links the current records. Update the current records after implementation is verified. Label unknowns and proposals explicitly.

## Replacing an older starter

Use a clean repository or a migration branch. Move any real documentation you have added before removing old directories. Uploading this version does not delete previous scripts, schemas, or folders. See MIGRATION.md for path changes.
