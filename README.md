# SupportAgent

**Agent-as-a-Service for customer support.**

SupportAgent resolves customer conversations through grounded retrieval, controlled account actions, and reliable escalation.

面向客服业务的 Agent：通过可溯源检索、受控账户操作和安全升级机制解决客户问题。

**Status:** Project scaffold · [Portfolio](https://0x0addc001.github.io/#use-cases)

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | Conversations, tickets, policies, account and order events |
| Models | Intent detection, response planning, policy reasoning |
| Training | SFT on resolved cases, DPO for policy adherence |
| Inference | Streaming responses, retrieval, action selection |
| Harness | Order, refund, CRM, and escalation tools |
| Eval | Resolution quality, factual accuracy, safety, compliance |

## Initial scope

- Build a policy-aware conversation state machine.
- Require evidence before factual or account claims.
- Put irreversible actions behind explicit authorization.

## Roadmap

- [ ] Conversation and escalation schemas
- [ ] Retrieval-grounded response baseline
- [ ] Controlled tool execution
- [ ] Resolution and policy evaluation
- [ ] Human review workflow

## Engineering principles

- Prefer clarification over invented facts.
- Keep side effects idempotent and auditable.
- Measure resolution, not message volume.

