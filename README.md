## Hi, I'm Breno 👋

Full-stack developer focused on **TypeScript**, **React/Next.js** and end-to-end web products, from idea to deploy. On the backend I also work with **C# / .NET** and **SQL Server**, and I enjoy projects that pair a polished interface with solid data and modeling under the hood.

---

### 🚀 Live projects

**⚽ [Porcento](https://porcento-app.vercel.app/): football in probabilities**  
Brazilian league predictions made simple: win/draw/loss chances, likely scoreline and projected standings, round by round. A clean interface backed by a custom statistical model.  
`Next.js` · `TypeScript` · `Supabase` · `Vercel` · statistical model (Dixon-Coles)

**📸 [Plating](https://plating-five.vercel.app/): AI photo studio**  
Turns a phone photo of a dish into an album of professional shots, with versions ready for every channel (menu, social, delivery). Built for small restaurants and bakeries.  
`Next.js` · `TypeScript` · image processing · generative AI

> These projects' repositories are private. Want to take a look at the code? Just reach out.

---

### 💳 Open-source backend

**🏦 [Wallet / Store-Credit System](https://github.com/brenoPellegrino/wallet-store-credit): money paths done right**  
A wallet and store-credit service built to show depth where it matters most: moving money safely. Append-only ledger, idempotent credits/debits/transfers, concurrency-safe debits with row locks and deadlock-free ordered locking, and transfers wrapped in a single ACID transaction. A covering index cut the balance query from 563 to 6 logical reads, measured with execution plans.  
`C#` · `.NET 8` · `SQL Server` · raw `ADO.NET` · stored procedures · `Docker` · xUnit + CI

**🐺 [Wolverine / CQRS POC](https://github.com/brenoPellegrino/dotnet-wolverine-poc): event-driven .NET with a transactional outbox**  
A .NET API using Wolverine for CQRS and messaging. Commands and queries flow through a message bus, domain events are published and handled, and a transactional outbox over EF Core and PostgreSQL saves each message in the same transaction as the data change and dispatches it after commit, so nothing is lost on failure. Vertical-slice clean architecture, FluentValidation, and integration tests against a real PostgreSQL via Testcontainers.  
`C#` · `.NET` · `Wolverine` · CQRS · transactional outbox · `EF Core` · `PostgreSQL` · Testcontainers · `Docker`

---

### 🛠️ Stack

`TypeScript` · `JavaScript` · `React` · `Next.js` · `Node.js` · `C#` · `.NET` · `Wolverine` · `SQL Server` · `PostgreSQL` · `Supabase` · `HTML` · `CSS` · `Docker` · `Git` · `Vercel`

---

### 📫 Contact

- GitHub: [@brenoPellegrino](https://github.com/brenoPellegrino)
- Email: bdpellegrino@gmail.com
