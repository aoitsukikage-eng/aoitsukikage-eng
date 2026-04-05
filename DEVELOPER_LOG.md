# Developer Journal

- Repository: `aoitsukikage-eng/aoitsukikage-eng`
- Period Covered: 2026-01-26 to 2026-04-06 (Asia/Taipei)
- Total Commits: 44
- Generated At: 2026-04-06 02:00:39 +0800

## High-Level Milestones

1. **Foundation (2026-01-26)**
- Initial profile README established and then simplified for clarity.

2. **Icon/Identity Iteration (2026-03-09)**
- Introduced custom SVG assets and iterated pronoun/icon visual language.

3. **Tokyo Night Redesign Wave (2026-03-18)**
- Major visual overhaul plus several rapid UI/spacing/copy fixes via feature branch merges.

4. **Solo Leveling System UI Overhaul (2026-04-05 onward)**
- Rebuilt profile into game-like HUD panels with custom SVG architecture, animation tuning, section headers, and battle-record integrations.
- Multiple status panel generations (v1-v6.4) were explored and refined based on visual QA.

5. **Caching and Delivery Hardening (2026-04-06)**
- Repeated cache-busting plus filename rotation (`status-core-v6-4.svg`) to force GitHub/Camo refresh consistency.

## Contribution Stats

-     35	YU-HUNG, SHIH
-      7	Isaac Clarke
-      2	Yuhung, Shih

## Most Frequently Changed Files

-      26 README.md
-       6 assets/status-core-v6.svg
-       6 assets/status-core-v6-3.svg
-       4 icons/hammer.svg
-       3 quote.svg
-       3 icons/warhammer.svg
-       2 assets/solo-system-banner.svg
-       2 assets/panel-status.svg
-       2 assets/panel-skills.svg
-       2 assets/panel-records.svg
-       2 assets/panel-links.svg
-       1 warhammer-svgrepo-com.svg
-       1 brand-warhammer-svgrepo-com.svg
-       1 assets/status-core-v6-4.svg
-       1 assets/status-core-v5.svg

## Full Commit Ledger (Chronological)

### 2026-01-26 20:52:36 +0800 | 1f8548a
- Subject: Create README.md
- Author: Yuhung, Shih
- Scope: 1 file changed, 52 insertions(+)
- Files: README.md

### 2026-01-26 20:59:19 +0800 | 7751f3d
- Subject: Refactor README for clarity and conciseness
- Author: Yuhung, Shih
- Scope: 1 file changed, 1 insertion(+), 19 deletions(-)
- Files: README.md

### 2026-03-09 19:47:38 +0800 | 9876d58
- Subject: Add files via upload
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 4 insertions(+)
- Files: brand-warhammer-svgrepo-com.svg, warhammer-svgrepo-com.svg

### 2026-03-09 19:55:29 +0800 | a572f29
- Subject: Add warhammer.svg icon file
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/warhammer.svg

### 2026-03-09 19:58:15 +0800 | d12df40
- Subject: Add hammer.svg icon file
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/hammer.svg

### 2026-03-09 20:01:04 +0800 | e04de7e
- Subject: Modify pronouns in README with images
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: README.md

### 2026-03-09 20:09:33 +0800 | 45a72c7
- Subject: Update hammer.svg
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 4 insertions(+), 2 deletions(-)
- Files: icons/hammer.svg

### 2026-03-09 21:35:22 +0800 | e143091
- Subject: Update hammer.svg
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/hammer.svg

### 2026-03-09 21:35:46 +0800 | c99370b
- Subject: Change hammer SVG color from #A78BFA to #60A5FA
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/hammer.svg

### 2026-03-09 21:37:24 +0800 | 5454b61
- Subject: Change SVG fill color to purple
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/warhammer.svg

### 2026-03-09 21:38:43 +0800 | 7674a31
- Subject: Fix pronouns section formatting in README
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: README.md

### 2026-03-09 21:46:38 +0800 | 036cbcb
- Subject: Change SVG fill color to #6D28D9
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: icons/warhammer.svg

