# Medithor Services - Development TODO

## Completed

✅ Scroll-to-top button (fixed amber, 300px threshold, RAF, mobile hidden)

## Current Task: Reposition WhatsApp Buttons in Services (Mobile)

**Status:** ✅ COMPLETE

**Changes Applied:**

- Mobile (@media ≤900px): `.svc-item` → `grid-template-columns: 3rem 1fr` (2 columns: num | full body)
- `.svc-wa` → `grid-column: 1 / -1; margin-top: 1.5rem; justify-content: center` (full-width below description)

**Result:** WhatsApp buttons now stack below descriptions on mobile, centered, with proper spacing. Desktop unchanged (3-column layout).

**Tested:** Responsive grid stacks correctly, buttons clickable.

## Next Tasks

- [ ] Additional mobile optimizations?

## Future Tasks

- [ ] Any additional mobile optimizations?
