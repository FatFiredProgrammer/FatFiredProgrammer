# FatFiredProgrammer

Retired software engineer and architect, roughly forty years of it, most of it in C# and .NET.
EE undergrad. Retired in 2019 to Columbus, Nebraska, where the most interesting software problems
turn out to be in a field rather than a data centre.

The handle is the thesis: fat FIRE — financially independent, retired early, with enough margin
that the question stopped being *can I afford this* and became *what should I build today*.
Lately the answer is mostly farming.

## What I'm working on

**Precision agriculture.** Turning what the equipment records into something a farmer can act
on. Yield, as-applied and prescription data arrive in a dozen vendor formats; the work is
normalising them onto the AgGateway ADAPT model, reconciling grain-cart loads against field and
destination totals, and keeping field boundaries and point data where they can be queried a
season later. ADAPT is mapped explicitly rather than auto-serialised — an upstream rename should
break my build, not quietly change what's stored.

**Farm operations and automation.** ESP32-S3 controllers on MQTT running pumps, bins and assorted
farm equipment (and a koi pond), firmware in C++/PlatformIO talking to a .NET back end on Azure.
Physical systems fail in ways web apps don't — a pump that doesn't run is a dead fish or a wet
bin, not a stack trace — so most of the interesting work is in the failure paths.

**AI as a working tool.** Agentic development in earnest rather than as a demo: Claude Code
driving real multi-project work, and MCP servers — farm, precision-ag, devops — that give an
agent the context it otherwise lacks. Much of the effort goes into the unglamorous half:
conventions, boundaries, and instructions precise enough that an agent can be pointed at one
subsystem and trusted inside it. Generation isn't the hard problem; scoping is.

**Financial modelling, still.** A .NET retirement-modelling and simulation engine for the
withdrawal-phase questions, with its own expression language (lexer, Pratt parser, AST) so
scenarios are written rather than hard-coded.

## Stack

**Current** — C# 14 / .NET 10 · Azure (Container Apps, App Configuration, Key Vault, Storage,
managed identity, Bicep) · Blazor · MCP · DocumentDB · xUnit · Docker · GitHub Actions

**Ag and embedded** — AgGateway ADAPT · ESP32-S3, C++/PlatformIO · MQTT · Redis

**Career** — C# and .NET across most of the last two decades · SQL Server and T-SQL ·
distributed and layered service architecture · Windows desktop and services

**Earlier** — assembly, C, C++, MongoDB, and a long tail of things that were load-bearing at the
time and are now history

## Interests

Precision ag and the data it throws off · farm equipment that ought to work and doesn't ·
agentic development and MCP · software architecture, especially where the boundaries go and why ·
embedded work close to the metal · FIRE and the withdrawal-phase maths · koi and pond chemistry

**Favorites** — [the repos I've starred](https://github.com/FatFiredProgrammer?tab=stars)

## Not looking for work

Genuinely retired. Always happy to talk shop.
