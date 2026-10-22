## [dynoxide.dev](https://dynoxide.dev)

The DynamoDB emulator I'm building now.

Software developer and AWS consultant in Manchester. Twenty years of it, mostly agency work, native mobile apps and cloud platforms, and more recently developer tools. I co-founded [Si Novi](https://sinovi.uk) in 2018.

Si Novi is a software development studio and cloud consultancy. We build SaaS platforms and business operations software, and modernise and support systems that clients already run. To talk about a project, email [hello@sinovi.uk](mailto:hello@sinovi.uk) or use the [contact page](https://sinovi.uk/contact-us).

### What's here

**[Dynoxide](https://dynoxide.dev)** - a DynamoDB emulator backed by SQLite, written in Rust. No Docker, no JVM. Runs as an HTTP server, an MCP server, an embedded library, or compiled to WebAssembly in the browser.

**[Parity Suite](https://paritysuite.org)** - an independent DynamoDB conformance suite. It scores every DynamoDB emulator against live AWS DynamoDB, region by region, and grades how far each one diverges. I maintain Dynoxide as well, which is stated on the board; the same tests run against every target.

**[Access Patterns](https://accesspatterns.dev)** - learn DynamoDB by running it in the browser, from your first GetItem through to single-table design.

[Nubo](https://nubo.sinovi.uk), a native DynamoDB client for macOS, iPadOS, Windows and Linux, is a Si Novi project.

### The rest of the stack

Production work is mostly AWS - ECS Fargate or Lambda depending on the job, CDK or arc.codes for infrastructure. DynamoDB is my default data store, which is how the tooling above started. 

Before that it was native iOS and Android for a few years, and I still keep some [plugins and tools](https://martinhicks.dev/projects/open-source) going for the Architect and Enhance ecosystems.

### Elsewhere

I write at [martinhicks.dev](https://martinhicks.dev) - there's a [journal](https://martinhicks.dev/articles) and a [project timeline](https://martinhicks.dev/projects) going back to 2005.

[Bluesky](https://bsky.app/profile/martinhicks.dev) · [Mastodon](https://hachyderm.io/@martinhicks) · [LinkedIn](https://www.linkedin.com/in/martin-hicks-8061748/) · hello@martinhicks.dev
