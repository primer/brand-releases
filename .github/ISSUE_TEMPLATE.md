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
- `/about/diversity`
- `/contact-sales`
- `/education`
- `/enterprise/advanced-security`
- `/enterprise`
- `/features/copilot/getting-started`
- `/features/copilot`
- `/features/preview`
- `/mobile`
- `/resources/articles/security/what-is-application-security`
- `/resources/articles/security`
- `/solutions/devops`
