<div align="center">

```
████████╗███████╗     ██╗ █████╗ ███████╗
╚══██╔══╝██╔════╝     ██║██╔══██╗██╔════╝
   ██║   █████╗       ██║███████║███████╗
   ██║   ██╔══╝  ██   ██║██╔══██║╚════██║
   ██║   ███████╗╚█████╔╝██║  ██║███████║
   ╚═╝   ╚══════╝ ╚════╝ ╚═╝  ╚═╝╚══════╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=800&color=00FF9C&center=true&vCenter=true&width=560&lines=backend+engineer;builds+distributed+systems;no+shared+db.+no+monoliths.+no+shortcuts." alt="Typing SVG" />

![views](https://komarev.com/ghpvc/?username=thetejascodes&style=flat-square&color=00FF9C&label=VIEWS)
[![blog](https://img.shields.io/badge/blog-hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://hashnode.com/@thetejascodes)
[![location](https://img.shields.io/badge/location-Parbhani,_India-black?style=flat-square)](#)

</div>

---

### `~/whoami.sh`

```bash
$ cat about.txt

Backend developer building systems that survive real failure modes:
crashed services, race conditions, network partitions, retries.

Every project below ships with tests, docker, and an ADR trail
explaining every non-obvious call — not just code that "works on my machine."
```

---

### `~/stack.json`

```json
{
  "languages":   ["TypeScript", "C++"],
  "backend":     ["Node.js", "Express 5"],
  "frontend":    ["React", "Next.js"],
  "data":        ["PostgreSQL", "Drizzle ORM", "MongoDB", "pgvector"],
  "infra":       ["Redis", "Valkey", "RabbitMQ", "WebSockets", "Docker"]
}
```

<div align="center">
<img src="https://skillicons.dev/icons?i=ts,cpp,nodejs,express,react,nextjs,postgres,redis,mongodb,docker&theme=dark" />
</div>

---

### `~/projects --list`

<table>
<tr>
<td width="50%" valign="top">

```
$ cd Flux && cat README.md
```
**quick-commerce as true microservices**

`Gateway · Catalog · Inventory · Order · Payment · Delivery`
— six services, zero shared database, wired together over RabbitMQ.

```diff
+ saga pattern w/ compensating transactions
+ concurrency-safe stock reservations
+ geospatial delivery routing
+ ADR for every architecture call
```

`TypeScript` `PostgreSQL` `Valkey/Redis` `RabbitMQ` `Docker`
[→ repo](https://github.com/thetejascodes/Flux)

</td>
<td width="50%" valign="top">

```
$ cd Grantly && cat README.md
```
**spec-compliant OIDC authorization server**

Not a toy auth demo — real PKCE, rotating refresh tokens,
RFC 7591 dynamic client registration.

```diff
+ AES-256-GCM encrypted client secrets
+ Google + GitHub social login
+ Redis-backed rate limiting
+ full Vitest coverage
```

`Express` `Drizzle ORM` `PostgreSQL` `Redis`
[→ repo](https://github.com/thetejascodes/Grantly) · [→ live](https://grantly-e90w.onrender.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

```
$ cd Unsaid && cat README.md
```
**anonymous real-time chat, built responsibly**

Mood-based stranger matching, verified pseudonymous accounts.

```diff
+ WebSocket chat + image sharing
+ AI icebreakers + AI moderation per message
+ report / block / bans that actually stick
```

`WebSockets` `Redis` `PostgreSQL` `Claude API`
[→ repo](https://github.com/thetejascodes/Unsaid)

</td>
<td width="50%" valign="top">

```
$ cd One-million-checkbox && cat README.md
```
**horizontal scaling, made visible**

1,000,000 checkboxes, one shared board, live for anyone.

```diff
+ toggle -> redis source of truth -> pub/sub fanout
+ any node serves any client, stays in sync
+ proof-of-concept for horizontal scale
```

`Node.js` `Socket.IO` `Redis Pub/Sub`
[→ repo](https://github.com/thetejascodes/One-million-checkbox) · [→ live](https://angelic-energy-production.up.railway.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

```
$ cd Meridian && cat README.md
```
**AI-native Gmail + Calendar client**

Keyboard-first inbox, one AI agent handles email + scheduling.

```diff
+ webhook-driven, zero polling
+ local vector search over full mail history
+ sub-second retrieval
```

`Next.js` `pgvector` `Drizzle` `Corsair MCP`
[→ repo](https://github.com/thetejascodes/Meridian)

</td>
<td width="50%" valign="top">

```
$ cd collabHub && cat README.md
```
**team collaboration platform**

Workspaces, projects, tasks, activity tracking.

```diff
+ workspace-scoped access control
+ React 19 + Vite + Framer Motion frontend
+ Express 5 + MongoDB backend
```

`React 19` `Express 5` `MongoDB`
[→ repo](https://github.com/thetejascodes/collabHub-team-work-space)

</td>
</tr>
</table>

<div align="center">
<sub>18 repos total — <a href="https://github.com/thetejascodes?tab=repositories">browse everything →</a></sub>
</div>

---

### `~/stats --fetch`

<div align="center">
<img height="165" src="https://github-readme-stats-beta-umber-84.vercel.app/api?username=thetejascodes&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true&hide_rank=true" />
<img height="165" src="https://github-readme-stats-beta-umber-84.vercel.app/api/top-langs/?username=thetejascodes&layout=compact&theme=chartreuse-dark&hide_border=true" />
<br>
<img src="https://streak-stats.demolab.com/?user=thetejascodes&theme=highcontrast&hide_border=true" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thetejascodes/thetejascodes/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thetejascodes/thetejascodes/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/thetejascodes/thetejascodes/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

---

<div align="center">

```
$ echo "open to backend / infra collaborations"
> open an issue on any repo above to say hi 👋
```

</div>
