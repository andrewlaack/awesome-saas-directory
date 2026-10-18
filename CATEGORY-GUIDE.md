# Category guide

This guide records the editorial taxonomy used by the README. It does not change the website database or its category URLs. The README sync generator was not present in the website checkout when this taxonomy was prepared; integrate this mapping into that generator before the next sync. This document is guidance, not an automated sync safeguard.

## Naming and placement

- Use short, familiar names that describe the job a tool does. Avoid generic endings such as “Solutions,” “Platforms,” and “Tools” unless they add meaning.
- Use eight browse groups with specific categories beneath them. Give each project one primary home; use tags or related links for secondary capabilities.
- Keep distinct tasks separate even when a category has one entry, such as passwords versus application secrets, or CRM versus customer support.
- AI chat assistants and AI app builders serve different audiences. Desktop applications and libraries should be labeled by their actual purpose.
- Add a category only when an existing one cannot describe the project's main purpose. Do not create category pages purely to target more keywords.
- Keep stable fragment IDs independent of display names. Retain legacy README anchors when renaming or merging sections.

## Previous category → current category

For split categories, the project-placement table below determines the destination.

| Previous category | Current category or categories |
|---|---|
| Machine Learning & AI Development Tools | AI Agents & App Builders; AI Chat Assistants |
| Content Management System Platforms | Content Management Systems (CMS); Knowledge Bases & Documentation |
| Authentication & Single Sign-On Solutions | Authentication & SSO |
| System Monitoring & Alerting Tools | Monitoring & Observability |
| Team Communication & Collaboration Tools | Team Chat & Video Conferencing |
| Web Analytics & Visitor Tracking Tools | Web & Product Analytics |
| API Development & Testing Tools | API Development & Testing |
| Business Intelligence & Data Analytics Tools | Business Intelligence |
| Observability & Performance Tools | Monitoring & Observability |
| Project Management & Planning Tools | Project Management |
| Backend Infrastructure Tools | Backend as a Service |
| Database Administration & Management Tools | Backend as a Service; No-Code Databases |
| Development Environment & IDE Tools | Code Editors & Cloud IDEs |
| E-Commerce & Digital Marketplace Tools | E-Commerce |
| Enterprise Search & Discovery Tools | Search Engines |
| Home Automation & Smart Home Tools | Home Automation; App Deployment & Self-Hosting |
| Internal Tool Development Platforms | Internal Tool Builders |
| Knowledge Base Management Systems | Knowledge Bases & Documentation |
| Personal Finance Management Tools | Personal Finance & Budgeting |
| Platform as a Service Development Tools | App Deployment & Self-Hosting |
| Product Analytics & User Tracking Tools | Web & Product Analytics |
| Software Development & DevOps Tools | Git Hosting & CI/CD |
| Team Productivity & Collaboration Tools | Notes & Personal Productivity; Real-Time Collaboration Libraries |
| Time Tracking & Productivity Tools | Time Tracking |
| Appointment & Resource Scheduling Tools | Appointment Scheduling |
| Community & Forum Management Platforms | Community Forums |
| Cross-Platform Desktop Application Tools | Media Players |
| Customer Engagement & Support Platforms | Customer Support |
| Customer Relationship Management Systems | Customer Relationship Management (CRM) |
| Design & Prototyping Development Tools | Design & Whiteboards |
| Digital Marketing Automation Tools | Email Marketing & Automation |
| Digital Signature & Document Signing Tools | E-Signatures |
| Distributed Cloud Storage Solutions | File Storage & Sharing |
| Document Management & Collaboration Systems | Document Management |
| Email Infrastructure & Marketing Tools | Email Marketing & Automation |
| Enterprise Resource Planning Systems | Enterprise Resource Planning (ERP) |
| Feature Flag & Toggle Management Tools | Feature Flags |
| Form Building & Survey Management Tools | Forms & Surveys |
| HR Management & Employee Tools | HR & Payroll |
| Localization and Translation Platforms | Localization & Translation |
| No-Code Development & Automation Tools | No-Code Databases |
| Note-Taking & Organization Tools | Notes & Personal Productivity |
| Notification & Alert Management Systems | Notification Infrastructure |
| Password Management & Credential Vaults | Password Managers |
| Photo & Video Management | Photo & Video Libraries |
| Product Information Management | Product Information Management (PIM) |
| Remote Access & System Control Tools | Remote Desktop |
| Secrets Management & Security Tools | Secrets Management |
| Social Media Management Platforms | Social Media Management |
| Subscription & Usage-Based Billing Tools | Billing & Subscriptions |
| URL Shortening & Link Management Tools | URL Shorteners |
| User Feedback Collection & Analysis Tools | Forms & Surveys |
| Web Scraping & Crawling Tools | Web Scraping |
| Whiteboarding & Diagramming Tools | Design & Whiteboards |
| Workflow & Process Automation Tools | Workflow Automation |

