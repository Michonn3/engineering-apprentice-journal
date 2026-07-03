# Engineering Principles

## Primary Question

> Why was it designed this way?

## Principle 0: Understanding precedes implementation

## Why?

I learn best when I understand why something exists before using it.

## Tradeoff

This is slower at first, but it helps me build knowledge that transfers across tools.

## Example

Before writing an Express route, I want to understand what Express it, why routes exist, and who talks to whom.

## Principle 1: Software is a network of conversations

## Why?

Commands, requests, and data move between responsible components.

## Example

git push is not just "upload code." It is:

Me → Terminal → Git → GitHub

## Principle 2: Classify before defining

When learning something new:

Dont ask, "What is Kubernetes?" First ask, "What kind of thing is Kubernetes?"

## Principle 3: Every component has one primary responsibility

Examples:

Git tracks history.

Express routes requests.

Mongoose communicates with MongoDB.

Flutter builds interfaces.

## Principle 4: Understanding relationships is more valuable than memorizing components.

Understanding

Flutter
↓
Express
↓
MongoDB

is more valuable than memorizing each technology independently.

## Version Roadmap

### Version 1 - Core Principles

- Document the engineering principles I discover
- Explain why each principle exists
- Include examples from my projects

### Version 2 - Tradeoffs
- Explain when each principle helps
- Explain when it should not be applied
- Compare related principles

### Version 3 - Wisdom
- Add lessons learned
- Record mistakes that changed my thinking
- Refine principles as my experience grows