### 2026-03-18 01:37:19 +0800 | 3404d89
- Subject: redesign: visual overhaul with Tokyo Night theme
- Author: Isaac Clarke
- Scope: 1 file changed, 63 insertions(+), 19 deletions(-)
- Files: README.md

### 2026-03-18 01:38:53 +0800 | a8d30d2
- Subject: Merge pull request #1 from aoitsukikage-eng/redesign/profile-v2
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 63 insertions(+), 19 deletions(-)
- Files: (none)

### 2026-03-18 01:40:39 +0800 | 3c9b7d5
- Subject: fix: restore original Gemini banner image as header
- Author: Isaac Clarke
- Scope: 1 file changed, 1 insertion(+), 1 deletion(-)
- Files: README.md

### 2026-03-18 01:44:45 +0800 | 8aabeae
- Subject: feat: improve connect section, quote, and footer design
- Author: Isaac Clarke
- Scope: 2 files changed, 43 insertions(+), 12 deletions(-)
- Files: README.md, quote.svg

### 2026-03-18 01:45:22 +0800 | 219315a
- Subject: fix: split About Me bullets into two-column layout
- Author: Isaac Clarke
- Scope: 1 file changed, 12 insertions(+)
- Files: README.md

### 2026-03-18 01:47:32 +0800 | 58ae9b9
- Subject: Merge pull request #2 from aoitsukikage-eng/redesign/profile-v2
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 56 insertions(+), 13 deletions(-)
- Files: (none)

### 2026-03-18 01:51:16 +0800 | 2c21604
- Subject: fix: table borders, button alignment, quote font size, remove footer
- Author: Isaac Clarke
- Scope: 2 files changed, 9 insertions(+), 7 deletions(-)
- Files: README.md, quote.svg

### 2026-03-18 01:53:46 +0800 | 869efe0
- Subject: Merge pull request #3 from aoitsukikage-eng/redesign/profile-v2
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 9 insertions(+), 7 deletions(-)
- Files: (none)

### 2026-03-18 01:55:38 +0800 | 23f2a81
- Subject: fix: add spacing above connect buttons and quote
- Author: Isaac Clarke
- Scope: 1 file changed, 3 insertions(+), 1 deletion(-)
- Files: README.md

### 2026-03-18 01:57:24 +0800 | 3023af0
- Subject: fix: revert About Me to single column list, remove table
- Author: Isaac Clarke
- Scope: 1 file changed, 13 deletions(-)
- Files: README.md

### 2026-03-18 01:59:07 +0800 | b4b2d64
- Subject: Merge pull request #4 from aoitsukikage-eng/redesign/profile-v2
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 3 insertions(+), 14 deletions(-)
- Files: (none)

### 2026-04-05 03:56:54 +0800 | 416932f
- Subject: feat: redesign profile README with solo leveling style
- Author: YU-HUNG, SHIH
- Scope: 8 files changed, 266 insertions(+), 54 deletions(-)
- Files: README.md, assets/panel-links.svg, assets/panel-records.svg, assets/panel-skills.svg, assets/panel-status.svg, assets/solo-divider.svg, assets/solo-system-banner.svg, quote.svg

### 2026-04-05 04:30:04 +0800 | 9498f6b
- Subject: fix: sharpen panel headers by removing blur filters
- Author: YU-HUNG, SHIH
- Scope: 4 files changed, 32 insertions(+), 32 deletions(-)
- Files: assets/panel-links.svg, assets/panel-records.svg, assets/panel-skills.svg, assets/panel-status.svg

### 2026-04-05 04:43:20 +0800 | 2e41b14
- Subject: fix: add crisp v2 panel headers and bust github image cache
- Author: YU-HUNG, SHIH
- Scope: 5 files changed, 64 insertions(+), 4 deletions(-)
- Files: README.md, assets/panel-links-v2.svg, assets/panel-records-v2.svg, assets/panel-skills-v2.svg, assets/panel-status-v2.svg

### 2026-04-05 18:24:44 +0800 | a45bd4f
- Subject: fix: slow banner motion and replace paused stats endpoints
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 9 insertions(+), 5 deletions(-)
- Files: README.md, assets/solo-system-banner.svg

