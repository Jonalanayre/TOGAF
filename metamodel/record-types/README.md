# Record types and homes

| Type | Meaning | Home |
| --- | --- | --- |
| Organization | A team or organizational unit | business-architecture/organizations/ |
| Objective | A desired business outcome | business-architecture/objectives/ |
| Capability | What the business can do | business-architecture/capabilities/ |
| Process | How work happens | business-architecture/processes/ |
| Value stream | Stages delivering value | business-architecture/value-streams/ |
| Business service | An offering consumed by a stakeholder | business-architecture/business-services/ |
| Data domain | A coherent area of data ownership | data-architecture/domains/ |
| Data entity | A shared business information concept | data-architecture/data-entities/ |
| Application | A system with responsibilities | application-architecture/applications/ |
| Application service | A function an application exposes | application-architecture/application-services/ |
| Integration | An interaction or data exchange | application-architecture/integrations/ |
| Technology component | A runtime or infrastructure element | technology-architecture/platforms-and-components/ |
| Network | Connectivity and routing boundaries | technology-architecture/networks/ |
| Technology service | Shared technical functionality | technology-architecture/technology-services/ |
| Environment | A deployment boundary | technology-architecture/environments/ |
| Initiative | Proposed architectural change | change/initiatives/ |
| Decision | A significant choice and its rationale | governance/decisions/ |

## Avoid double documentation

An application service describes what functionality is offered; an integration describes how systems interact. Create both only when they answer different questions. A conceptual data model links shared entity definitions. An integration's mapping describes that flow's transformation, not a second enterprise data dictionary.

Vendor products can support multiple roles. Choose the scope of each record first. Link a technical service to its implementing product rather than copying the product's ownership and lifecycle into multiple records.
