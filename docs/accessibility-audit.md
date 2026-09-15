# Accessibility Baseline Audit

## 1. Audit Overview

This audit evaluates the accessibility of a real public-facing service website. The purpose is to identify common accessibility barriers and document practical remediation steps for building more inclusive digital services.

### Audit Methods

- Lighthouse accessibility audit
- Keyboard-only navigation
- Manual visual inspection
- Review of page structure and navigation

## 2. Website Audited

**Website Type:** Public Service Website

**Audit Focus:**
- Keyboard accessibility
- Navigation and focus order
- Form accessibility
- Alternative text
- Semantic structure
- Color and visual accessibility

## 3. Accessibility Findings

### Issue 1: Keyboard Navigation

**Observation:** Some interactive elements should be checked for complete keyboard accessibility.

**Evidence:** Keyboard-only navigation using the Tab key.

**Priority:** High

**Remediation:** Ensure every interactive element can be reached and operated using the keyboard and that the tab order follows a logical sequence.

---

### Issue 2: Visible Keyboard Focus

**Observation:** Focus indicators should remain clearly visible when navigating using the keyboard.

**Evidence:** Manual keyboard navigation test.

**Priority:** High

**Remediation:** Provide a clear `:focus-visible` style for links, buttons, form fields, and other interactive elements.

---

### Issue 3: Alternative Text

**Observation:** Images should have meaningful alternative text when they communicate useful information.

**Evidence:** Accessibility inspection of page images.

**Priority:** Medium

**Remediation:** Add descriptive `alt` text to informative images. Decorative images should use an appropriate empty alternative attribute.

---

### Issue 4: Form Labels

**Observation:** Form controls should have clear and programmatically associated labels.

**Evidence:** Manual inspection of input and form elements.

**Priority:** High

**Remediation:** Use semantic `<label>` elements and correctly associate them with their corresponding form controls.

---

### Issue 5: Semantic Page Structure

**Observation:** Headings and navigation landmarks should follow a meaningful hierarchy.

**Evidence:** Manual inspection of page structure.

**Priority:** Medium

**Remediation:** Use semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`, with headings arranged in a logical hierarchy.

## 4. Remediation Priority

| Priority | Action |
|---|---|
| High | Fix keyboard accessibility |
| High | Improve visible focus indicators |
| High | Correct form label associations |
| Medium | Improve alternative text |
| Medium | Improve semantic page structure |

## 5. Keyboard Navigation Test

The website was tested using keyboard-only interaction.

### Test Procedure

1. Open the website.
2. Do not use the mouse.
3. Press `Tab` repeatedly.
4. Check whether focus moves logically.
5. Use `Enter` or `Space` to activate controls.
6. Use `Shift + Tab` to move backwards.
7. Check whether any interactive element is unreachable.
8. Check whether focus remains visible.

## 6. Evidence

The following evidence should be added to this repository:

- Lighthouse accessibility report screenshot
- Keyboard navigation screenshot
- Accessibility issue screenshots
- Page structure or navigation screenshot

Screenshots are stored in:

`docs/screenshots/`

## 7. Conclusion

The audit establishes an accessibility baseline for the selected public-facing service website. The findings focus on keyboard accessibility, focus visibility, forms, alternative text, and semantic structure.

The identified issues can be addressed through semantic HTML, accessible form design, clear focus indicators, meaningful alternative text, and systematic keyboard testing.

## 8. Next Steps

The next phase is to create a maintainable full-stack project foundation with separate client, server, documentation, and test boundaries.

The first vertical feature slice will demonstrate an accessible client interface communicating with a server API.
