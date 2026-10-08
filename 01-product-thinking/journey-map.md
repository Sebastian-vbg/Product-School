# Future State Journey Map: StreamLine Spotlight

Persona: Priya, The Overwhelmed Browser

## Journey Stages

### Stage 1: Arrive
- **User action:** Opens app to Spotlight shelf -> skips the 15,000-title scroll.
- **Internal state:** Braced for a scroll -> quick, curious relief.
- **Pain point addressed:** Twenty-minute scroll -> instant, small starting point.

### Stage 2: Trust the pick
- **User action:** Reads the curator's note -> learns why a film suits tonight.
- **Internal state:** Wary of algorithms -> reassured by a human voice.
- **Pain point addressed:** Repetitive "Because you watched" rows -> reasoned, human recommendations.

### Stage 3: Decide fast
- **User action:** Chooses from a short shortlist -> decides in minutes, not twenty.
- **Internal state:** Choice anxiety -> confident, low-effort decision.
- **Pain point addressed:** Choice overload -> a finite shortlist worth her evening.

### Stage 4: Watch and return
- **User action:** Finishes the film in-app -> no DVD fallback needed.
- **Internal state:** Evening well spent -> anticipation of next Spotlight.
- **Pain point addressed:** Off-platform substitution -> viewing and loyalty stay with us.

---

## Competitive advantages over the manual workaround

1. **Decides in minutes** -> replaces twenty minutes of scrolling with an actual viewing.
2. **Stays small yet refreshes** -> DVD familiarity without a static, repeating shelf.
3. **Keeps her in-app** -> retains viewing, engagement data and subscription value.

---

## Notes on the journey

- **Stage 4 depends on a technical fix.** Finishing a film cleanly across devices relies on resolving resume-playback (BUG-1061) and watchlist sync (BUG-1058). Without those fixes, a curated pick could still fail at the handoff.
- **Stage 2 leans on supporting research.** The distrust of algorithms comes from Marcus (UXR-02) and Sam (UXR-10), not from Priya herself. Her own interview shows only the scroll-and-bail behavior and the DVD fallback, so it's worth validating with her segment before you commit to curator notes as the trust mechanism.
