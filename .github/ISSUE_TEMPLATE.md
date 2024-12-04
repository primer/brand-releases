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
- [ ] Manually verify regressions on following pages against production:
- `/features/copilot`
- `/enterprise`
- `/enterprise/advanced-security`
- `/articles/security`
- `/articles/security/what-is-security-testing`
- `/features/preview`
- `/features/copilot/getting-started` and `/features/copilot`
- `/solutions/devops`
- `/education`
- `/mobile`
- `/contact-sales`
- `/about/diversity`