## Project placement and stable fragments

| Group | Category | Fragment | Projects |
|---|---|---|---|
| AI & Automation | AI Chat Assistants | `ai-chat-assistants` | Open WebUI, Lobe Chat, AnythingLLM, Chatbox, Jan, LibreChat |
| AI & Automation | AI Agents & App Builders | `ai-agents-app-builders` | Dify, AgentDock |
| AI & Automation | Workflow Automation | `workflow-automation` | n8n |
| Analytics & Monitoring | Web & Product Analytics | `web-product-analytics` | Umami, Plausible, Matomo, OpenPanel, PostHog, OpenReplay |
| Analytics & Monitoring | Business Intelligence | `business-intelligence` | Apache Superset, Metabase, Redash |
| Analytics & Monitoring | Monitoring & Observability | `monitoring-observability` | Uptime Kuma, Gatus, OpenStatus, Checkmate, Grafana, Netdata, Sentry, SolidPing |
| Development & Infrastructure | API Development & Testing | `api-development-testing` | Hoppscotch, Insomnia, Scalar |
| Development & Infrastructure | Backend as a Service | `backend-as-a-service` | Appwrite, PocketBase, Supabase |
| Development & Infrastructure | Code Editors & Cloud IDEs | `code-editors-cloud-ides` | CodeEdit, Gitpod |
| Development & Infrastructure | Git Hosting & CI/CD | `git-hosting-ci-cd` | Gitea, GitLab CE |
| Development & Infrastructure | App Deployment & Self-Hosting | `app-deployment-self-hosting` | Coolify, Dokploy, Olares |
| Development & Infrastructure | Search Engines | `search-engines` | Meilisearch, Typesense |
| Development & Infrastructure | Internal Tool Builders | `internal-tool-builders` | Appsmith, Budibase |
| Development & Infrastructure | No-Code Databases | `no-code-databases` | NocoDB, Baserow |
| Development & Infrastructure | Feature Flags | `feature-flags` | Unleash |
| Development & Infrastructure | Notification Infrastructure | `notification-infrastructure` | Novu |
| Development & Infrastructure | Real-Time Collaboration Libraries | `real-time-collaboration-libraries` | Loro |
| Development & Infrastructure | Web Scraping | `web-scraping` | firecrawl |
| Development & Infrastructure | Localization & Translation | `localization-translation` | Tolgee |
| Security & Access | Authentication & SSO | `authentication-sso` | Keycloak, Authentik, ZITADEL, Hanko |
| Security & Access | Password Managers | `password-managers` | Vaultwarden |
| Security & Access | Secrets Management | `secrets-management` | Infisical |
| Security & Access | Remote Desktop | `remote-desktop` | RustDesk |
| Teamwork & Productivity | Team Chat & Video Conferencing | `team-chat-video-conferencing` | Rocket.Chat, Mattermost, Jitsi Meet, Zulip |
| Teamwork & Productivity | Project Management | `project-management` | Plane, Huly Platform, Vikunja |
| Teamwork & Productivity | Knowledge Bases & Documentation | `knowledge-bases-documentation` | Outline, BookStack, Docusaurus |
| Teamwork & Productivity | Notes & Personal Productivity | `notes-personal-productivity` | Zettlr, Maccy |
| Teamwork & Productivity | Time Tracking | `time-tracking` | SolidTime, Kimai |
| Teamwork & Productivity | Appointment Scheduling | `appointment-scheduling` | Cal.com |
| Teamwork & Productivity | Design & Whiteboards | `design-whiteboards` | Penpot, Excalidraw |
| Content & Marketing | Content Management Systems (CMS) | `content-management-systems-cms` | Strapi, Ghost, Payload CMS, Directus |
| Content & Marketing | Community Forums | `community-forums` | Discourse |
| Content & Marketing | Email Marketing & Automation | `email-marketing-automation` | listmonk, Mautic |
| Content & Marketing | Forms & Surveys | `forms-surveys` | Typebot, Formbricks |
| Content & Marketing | Social Media Management | `social-media-management` | Postiz |
| Content & Marketing | URL Shorteners | `url-shorteners` | Dub |
| Business & Commerce | Customer Support | `customer-support` | Chatwoot |
| Business & Commerce | Customer Relationship Management (CRM) | `customer-relationship-management-crm` | Twenty |
| Business & Commerce | E-Commerce | `e-commerce` | Medusa, Saleor |
| Business & Commerce | Enterprise Resource Planning (ERP) | `enterprise-resource-planning-erp` | ERPNext, OpenBooks |
| Business & Commerce | HR & Payroll | `hr-payroll` | Frappe HR |
| Business & Commerce | Billing & Subscriptions | `billing-subscriptions` | Lago |
| Business & Commerce | E-Signatures | `e-signatures` | Documenso |
| Business & Commerce | Document Management | `document-management` | Paperless-ngx |
| Business & Commerce | Product Information Management (PIM) | `product-information-management-pim` | UnoPim |
| Personal & Home | File Storage & Sharing | `file-storage-sharing` | Nextcloud |
| Personal & Home | Personal Finance & Budgeting | `personal-finance-budgeting` | Actual Budget, Firefly III |
| Personal & Home | Photo & Video Libraries | `photo-video-libraries` | Immich |
| Personal & Home | Media Players | `media-players` | IINA |
| Personal & Home | Home Automation | `home-automation` | Home Assistant |

