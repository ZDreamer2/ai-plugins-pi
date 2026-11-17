---
name: ai-marketplace
description: 'Guides AI plugin marketplace development and source collaboration. Use for marketplace sources, plugins, distribution configuration, or source synchronization.'
disable-model-invocation: false
---

# AI plugin marketplace

## Goal

Classify the user's intent and dispatch to the right handler.

## Commands

- `/skill:ai-marketplace develop <request>` - Dispatch to `Develop`
- `/skill:ai-marketplace configure <request>` - Dispatch to `Configure`
- `/skill:ai-marketplace sync <request>` - Dispatch to `Sync`

## Workflows

### Develop

Plan or implement marketplace sources, plugins, builder behavior or generated distributions.

Follow the [marketplace planning guidance](../../codebase/on-plan.md) before planning and the [marketplace build guidance](../../codebase/on-build.md) before implementation.

### Configure

Set up source hosting, automated builds and generated-distribution publication.

Follow the [marketplace repository configuration workflow](workflows/sys/configure/do.md).

### Sync

Synchronize one authoritative marketplace source checkout: inspect local and incoming changes, integrate colleagues' work, commit intended edits and push them while preserving work.

Follow the [marketplace source synchronization workflow](workflows/sync/do.md).
