# PennPaws

**A Penn student you can trust looks after your pet while you're away.**

PennPaws helps Penn students find a verified fellow student to walk their dog or visit their cat when they travel. Owners answer a few quick questions, AI drafts the request and the care agreement, and nothing is booked until both people approve. It ships as a tool on [penntools.org](https://penntools.org) for Wharton AI Club's AI Product Manager Training, Cohort 3.

| | |
|---|---|
| **Team** | Lu Lu, Esther Li |
| **Status** | Core loop built and tested. Next: browser testing and 5 user tests |
| **Demo day** | Tue 11/17, live on penntools.org |
| **Code** | Branch [`team/pennpaws`](https://github.com/LuLu1016/penn-tools/tree/team/pennpaws/tools/pennpaws) |

## Why it matters

Students with pets get stuck every time they leave campus for recruiting, breaks or a weekend away. Rover and Wag match you with strangers and ask you to trust star ratings. PennPaws only admits verified upenn.edu accounts, so trust comes from the community. We launch the week before Thanksgiving, when hundreds of owners leave at once.

## How it works

```
Owner answers a few quick questions ──► AI writes a request card ──► owner posts it ✋
                                                                           │
Sitter browses open requests and taps "I can help" ◄───────────────────────┘
        │
        ▼
AI drafts a care agreement: dates, visits, keys, food, vet, pay
        │
        ▼
Owner approves ✋ + sitter approves ✋ ──► booked, both see each other's Penn email
```

## Read more

| | |
|---|---|
| [Product overview and problem statement](https://github.com/LuLu1016/penn-tools/blob/team/pennpaws/tools/pennpaws/README.md) | Start here |
| [Product requirements](https://github.com/LuLu1016/penn-tools/blob/team/pennpaws/tools/pennpaws/docs/PRD.md) | The bet, users, principles, metrics, plan |
| [Requirements tracker](https://github.com/LuLu1016/penn-tools/blob/team/pennpaws/tools/pennpaws/docs/REQUIREMENTS.md) | Every feature with acceptance criteria, owner and due date |
| [Architecture](https://github.com/LuLu1016/penn-tools/blob/team/pennpaws/tools/pennpaws/docs/ARCHITECTURE.md) | Sign in, data model, booking states, AI layer, scaling |
| [Design](https://github.com/LuLu1016/penn-tools/blob/team/pennpaws/tools/pennpaws/docs/DESIGN.md) | Screens, survey questions, visual direction |

## About this repository

This is a fork of [whartonAIclub/penn-tools](https://github.com/whartonAIclub/penn-tools), the platform behind penntools.org. PennPaws lives in `tools/pennpaws/` and `apps/web/src/app/tools/pennpaws/` on the `team/pennpaws` branch. The platform's own README is [here](../README.md).
