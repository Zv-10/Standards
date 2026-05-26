# Figma Issues Tagging Cheat Sheet

## Syntax

`[Tag] (Subtag) Label`

**Example:** `[Design] (Colors) Primary button color mismatch`

### Primary Category Tags
```
[Proto]
[Design]
[Logic]
[Accessibility]
[Copy]
[Content]
[Mobile]
[Desktop]
[Tablet]
```

### Proto Subtags
```
[Proto] (Interaction)
[Proto] (Flow)
[Proto] (Animation)
[Proto] (Responsiveness)
```

### Design Subtags
```
[Design] (Layout)
[Design] (Typography)
[Design] (Colors)
[Design] (Icons)
[Design] (Components)
[Design] (Spacing)
[Design] (Shadows/Effects)
[Design] (Label)
```

### Logic Subtags
```
[Logic] (Validation)
[Logic] (Data)
[Logic] (States)
[Logic] (Permissions)
[Logic] (Business Rules)
[Logic] (Performance)
```

### Accessibility Subtags
```
[Accessibility] (Contrast)
[Accessibility] (ARIA)
[Accessibility] (Keyboard)
[Accessibility] (Screen Reader)
[Accessibility] (Motion)
```

### Copy Subtags
```
[Copy] (Microcopy)
[Copy] (Error Messages)
[Copy] (Empty States)
[Copy] (Consistency)
```

### Content Subtags
```
[Content] (Missing)
[Content] (Length)
[Content] (Images)
[Content] (Real Data)
```

### Mobile Subtags
```
[Mobile] (Touch)
[Mobile] (Responsive)
[Mobile] (Viewport)
[Mobile] (Gesture)
```

### Desktop Subtags
```
[Desktop] (Responsive)
[Desktop] (Hover States)
[Desktop] (Breakpoints)
```

### Tablet Subtags
```
[Tablet] (Responsive)
[Tablet] (Orientation)
```

### Priority/Severity Tags
```
🔴 [Critical]
🟠 [High]
🟡 [Medium]
🟢 [Low]
```

### Status Tags
```
[Status] (Open)
[Status] (In Progress)
[Status] (Ready for Dev)
[Status] (Done)
[Status] (Blocked)
```

### Viewport Tags
```
[Viewport] (Mobile)
[Viewport] (Tablet)
[Viewport] (Desktop)
[Viewport] (All)
```

### Browser/Platform Tags
```
[Browser] (Chrome)
[Browser] (Firefox)
[Browser] (Safari)
[Platform] (Web)
[Platform] (iOS)
[Platform] (Android)
```

---

## Main Tags (Primary Categories)

### [Proto]
Issues related to prototype functionality, interactions, and user flows.

**Subtags:**
- `[Proto] (Interaction)` — Button clicks, hover states, animations not working
- `[Proto] (Flow)` — Navigation paths, missing screens, broken user journeys
- `[Proto] (Animation)` — Transition timing, easing, motion issues
- `[Proto] (Responsiveness)` — Prototype behavior across devices

**Example:** *"Login button doesn't advance to next screen" → `[Proto] (Flow)`*

---

### [Design]
Visual design issues: layout, typography, spacing, colors, components.

**Subtags:**
- `[Design] (Layout)` — Grid misalignment, spacing inconsistencies, positioning
- `[Design] (Typography)` — Font sizes, weights, line heights, hierarchy
- `[Design] (Colors)` — Wrong color used, contrast issues, brand compliance
- `[Design] (Icons)` — Missing icons, inconsistent icon style, sizing
- `[Design] (Components)` — Reusable component inconsistencies or missing variants
- `[Design] (Spacing)` — Padding, margins, gaps not matching design system
- `[Design] (Shadows/Effects)` — Drop shadows, blur, borders inconsistent
- `[Design] (Label)` — Text labels, button text, microcopy issues

**Example:** *"Button text is 12px but should be 14px" → `[Design] (Typography)`*

---

### [Logic]
Functional/backend requirements, data handling, business rules.

**Subtags:**
- `[Logic] (Validation)` — Form validation rules, error states, input constraints
- `[Logic] (Data)` — Data structure, API requirements, field mapping
- `[Logic] (States)` — Empty state, loading state, error state, success state
- `[Logic] (Permissions)` — Role-based visibility, access control
- `[Logic] (Business Rules)` — Conditional logic, calculations, workflows
- `[Logic] (Performance)` — Load times, optimization requirements

**Example:** *"Form should validate email before submission" → `[Logic] (Validation)`*

---

## Additional Main Tags

### [Accessibility]
A11y compliance, WCAG standards, inclusive design.

**Subtags:**
- `[Accessibility] (Contrast)` — Color contrast ratio issues
- `[Accessibility] (ARIA)` — Missing ARIA labels, semantic HTML
- `[Accessibility] (Keyboard)` — Tab order, keyboard navigation
- `[Accessibility] (Screen Reader)` — Alt text, announcement issues
- `[Accessibility] (Motion)` — Avoid flashing/strobing, vestibular sensitivity

**Example:** *"Button has insufficient contrast ratio" → `[Accessibility] (Contrast)`*

---

### [Copy]
Content, wording, messaging, microcopy.

**Subtags:**
- `[Copy] (Microcopy)` — Button labels, placeholder text, helper text
- `[Copy] (Error Messages)` — Error message clarity, tone
- `[Copy] (Empty States)` — Empty state messaging, CTAs
- `[Copy] (Consistency)` — Terminology mismatches, voice/tone

**Example:** *"Error message is unclear" → `[Copy] (Error Messages)`*

---

### [Content]
Missing content, placeholder text, content gaps.