## Sync acceptance checks

1. Preserve every project exactly once, including repository links, descriptions, logos, and star badges.
2. Recalculate project and category totals and per-category counts.
3. Check that every contents link resolves to a unique anchor and that legacy anchors still resolve.
4. Keep the group order and category scope descriptions. Update this guide when a project changes categories.
5. Review new or renamed projects explicitly; do not silently omit projects that have no mapping.

## Recommended next improvements

These are follow-up recommendations, not implemented features.

1. **Verify license and deployment labels.** Record the actual license, whether it is open source or source available, which features are paid, and whether the entry is a hosted app, desktop app, or library. Audit existing “open-source alternative” claims individually. Do not infer readiness or license compliance from GitHub stars.
2. **Make entries easier to compare.** Add a verified directory-profile link beside the repository link, plus last-reviewed date, deployment options, and basic resource requirements. Use structured fields so the website and README share the same facts.
3. **Improve category landing pages on the website.** Give each page a useful introduction, selection criteria, and meaningful differences between its tools. Keep existing URL slugs when changing labels; if URLs must change, add permanent redirects and update internal links, canonicals, and the sitemap. Review merged categories before applying this README taxonomy to the database.
4. **Improve alternative comparisons.** Build on existing alternative pages with evidence about migration, missing features, import/export, and self-hosted versus paid editions. Prioritize comparisons using actual Search Console queries and user demand; no keyword-volume research was performed for this taxonomy.
5. **Make freshness visible.** Track the last editorial review separately from the last automated stats update. Flag archived repositories, changed licenses, broken links, and renamed projects for review.
6. **Evaluate the README layout on mobile.** The current HTML cards preserve existing content but are long. Consider compact entries with one-line descriptions and secondary links after checking GitHub rendering and accessibility.

## SEO rationale and limits

Concise, accurate category names help readers understand headings and links. Google's [title-link guidance](https://developers.google.com/search/docs/appearance/title-link) recommends descriptive, concise titles and avoiding keyword stuffing. Its [people-first content guidance](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) emphasizes useful content and clear sourcing.

These changes improve information architecture; they do not establish search volume or guarantee rankings. README fragments are sections of one document, not independent category landing pages. The website needs its own content and URL migration work to benefit from corresponding changes there.
