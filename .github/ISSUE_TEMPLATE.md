---
title: New release available "{{ env.release_name }}"
labels: release
---

A new release is available: {{ env.release_url }}.

## Changelog

{{ env.release_body }}

## ❗ Dotcom integration checklist

> [!NOTE]  
> GitHub Staff only

Please ensure these items are checked before merging.

- Performed successful integration test with `github/github`
  - [ ] Install release `{{ env.release_name }}`
  - [ ] Verify CI passes
- [ ] Manually verify no regressions on the following pages against production:
  - [ ] `/about` (https://github.com/about)
  - [ ] `/education` (https://github.com/education)
  - [ ] `/enterprise` (https://github.com/enterprise)
  - [ ] `/events/universe/recap` (https://github.com/events/universe/recap)
  - [ ] `/features` (https://github.com/features)
  - [ ] `/features/actions` (https://github.com/features/actions)
  - [ ] `/features/ai/github-app` (https://github.com/features/ai/github-app)
  - [ ] `/features/copilot` (https://github.com/features/copilot)
  - [ ] `/features/copilot/ai-code-editor` (https://github.com/features/copilot/ai-code-editor)
  - [ ] `/features/copilot/plans` (https://github.com/features/copilot/plans)
  - [ ] `/home` (https://github.com/home)
  - [ ] `/mobile` (https://github.com/mobile)
  - [ ] `/pricing` (https://github.com/pricing)
  - [ ] `/resources/articles/what-is-application-security` (https://github.com/resources/articles/what-is-application-security)
  - [ ] `/security` (https://github.com/security)
  - [ ] `/security/advanced-security` (https://github.com/security/advanced-security)
  - [ ] `/security/plans` (https://github.com/security/plans)
  - [ ] `/solutions/use-case/devops` (https://github.com/solutions/use-case/devops)
  - [ ] `/why-github` (https://github.com/why-github)