### 2026-04-05 18:44:00 +0800 | 3b56d0d
- Subject: feat: add status core HUD with class, buffs, and custom loadout icons
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 119 insertions(+), 6 deletions(-)
- Files: README.md, assets/status-core-v1.svg

### 2026-04-05 19:15:03 +0800 | a97d82a
- Subject: refactor: redesign status panel v3 with cleaner hierarchy
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 84 insertions(+), 3 deletions(-)
- Files: README.md, assets/status-core-v3.svg

### 2026-04-05 20:23:19 +0800 | 4266acb
- Subject: refactor: status panel v4 with cleaner top hierarchy
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 83 insertions(+), 3 deletions(-)
- Files: README.md, assets/status-core-v4.svg

### 2026-04-05 20:50:11 +0800 | d92dd8b
- Subject: refactor: status panel v5 with identity and combat split
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 123 insertions(+), 1 deletion(-)
- Files: README.md, assets/status-core-v5.svg

### 2026-04-06 00:06:29 +0800 | f3292b7
- Subject: refactor: status panel v6 clean top layout and restore original intro
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 123 insertions(+), 1 deletion(-)
- Files: README.md, assets/status-core-v6.svg

### 2026-04-06 00:27:41 +0800 | 746a31a
- Subject: fix: move intro line above stats section in status panel
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 35 insertions(+), 41 deletions(-)
- Files: assets/status-core-v6.svg

### 2026-04-06 00:38:39 +0800 | 9a83567
- Subject: style: loosen top label spacing and enlarge intro line
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 38 insertions(+), 38 deletions(-)
- Files: assets/status-core-v6.svg

### 2026-04-06 00:56:01 +0800 | 8a6bc3d
- Subject: refine: equalize stat bar lengths and restyle combat labels
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 47 insertions(+), 41 deletions(-)
- Files: assets/status-core-v6.svg

### 2026-04-06 01:04:42 +0800 | c08b395
- Subject: refine: rebalance combat stats layout and terminology
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 39 insertions(+), 39 deletions(-)
- Files: assets/status-core-v6.svg

### 2026-04-06 01:15:17 +0800 | cbe3ad8
- Subject: refine: move bars to primary row and shift right stats left
- Author: YU-HUNG, SHIH
- Scope: 1 file changed, 39 insertions(+), 39 deletions(-)
- Files: assets/status-core-v6.svg

### 2026-04-06 01:18:56 +0800 | 54da328
- Subject: fix: bust github image cache for status core panel
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 123 insertions(+), 1 deletion(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:25:07 +0800 | 2a9bb4f
- Subject: refine: v6.3 align combat bars and strengthen readability
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 43 insertions(+), 43 deletions(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:31:41 +0800 | e9645b5
- Subject: refine: v6.4a tighten left stat spacing and shift right group left
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 37 insertions(+), 37 deletions(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:36:30 +0800 | da4c9bf
- Subject: refine: shift left stat bars inward and add vertical breathing room
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 40 insertions(+), 40 deletions(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:42:58 +0800 | 181777f
- Subject: refine: match left bar spacing to CRIT rule and lower combat rows
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 40 insertions(+), 40 deletions(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:47:24 +0800 | 335fa14
- Subject: refine: add lower panel breathing room and drop combat block
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 41 insertions(+), 41 deletions(-)
- Files: README.md, assets/status-core-v6-3.svg

### 2026-04-06 01:50:49 +0800 | 665df15
- Subject: fix: force refresh by switching status core svg filename
- Author: YU-HUNG, SHIH
- Scope: 2 files changed, 123 insertions(+), 1 deletion(-)
- Files: README.md, assets/status-core-v6-4.svg

## Notes for Current Solo-Leveling Branch of Work

- Main active visual path currently points to `assets/status-core-v6-4.svg?v=20260406h` in README.
- Latest commit at generation time: `665df15`
- If GitHub profile still appears stale, raw/commit URLs should be used first for truth checks before additional design edits.
