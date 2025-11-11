---
'astro': patch
---

Add `preventTransition` flag to history state to prevent view transitions on popstate events. This allows custom navigation that updates the URL without triggering a view transition when using browser back/forward buttons.





