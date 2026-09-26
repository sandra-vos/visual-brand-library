---
title: Pro-Vital Brand Guidelines
file: projects/pro-vital/config/image-generation/brands/pro-vital/brand-guidelines.md

document_type: Project Reference
layer: Project

version: 1.0.1
status: Active

owner: Pro-Vital
project: Pro-Vital

language:
  system: English
  content: English

reference_type: Brand Guideline
authority: High

scope:
  - All

last_updated: 2026-09-24
---

# Pro-Vital Brand Guidelines

## Purpose

This Reference defines the persistent visual identity of Pro-Vital.

It provides the base Brand identity from which all Pro-Vital visual output inherits.

More specific visual guidance MAY be provided by:

- Visual Style;
- Visual Variants;
- Visual Subjects;
- Image Generation Guidelines.

More specific visual guidance MUST follow the inheritance behaviour defined by the Visual Standard.

---

# Brand Identity

Pro-Vital uses a natural, recognisable visual identity centred around its green colour palette and leaf-based Brand mark.

The visual identity SHOULD remain recognisable across all applications.

---

# Logo

The Pro-Vital logo combines:

- the Pro-Vital wordmark;
- the leaf Brand mark;
- the registered trademark symbol.

Approved logo variants include:

- full-colour logo;
- monochrome logo;
- full-colour logo with descriptor;
- monochrome logo with descriptor.

The descriptor used in the extended logo is:

> VOEDINGSSUPPLEMENTEN

Approved logo source files MUST be used whenever the Pro-Vital logo is reproduced.

The logo MUST NOT be reconstructed, redrawn or approximated when an approved source asset is available.

---

# Brand Mark

The Pro-Vital Brand mark consists of the leaf composition positioned above the `i` within the Pro-Vital wordmark.

The Brand mark MAY be used independently when an approved standalone Brand Mark Asset is available and the intended application permits standalone use.

The geometry and proportions of the Brand mark MUST NOT be reconstructed or altered.

---

# Base Colour Palette

The following colours form the persistent Pro-Vital Brand palette.

## Primary Colour

```yaml
name: Pro-Vital Primary Green
hex: "#8ABE23"
```

The Primary Green is used prominently within the Pro-Vital identity and wordmark.

---

## Secondary Colour

```yaml
name: Pro-Vital Secondary Green
hex: "#006934"
```

The Secondary Green provides the darker Brand colour used within the Pro-Vital identity and wordmark.

---

# Colour Usage

The Primary and Secondary Brand colours MAY be used together.

Visual Variants MAY extend the base Brand palette with additional colours.

When a Visual Variant uses `extend` inheritance:

- the base Brand colours remain available;
- Variant colours MAY be combined with the base Brand colours.

When a Visual Variant uses `override` inheritance:

- explicitly overridden Brand colour values are replaced;
- Brand values that are not explicitly overridden remain inherited.

Colour combinations MUST preserve sufficient readability and visual clarity.

---

# Typography

The primary Pro-Vital typeface is:

```yaml
font_family: Poppins
```

Poppins SHOULD be used for Pro-Vital branded typography unless another approved Visual Reference explicitly defines different typography for a specific application.

Typography hierarchy, weights, sizing and application rules MAY be further defined by the Visual Style.

---

# Relationship to Visual Variants

Visual Variants provide reusable variations of the Pro-Vital base visual identity.

The Pro-Vital Brand Guidelines remain the base visual identity unless a Visual Variant explicitly overrides individual Brand values.

Visual Variants MUST follow the inheritance rules defined by the Visual Standard.

---

# Visual Assets

Approved Pro-Vital Brand Assets are maintained separately from this Reference.

Typical Brand Assets include:

- full-colour logo;
- monochrome logo;
- logo with descriptor;
- standalone Brand mark.

Visual Assets are source material and MUST NOT be embedded into this Reference as substitutes for the original files.

---

# Restrictions

Pro-Vital Brand identity MUST NOT be altered in ways that compromise recognition or consistency.

Unless explicitly permitted by another approved Visual Reference:

- logo proportions MUST NOT be changed;
- logo elements MUST NOT be repositioned;
- logo colours MUST NOT be arbitrarily changed;
- the Brand mark MUST NOT be redrawn;
- typography MUST NOT be replaced without an approved reason;
- unapproved visual effects MUST NOT be applied to the logo.

---

# Relationship to Other Visual References

This Reference defines persistent Brand identity only.

It does not define:

- photography style;
- illustration style;
- general composition;
- Visual Variant palettes;
- Subject-specific visual guidance;
- AI image-generation behaviour.

Those responsibilities belong to their respective Visual References.

---

# Published Representations

This Reference, Visual Style and Visual Variants are the authoritative textual sources for Pro-Vital Brand identity and application, within their existing scopes and inheritance rules.

The `brand.yaml` file configures structured display data, asset selection and publication. Its visual-language and usage summaries are descriptive views, not independent permissions to override these References. Changes to application rules MUST be made in the applicable Reference first.

The public AI reference pack MUST include these approved visual source documents verbatim, both as files and within `brand.json`. It MUST NOT substitute independently maintained usage summaries for their full instructions. Repository commit, source paths, document versions and content hashes identify the exported snapshot; they do not prove that a runtime has inspected it.

Project, Framework, Subject and compliance requirements remain applicable and are not replaced by the public visual pack.

---

# Guiding Principle

> Preserve the recognisable Pro-Vital identity while allowing controlled visual variation through the Project Visual System.
