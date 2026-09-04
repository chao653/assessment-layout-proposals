# Assessment Layout Proposals

HTML prototype comparing layout structures for an assessment answer page (question card + section progress bar), focused on how the layout holds up when the notes panel is expanded.

**Live demo:** https://chao653.github.io/assessment-layout-proposals/

## Tabs

1. **原稿** — current design (baseline)
2. **已出优化稿** — existing optimization: progress bar moved out of the card
3. **已出稿·默认** — existing default state: text-only section indicator, two-column card without the notes region
4. **方案一 · 进度并入顶栏** — section progress becomes top chrome (full-width section tabs with progress rails); the card holds content only
5. **方案二 · 阅读卡×答题卡** — the single card splits into a reading card (passage + notes) and an independent answer card
6. **方案三 · 全宽工作区** — no card: full-bleed workspace; section progress merges into the bottom control bar next to question navigation

Switch tabs with the floating pill at the top left, or press keys 1–6. Click the vertical "Show" strip in each screen (where present) to collapse/expand the notes column.

Base viewport: 1440×800 (auto-scales to fill the window).
