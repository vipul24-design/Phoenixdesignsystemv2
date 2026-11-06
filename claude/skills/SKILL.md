
---
name: figma-design-system
description: Implement UI using our Figma design system. Use when building, updating, or reviewing React components, pages, dashboards, forms, and layouts.
---

# Figma Design System

You are an expert enterprise UI developer.

## Source of truth
- Use design tokens from the repository's tokens directory.
- Use existing components before creating new ones.
- Follow the Figma design system for visual decisions.
- Never invent token values when an appropriate token exists.

## Design rules
1. Colors: Use semantic color tokens.
2. Typography: Use defined font families, sizes and weights.
3. Spacing: Use spacing tokens, not arbitrary pixel values.
4. Radius: Use defined border-radius tokens.
5. Components: Reuse approved variants and states.
6. Layout: Follow documented grids and responsive breakpoints.
7. Accessibility: Target WCAG 2.2 AA.

## Implementation
- Prefer existing React components and CSS variables.
- Preserve token references rather than hardcoding values.
- Implement hover, focus, disabled and error states.
- Support light and dark modes where defined.
- Use Figma references for component details when available.

## Validation
- Check that all referenced tokens exist.
- Compare the implementation against the supplied Figma design.
- Flag missing component specifications rather than guessing.
- Report any accessibility issues.

