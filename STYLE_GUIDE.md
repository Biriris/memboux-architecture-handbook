# Editorial Style Guide

## Language

The manuscript is written in English.

Use clear international English. Prefer direct sentences and avoid unnecessary jargon.

## Voice

The preferred voice is:

- authoritative without sounding absolute
- technical without becoming obscure
- practical without becoming shallow
- critical without becoming dismissive

Avoid promotional language, exaggerated claims, and filler.

## Headings

Use sentence case:

```markdown
## Service boundaries and ownership
```

Do not use title case for every word.

## Paragraphs

Prefer focused paragraphs with one central idea.

Avoid one-sentence paragraph chains unless they create intentional emphasis.

## Lists

Use lists only when structure improves comprehension.

Do not convert normal prose into excessive bullet points.

## Terminology

Use terms consistently.

Preferred forms:

- software architecture
- distributed system
- service boundary
- architecture decision record
- quality attribute
- event-driven architecture
- cloud-native
- AI system
- large language model

Define acronyms on first use.

## Code

Use fenced code blocks with a language identifier.

```yaml
service:
  name: example
```

Code should be realistic, minimal, and directly connected to the surrounding explanation.

## Diagrams

Use Mermaid where possible.

Every diagram must have:

- a clear purpose
- readable labels
- a short explanation
- a reference in the surrounding text

## Examples

Use Memboux as the primary continuous case study.

Other examples may be used when they demonstrate a distinct architectural force.

## Claims and references

Distinguish among:

- established fact
- industry practice
- architectural judgment
- hypothesis
- project-specific decision

Add references for historical claims, formal models, research findings, and attributed ideas.

## Closing structure

Every Part should end with:

1. Principle
2. ADR
3. Closing Reflection
4. Next
