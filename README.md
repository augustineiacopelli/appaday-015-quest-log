# Quest Log

A Minecraft-inspired homework tracker where assignments become quests. Check one off and earn a randomized achievement toast with XP. Level up to unlock new badge tiers — from Starter all the way to Grandmaster. Built during AppADay Day 15.

## What It Does

Quest Log turns homework assignments into quests. Add any assignment, tap it when it's done, and a Minecraft-style achievement toast slides in with a badge, a title, and an XP reward. XP accumulates in a level bar at the top of the screen. Level up to unlock new badge tiers, each with higher XP rewards and cooler icons. The Active / Completed / All tabs keep the list clean as you work through your day.

## How to Use

1. Type a homework assignment into the input field and tap **+ ADD** or press Enter.
2. Tap any quest card to mark it complete — watch the achievement toast fire.
3. Level up by completing enough quests to fill the XP bar.
4. Check the **Completed** tab to review everything you've finished.
5. Tap × on any card to delete it.

## Technical Notes

- Vanilla HTML, CSS, and JavaScript — no frameworks or dependencies.
- All data persists via `localStorage` so your quests and XP survive page refreshes.
- XP curve starts at 60 XP for level 1→2 and increases by 20 XP per level thereafter.
- Badge tiers unlock at levels 1, 2, 3, 5, 8, and 12. Each tier adds new icons and higher XP values (10–40 per completion) to the achievement pool.
- Fonts loaded from Google Fonts: Press Start 2P and VT323.

## Definition of Complete

- [x] Assignments can be added and deleted
- [x] Completing a quest fires a Minecraft-style achievement toast
- [x] XP is awarded per completion and tracked across sessions
- [x] Level-up overlay fires with particle burst when XP threshold is crossed
- [x] Level-up overlay displays newly unlocked badge tier and badges
- [x] Active quest count (not total) shown in stats chip
- [x] Active / Completed / All filter tabs work correctly
- [x] Fully mobile-friendly at 375px viewport
- [x] Published to GitHub Pages

## Future Updates

-
