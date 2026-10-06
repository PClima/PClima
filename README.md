<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="Pedro Cordeiro Lima — Systems should talk to each other." src="./assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://cordeirolima.net"><img src="https://img.shields.io/badge/portfolio-dev.cordeirolima.net-1A1916?style=for-the-badge&labelColor=3B6D11" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/pedro-cordeiro/"><img src="https://img.shields.io/badge/linkedin-connect-1A1916?style=for-the-badge&logo=linkedin&logoColor=EAF3DE&labelColor=3B6D11" alt="LinkedIn"></a>
  <a href="mailto:pedro@cordeirolima.net"><img src="https://img.shields.io/badge/email-pedro@cordeirolima.net-1A1916?style=for-the-badge&labelColor=3B6D11" alt="E-mail"></a>
</p>

<br>

Most of the software I touch doesn't fail because of bad code — it fails because **two systems that should talk to each other don't**, and a person ends up being the integration layer. I'm a backend developer who likes fixing exactly that.

```yaml
# ~/now.yml — what I'm up to (Oct 2026)

day_job:
  at:   Bosch
  what: conversational AI — building chatbots on Cognigy

building:
  at:   Stako  # co-founder
  what: a website factory — Astro + Directus per client, Neon Postgres, Cloudflare

freelance:
  at:   Cordeiro Lima
  what: connecting the isolated systems of small businesses with no in-house IT

based_in: Hortolândia, SP — Brazil
open_to:  backend & integration projects
```

### 🔌 How I think about it

```mermaid
flowchart TB
    subgraph today["😩 Today — a person is the integration"]
        direction LR
        A[(Spreadsheet)] -. someone copies .-> B[ERP] -. someone exports .-> C[WhatsApp]
    end
    subgraph after["✅ After — the systems talk"]
        direction LR
        D[(Spreadsheet)] <--> I{{Integration}} <--> E[ERP]
        I <--> F[WhatsApp / e-mail]
    end
    today ==> after

    classDef manual fill:#F7F5F0,stroke:#8A7F6E,stroke-dasharray:4 3,color:#1A1916
    classDef sys fill:#EAF3DE,stroke:#3B6D11,color:#1A1916
    classDef core fill:#3B6D11,stroke:#3B6D11,color:#F7F5F0
    class A,B,C manual
    class D,E,F sys
    class I core
    style today fill:transparent,stroke:#8A7F6E,stroke-dasharray:4 3
    style after fill:transparent,stroke:#3B6D11
```

### 🧰 Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=java,nodejs,ts,astro,postgres,tailwind,cloudflare,git,linux&perline=9" alt="Java, Node.js, TypeScript, Astro, PostgreSQL, Tailwind, Cloudflare, Git, Linux">
</p>

<sub>Also in the daily rotation: Directus · Drizzle · Clerk · Railway · n8n · Cognigy</sub>

### 🏢 Been around

**IBM** · **Claro** · **Greenbrier Maxion** · **Bosch**

<sub>Years of enterprise systems integration — now applied to companies that don't have an IT department.</sub>

<br>

<p align="center">
  <sub><i>“Seus sistemas deveriam conversar entre si.”</i></sub>
</p>
