# Hi, I'm Chris

CS junior at CU Boulder. I build full-stack products using Claude Code as my primary development environment.

## CampusGig | [campusgig.app](https://campusgig.app)

A production two-sided marketplace where verified .edu students sell professional services and businesses post hiring requests. Built to help students gain real-world experience and bridge the gap between classroom learning and industry expectations.

**Solo-built and deployed** with Next.js 16, React 19, TypeScript, Prisma 7, Neon Postgres, Stripe Connect, Clerk, Vercel, and 10+ other integrations.

### Key Technical Highlights

- Stripe Connect escrow payment system with manual-capture authorization, automated release cron, dispute resolution, and refund protection
- Real-time messaging with quote negotiation, order delivery workflow, and review/rating system
- Admin dashboard with content moderation, dispute resolution, and broadcast email system
- Two-role access control with .edu verification, SEO-optimized profiles with JSON-LD
- 241 unit/integration tests (Vitest) + Playwright e2e suite
- GitHub Actions CI/CD, Sentry error tracking, PostHog analytics, Upstash rate limiting

### Built with Claude Code

I use Claude Code as my daily development environment. For CampusGig, I wrote 6 custom sub-agents (verifier, schema reviewer, logic checker, content sync, context keeper, pre-flight), custom skills for repeatable workflows, agent teams for parallelized feature development, and MCP server integrations (Playwright, Figma, Context7).

## Tech Stack

**Languages:** TypeScript, JavaScript, Python, C/C++, SQL, Java

**Frameworks:** Next.js, React, Node.js, Prisma, PostgreSQL, Stripe Connect, Clerk, Vercel

**Tools:** Claude Code, Git, Vitest, Playwright, Sentry, PostHog, GitHub Actions CI/CD

## Links

- [campusgig.app](https://campusgig.app)
- [LinkedIn](https://linkedin.com/in/christophercoleman)
