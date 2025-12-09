# Episode 1: Why Embedded Documents Beat Joins Every Time

**Category:** Data Modeling
**Difficulty:** Beginner

## Overview

Did you know that most MongoDB performance issues come from trying to make it act like a relational database?

## The Challenge

Developers coming from SQL often split data across collections like they would with tables, creating unnecessary complexity and slower queries.

## The Solution

Instead of storing user addresses in a separate collection, embed them directly in the user document. One query instead of two, and you get atomic updates for free. Use this pattern when data is accessed together and has a one-to-one or one-to-few relationship.

## Key Takeaway

This simple change reduced our query time by 80% and eliminated join complexity. Your app gets faster, your code gets simpler.

## Watch the Episode

[View full episode →](https://mikesmongodbminute.com/episodes/why-embedded-documents-beat-joins-every-time)

---

*Part of [Mike's MongoDB Minute](https://mikesmongodbminute.com) - 60-second MongoDB tips*