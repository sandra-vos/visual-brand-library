---
title: Pro-Vital Visual Variants
file: projects/pro-vital/config/image-generation/brands/pro-vital/visual-variants.md

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

last_updated: 2026-09-07
---

# Pro-Vital Visual Variants

## Purpose

This Reference defines reusable visual variations of the base Pro-Vital visual identity.

Visual Variants extend or override the visual identity defined by the Brand Guidelines and Visual Style.

Pro-Vital currently uses Visual Variants for two independent dimensions:

- Product Category;
- Audience.

These dimensions MAY be used independently or simultaneously when relevant to the visual context.

---

# Inheritance

Unless explicitly stated otherwise, all Visual Variants defined in this Reference use:

```yaml
inheritance: extend
```

This means that Variant-specific visual characteristics are added to the base Pro-Vital visual identity.

The base Pro-Vital Brand colours and other Brand characteristics remain available for use.

Variant colours MUST NOT be interpreted as replacements for the base Brand palette unless a Variant explicitly uses `override`.

---

# Product Category Variants

Product Category Variants visually distinguish the different Pro-Vital Product Categories.

A Product Category Variant is associated with the Product Category rather than with a specific piece of content.

When a Visual Subject belongs to a Product Category, the corresponding Product Category Variant SHOULD be available to visual Workflows involving that Subject.

The Category colour MAY be combined with the base Pro-Vital Brand colours.

Each Product Category MAY define:

- a primary Category colour;
- supporting Category colours;
- additional Category-specific visual guidance where required.

---

## Vitaminen

```yaml
variant_type: Product Category
name: Vitaminen
inheritance: extend

palette:
  primary: "#70BEC1"
  supporting_1:
  supporting_2:
```

---

## Mineralen

```yaml
variant_type: Product Category
name: Mineralen
inheritance: extend

palette:
  primary: "#A193BE"
  supporting_1:
  supporting_2:
```

---

## Antioxidanten

```yaml
variant_type: Product Category
name: Antioxidanten
inheritance: extend

palette:
  primary: "#7CBB48"
  supporting_1:
  supporting_2:
```

---

## Stofwisseling

```yaml
variant_type: Product Category
name: Stofwisseling
inheritance: extend

palette:
  primary: "#E3A100"
  supporting_1:
  supporting_2:
```

---

## Bewegen

```yaml
variant_type: Product Category
name: Bewegen
inheritance: extend

palette:
  primary: "#698188"
  supporting_1:
  supporting_2:
```

---

## Vetzuren

```yaml
variant_type: Product Category
name: Vetzuren
inheritance: extend

palette:
  primary: "#F06D5D"
  supporting_1:
  supporting_2:
```

---

## Probiotica

```yaml
variant_type: Product Category
name: Probiotica
inheritance: extend

palette:
  primary: "#B56999"
  supporting_1:
  supporting_2:
```

---

## Speciale formules

```yaml
variant_type: Product Category
name: Speciale formules
inheritance: extend

palette:
  primary: "#7B5039"
  supporting_1:
  supporting_2:
```

---

## Lactoferrine

```yaml
variant_type: Product Category
name: Lactoferrine
inheritance: extend

palette:
  primary: "#965A6B"
  supporting_1:
  supporting_2:
```

---

# Product Category Colour Usage

Category colours provide additional visual identity for Products belonging to that Category.

Category colours MAY be used for:

- backgrounds;
- graphical accents;
- shapes;
- supporting illustrations;
- highlighting;
- other appropriate visual elements.

Category colours MAY be combined with the base Pro-Vital Brand palette.

The Product Category colour SHOULD support Product recognition without replacing the overall Pro-Vital identity.

Supporting Category colours SHOULD be used where available to create tonal variation within the Category palette.

---

# Audience Variants

Audience Variants visually identify specific Pro-Vital professional audiences.

The currently defined Audience Variants are:

- Winkels;
- Zorg;
- Sport;
- Verloskunde.

Unlike Product Category Variants, Audience Variants are contextual.

They SHOULD only be applied when content or visual output is explicitly targeted at the corresponding Audience.

A Product MUST NOT permanently inherit an Audience Variant solely because that Product may be relevant to that Audience.

---

## Winkels

```yaml
variant_type: Audience
name: Winkels
inheritance: extend

visual_identity:
  primary_colour: #f06d5d
  icon: winkels
```

---

## Zorg

```yaml
variant_type: Audience
name: Zorg
inheritance: extend

visual_identity:
  primary_colour: #b56999
  icon: zorg
```

---

## Sport

```yaml
variant_type: Audience
name: Sport
inheritance: extend

visual_identity:
  primary_colour: #70bec1
  icon: sport
```

---

## Verloskunde

```yaml
variant_type: Audience
name: Verloskunde
inheritance: extend

visual_identity:
  primary_colour: #e3a100
  icon: verloskunde
```

---

# Audience Variant Usage

Audience Variants SHOULD be used only when the intended communication is specifically targeted at an Audience.

Audience Variants MAY provide:

- the Audience colour;
- the Audience icon.

Audience Variants MUST NOT determine which Products are relevant to an Audience.

Product relevance, targeting and marketing strategy belong to the appropriate Product and strategic knowledge sources.

Visual Variants only define how an applicable Audience MAY be represented visually.

---

# Combining Visual Variants

A Product Category Variant and an Audience Variant MAY be active simultaneously.

Conceptually:

```text
Pro-Vital Brand
       +
Product Category Variant
       +
Audience Variant
       =
Resolved Visual Identity
```

For example, content about a Product MAY use its Product Category visual identity while additionally incorporating an Audience icon or Audience colour when the content is explicitly targeted at that Audience.

The presence of an Audience Variant SHOULD NOT unnecessarily replace or dominate the Product Category identity.

When multiple active Variants define conflicting visual values, the conflict MUST NOT be resolved arbitrarily.

---

# Relationship to Visual Subjects

Visual Subjects MAY identify their applicable Product Category Variant.

Audience Variants SHOULD normally be selected from the context of the active Workflow rather than stored as permanent properties of a Product Visual Subject.

This separation allows the same Product Visual Subject to be used across multiple Audiences.

---

# Visual Assets

Audience icons and other Variant-specific source material are Visual Assets.

They SHOULD be stored separately from this Reference within the active Brand Context's visual source material.

The `icon` value identifies the required Audience Asset semantically. It MUST NOT encode a repository path or file extension.

The applicable Workflow MUST discover the matching Asset through the repository conventions defined by the Visual Standard.

This Reference defines the meaning and usage of those Assets.

The original files remain the authoritative visual source material.

---

# Guiding Principle

> Extend the Pro-Vital identity with context-specific visual characteristics without unnecessarily replacing or fragmenting the underlying Brand.