**Subtags:**
- `[Content] (Missing)` — Placeholder text, TBD content
- `[Content] (Length)` — Text overflow, truncation issues
- `[Content] (Images)` — Missing images, wrong image size
- `[Content] (Real Data)` — Needs real data instead of mock data

**Example:** *"This section needs real product images" → `[Content] (Images)`*

---

### [Mobile]
Mobile-specific issues, responsive design, touch targets.

**Subtags:**
- `[Mobile] (Touch)` — Touch target too small, spacing for fingers
- `[Mobile] (Responsive)` — Layout breaks on mobile, scaling issues
- `[Mobile] (Viewport)` — Specific to iPhone/Android dimensions
- `[Mobile] (Gesture)` — Swipe, pinch, long-press interactions

**Example:** *"Button is too small to tap on mobile" → `[Mobile] (Touch)`*

---

### [Desktop]
Desktop-specific issues, large screen layouts.

**Subtags:**
- `[Desktop] (Responsive)` — Layout issues on wide screens
- `[Desktop] (Hover States)` — Missing or inconsistent hover effects
- `[Desktop] (Breakpoints)` — Specific to desktop breakpoints

**Example:** *"Sidebar doesn't appear on desktop view" → `[Desktop] (Responsive)`*

---

### [Tablet]
Tablet-specific issues, medium screen layouts.

**Subtags:**
- `[Tablet] (Responsive)` — Layout doesn't adapt to tablet dimensions
- `[Tablet] (Orientation)` — Landscape vs. portrait issues

---

## Priority/Severity Tags (Add to any issue)

Combine with primary tags for urgency:

- `🔴 [Critical]` — Blocks user flow, major bug, security issue
- `🟠 [High]` — Significant impact, needed before launch
- `🟡 [Medium]` — Should fix, but not blocking
- `🟢 [Low]` — Nice-to-have, polish/refinement

**Example:** *`[Proto] (Flow)` `🔴 [Critical]` — "Login doesn't work on any screen"*

---

## Status Tags (Track resolution)

- `[Status] (Open)` — Newly reported, awaiting triage
- `[Status] (In Progress)` — Designer/dev actively working
- `[Status] (Ready for Dev)` — Design finalized, ready to hand off
- `[Status] (Done)` — Issue resolved and verified
- `[Status] (Blocked)` — Waiting on external dependency

**Example:** *`[Design] (Colors)` `[Status] (In Progress)`*

---

## Device/Viewport Tags (Specify where issue appears)

- `[Viewport] (Mobile)` — iPhone SE, iPhone 12, iPhone 14 Pro Max
- `[Viewport] (Tablet)` — iPad, iPad Pro
- `[Viewport] (Desktop)` — 1920x1080, 2560x1440
- `[Viewport] (All)` — Appears across all viewports

**Example:** *`[Design] (Layout)` `[Viewport] (Mobile)` — "Grid breaks below 375px"*

---

## Browser/Platform Tags (If applicable)

- `[Browser] (Chrome)`
- `[Browser] (Firefox)`
- `[Browser] (Safari)`
- `[Platform] (Web)`
- `[Platform] (iOS)`
- `[Platform] (Android)`

---

## Complete Tagging Examples

**Example 1:**
```
[Proto] (Flow) | 🔴 [Critical] | [Status] (Open)
"Add to cart button doesn't proceed to checkout"
```

**Example 2:**
```
[Design] (Colors) | [Accessibility] (Contrast) | 🟠 [High]
"Primary button text fails WCAG AA contrast ratio"
```

**Example 3:**
```
[Mobile] (Touch) | [Design] (Spacing) | 🟡 [Medium] | [Viewport] (Mobile)
"Submit button touch target is 32px, should be 44px minimum"
```

**Example 4:**
```
[Copy] (Microcopy) | [Logic] (Validation) | 🟢 [Low]
"Error message says 'Invalid input' but should specify 'Email format invalid'"
```

**Example 5:**
```
[Content] (Missing) | [Design] (Layout) | [Status] (Ready for Dev)
"Hero section needs high-res background image (2560x1440px)"
```

---

## Tag Organization Strategy

**By Phase:**
- During design review: Use `[Design]`, `[Copy]`, `[Accessibility]`
- Before handoff: Add `[Logic]`, `[Content]`, `[Status] (Ready for Dev)`
- During dev: Track `[Status]`, use `[Desktop]` / `[Mobile]` / `[Tablet]`
- Before launch: Verify `[Accessibility]` and `[Mobile] (Responsive)`

**Color Coding in Figma (Optional):**
- 🔵 Blue = `[Design]`
- 🟣 Purple = `[Proto]`
- 🟠 Orange = `[Logic]`
- 🟢 Green = `[Accessibility]`
- 🔴 Red = `[Critical]`
- ⚫ Gray = `[Status]`

---

## Quick Reference Checklist

### Must-Have Tags for Every Issue
- [ ] Primary category (`[Proto]`, `[Design]`, `[Logic]`, etc.)
- [ ] Specific subtag if applicable
- [ ] Priority level (`🔴` `🟠` `🟡` `🟢`)
- [ ] Status (optional but recommended)

### Before Design Handoff
- [ ] All `[Design]` issues resolved
- [ ] All `[Accessibility]` issues addressed
- [ ] All `[Copy]` issues approved
- [ ] Issues marked `[Status] (Ready for Dev)`

### Before Launch
- [ ] No `🔴 [Critical]` issues open
- [ ] All `[Mobile]` issues verified
- [ ] All `[Accessibility]` issues compliant
- [ ] All `[Status]` issues marked `Done`


---

aerl.mrtn
