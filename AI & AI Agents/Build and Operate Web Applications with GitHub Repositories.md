# Build and Operate Web Applications with GitHub Repositories

The supplied post groups these repositories into a path from interface creation to production deployment. Stars and declared licenses were checked on **10 October 2026**. Values prefixed with `~` are rounded counts shown by GitHub. Star counts can change.

The collection includes projects with different licensing terms. In particular, n8n uses a Sustainable Use License with a separate Enterprise License for `.ee` files, and Dokploy has a mixed license: Apache License 2.0 outside `/proprietary`, with DSAL 1.0 terms for that directory.

## Build the interface

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [wandb/openui](https://github.com/wandb/openui) | ~22.6k | Apache License 2.0 | Generate and render user-interface components from natural-language descriptions. |
| [stackblitz-labs/bolt.diy](https://github.com/stackblitz-labs/bolt.diy) | ~19.9k | MIT License | Prompt, run, edit, and deploy full-stack web applications using a choice of language models. |
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | ~26.9k | Apache License 2.0 | Visually build and edit React applications with AI assistance. |

## Connect the backend

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [supabase/supabase](https://github.com/supabase/supabase) | ~111k | Apache License 2.0 | Provide a Postgres development platform with database, authentication, storage, APIs, and related services. |
| [appwrite/appwrite](https://github.com/appwrite/appwrite) | ~57.6k | BSD 3-Clause License | Provide a backend platform with authentication, databases, storage, functions, messaging, realtime features, and hosting. |
| [payloadcms/payload](https://github.com/payloadcms/payload) | ~45.2k | MIT License | Provide a TypeScript and Next.js framework for building applications and managing content. |

## Automate workflows and background jobs

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) | ~16.5k | Apache License 2.0 | Build and run durable background jobs, workflows, and long-running AI tasks. |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | 206,869 | Sustainable Use License; Enterprise License for `.ee` files ([license](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)) | Connect services and automate workflows, with options to host the automation yourself. |

## Deploy and operate

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [coollabsio/coolify](https://github.com/coollabsio/coolify) | 62,807 | Apache License 2.0 | Deploy and manage applications, databases, and services on self-managed servers. |
| [Dokploy/dokploy](https://github.com/Dokploy/dokploy) | ~37.7k | Mixed: Apache License 2.0 outside `/proprietary`; Dokploy Source Available License (DSAL) 1.0 for `/proprietary` ([Apache terms](https://github.com/Dokploy/dokploy/blob/canary/LICENSE.MD), [DSAL terms](https://github.com/Dokploy/dokploy/blob/canary/LICENSE_PROPRIETARY.md)) | Provide a self-hostable platform for deploying and managing applications and databases. |

## Architecture in the supplied post

**Idea → UI → backend → database → workflows → background jobs → deployment → production**

The post also suggests these example combinations:

- **AI SaaS:** bolt.diy → Supabase → Trigger.dev → Coolify
- **Internal tools:** OpenUI → Appwrite → n8n → Dokploy
- **Content platform:** Onlook → Payload → Trigger.dev → Coolify

These combinations are preserved as recommendations from the supplied post; this note does not claim that each combination has been independently tested.

For the complete project-wide ranking, see [GitHub Repositories Ranked by Stars](../GitHub%20Repositories%20Ranked%20by%20Stars.md).


## Tools used to plan and design the Sonu Singh portfolio

The following repositories informed the portfolio specification, animated components, and design review. Star counts and declared licenses checked on **11 October 2026**.

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [github/spec-kit](https://github.com/github/spec-kit) | 140,786 | MIT License | Give AI coding agents structured processes and reusable templates for specification-driven development. |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 98.4k (18 Oct 2026) | MIT License | Give coding agents art direction, reference images, and browser checks to improve generated interfaces. |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 79,641 | Apache License 2.0 | Provide design guidance, commands, and checks for AI-assisted frontend work. |
| [DavidHDev/react-bits](https://github.com/DavidHDev/react-bits) | 48,891 | MIT License + Commons Clause; restricts selling, sublicensing, or redistributing the components themselves ([license](https://github.com/DavidHDev/react-bits/blob/main/LICENSE.md)) | Provide animated, interactive, customizable React and Next.js components for websites and apps. |

For the complete project-wide ranking, see [GitHub Repositories Ranked by Stars](../GitHub%20Repositories%20Ranked%20by%20Stars.md).
