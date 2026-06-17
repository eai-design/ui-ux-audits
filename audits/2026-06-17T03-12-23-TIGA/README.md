# UI/UX Analysis Package

This package was generated locally by UI/UX Internal Monitor v2.6.0.

## Files

- `ux-monitor.json`: behavior events, styleSnapshot, iconSnapshot, metrics
- `snapshot.html`: high-fidelity HTML snapshot of the current page or latest captured page
- `snapshots/*.html`: all page snapshots captured during monitoring
- `snapshots-manifest.json`: index of captured pages, routes, titles, and capture time
- `screenshots/*.png`: viewport screenshots captured during monitoring
- `DESIGN.md`: preservation-first Design QA source-of-truth spec
- `SKILL.md`: Design QA context instructions
- `README.md`: this file

## Recommended Skill Usage

Upload all files with screenshots and product context, then ask:

```text
請根據產品介紹、screenshots/*.png、ux-monitor.json、snapshots-manifest.json、snapshots/*.html、DESIGN.md、SKILL.md，針對完整操作路徑做 Design QA 設計走查。
第一階段只輸出 design-qa-visual-checklist.html；保留原站 UI 風格與 token，只針對真實問題提供局部 After，主觀項請寫「建議」。
```

## Privacy

No external AI/API was called during package generation.
