# FatFiredProgrammer

Retired software engineer and architect, roughly forty years of it. EE undergrad, most of the
career in C# and .NET. Retired in 2019 and now build things because they're interesting rather
than because someone is paying for them. Omaha, Nebraska.

The handle is the thesis: fat FIRE — financially independent, retired early, with enough margin
that the interesting question stopped being *can I afford this* and became *what should I build
today*.

## What I'm working on

**Financial modelling.** A .NET solution for retirement modelling and simulation — the
withdrawal-phase questions that only start mattering once the accumulation phase is over. It grew
its own expression language along the way (lexer, Pratt parser, AST) so scenarios can be written
rather than hard-coded, plus a data-acquisition side that exists largely because I wanted out of
Quicken. Layered, volatility-decomposed, and rather more architecture than the problem strictly
demands — that part is deliberate.

**Home and farm automation.** ESP32-S3 controllers on MQTT running a koi pond and assorted farm
equipment, firmware in C++/PlatformIO talking to a .NET back end. Physical systems fail in ways web
apps don't — a pump that doesn't run is a dead fish, not a stack trace — so most of the interesting
work is in the failure paths.

**AI as a working tool.** Agentic development in earnest rather than as a demo: Claude Code driving
real multi-project work, MCP servers to supply the context it otherwise lacks, and a good deal of
effort spent on the unglamorous half — conventions, boundaries, and instructions precise enough
that an agent can be pointed at one subsystem and trusted inside it. Generation isn't the hard
problem; scoping is.

## Stack

**Primary, current** — C# 14 / .NET 10 · Azure (App Configuration, Key Vault, Storage/ADLS,
managed identity, Bicep) · Blazor · xUnit · Docker · Git and GitHub Actions

**Primary, career** — C# and .NET across most of the last two decades · SQL Server and T-SQL · distributed and layered
service architecture · IDesign / volatility-based decomposition · Windows desktop and services

**Earlier** — assembly, C, C++, MongoDB, and a long tail of things that were load-bearing at the
time and are now history

**Current, embedded** — ESP32-S3, C++/PlatformIO, MQTT, Redis

**Picking back up** — the modern frontend stack (TypeScript, Tailwind, Vite) and everything in
.NET and Azure that shipped while I wasn't looking

## Interests

FIRE and the withdrawal-phase maths · retirement tax planning · software architecture, especially
where the boundaries go and why · agentic development and MCP · embedded work close to the metal ·
koi and pond chemistry · farm equipment that ought to work and doesn't

**Favorites** — [the repos I've starred](https://github.com/FatFiredProgrammer?tab=stars)

## Not looking for work

Genuinely retired. Always happy to talk shop.
