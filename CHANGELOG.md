# Changelog

## Website v1.0 - 2026-01-19

### Accessibility, Responsiveness, & Security Improvements

- **Layout CSS**: The layout now relies on Flexbox for centering, which is intrinsically responsive and robust.

- **Refactored Units to `rem`**: Converted all fixed pixel (`px`) values to relative `rem` units (based on 16px root). This ensures the interface scales correctly if the user adjusts their browser's font size settings.

- **Improved Semantic HTML**: Replaced the generic `<div class="attribution">` with the semantic `<footer class="attribution">` element to provide better document structure for screen readers.

- **Added Focus States**: Implemented `:focus-visible` styles for attribution links to ensure keyboard navigation users can clearly see which element is focused.

- **Added protection against "tabnabbing"**: with rel="noopener noreferrer" in the footer link, as a security best practice for links that open in a new tab (target="_blank"). It prevents the new page from potentially accessing the window object of the page.