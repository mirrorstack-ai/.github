# MirrorStack

**The agentic CMS** — an AI-native content platform where modules are discovered and operated by agents.

Tell the agent what a client needs and it composes the app from shared modules. Ship every client a custom app and maintain just one backend.

## Products

MirrorStack is in **early access** and invite-only for now: we're still in early-stage testing and not open to the public yet. For an invite, email [support@mirrorstack.ai](mailto:support@mirrorstack.ai?subject=MirrorStack%20early%20access).

- **[apps](https://apps.mirrorstack.ai)** — compose client apps from shared modules, run by agents
- **[account](https://account.mirrorstack.ai)** — your MirrorStack account: passkeys, OAuth, sessions and permissions

On the roadmap: CRM, finance, project board and analytics.

## Open Source

Apache-2.0 and pre-1.0, so expect breaking changes. Contributions welcome: open an issue and agree the approach before sending a PR.

- **[app-module-sdk](https://github.com/mirrorstack-ai/app-module-sdk)** — Go SDK for building MirrorStack modules
- **[mirrorstack-cli](https://github.com/mirrorstack-ai/mirrorstack-cli)** — CLI to log in, scaffold, develop and deploy modules (deploying needs an invited account)
- **[app-module-client](https://github.com/mirrorstack-ai/app-module-client)** — framework-neutral typed client for application modules
- **[web-ui-kit](https://github.com/mirrorstack-ai/web-ui-kit)** — shared React UI components, with a [Storybook demo](https://mirrorstack-ai.github.io/web-ui-kit/)

## Source-available

Services behind the platform, published so you can check what they do instead of trusting us. Licensed under the Functional Source License (FSL-1.1-ALv2); each release converts to Apache-2.0 two years after it ships.

- **[billing-engine](https://github.com/mirrorstack-ai/billing-engine)** — the billing service: usage metering and Stripe, public so you can check the platform's arithmetic (no new charges are collected through it yet)
- **[dns-delegate-engine](https://github.com/mirrorstack-ai/dns-delegate-engine)** — holds the DNS credentials you can delegate when connecting a custom domain, and nothing else; public so you can check what it can touch (rebuild in progress)

## Community

- 💬 Questions and chat: [Join our Discord](https://discord.gg/QABqwGnXbc)
- 🐛 Bugs and ideas: open an issue in the relevant repo

---

[mirrorstack.ai](https://mirrorstack.ai)
