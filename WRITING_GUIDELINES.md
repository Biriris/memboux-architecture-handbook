# Writing Guidelines

## Chapter objective

Every chapter must teach the reader how to reason, not merely what terminology to memorize.

A strong chapter should answer:

- What problem does this concept address?
- What forces make the problem difficult?
- What trade-offs are involved?
- What changes when the system scales?
- What commonly goes wrong?
- How should an architect decide?

## Recommended chapter structure

```markdown
# Chapter title

## Learning objectives

## Introduction

## Mental model

## Historical context

## Architecture

## Deep dive

## Trade-offs

## Patterns

## Anti-patterns

## Real-world examples

## Memboux example

## Code or configuration example

## Diagram

## Architecture Decision Record

## Principle

## Checklist

## References

## Further reading
```

Not every section is mandatory. Use only sections that add value.

## Part length

Target range:

- 1,500–2,500 words for a standard Part
- longer only when the subject requires it
- shorter only when the material is genuinely complete

## Depth expectations

Do not stop at definitions.

Explain:

- causal mechanisms
- failure modes
- organizational implications
- operational consequences
- evolutionary consequences
- decision criteria

## Trade-offs

Avoid presenting architecture choices as universally correct.

For each significant option, discuss:

- benefits
- costs
- constraints
- reversibility
- operational impact
- team impact
- failure behavior

## Anti-patterns

An anti-pattern section should explain:

1. why the approach initially appears attractive
2. the hidden cost
3. the conditions under which it becomes harmful
4. signals that reveal the problem
5. possible remediation

## Memboux continuity

Memboux should evolve throughout the book.

Keep its:

- business capabilities
- services
- teams
- data
- infrastructure
- incidents
- constraints

consistent across volumes.

## ADR numbering

Use the format:

```text
ADR-0087
```

Never reuse a number.

## Principle numbering

Use the format:

```text
Principle 083
```

Never reuse a number.

## File naming

Use lowercase kebab-case:

```text
chapter-02-service-architecture.md
```

For multi-part chapters:

```text
chapter-02-part-10-service-architecture-anti-patterns.md
```
