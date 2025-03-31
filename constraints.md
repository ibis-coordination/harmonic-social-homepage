---
layout: default
title: Constraints | Harmonic Team
permalink: /constraints
---

# Intentional Design Constraints

The design of Harmonic Team follows several strict rules including the following:

1. No discussion features (comments, chat, direct messages, etc.)
2. No notifications
3. No text search

At first glance, these rules might seem like an odd choice and unnecessarily limiting to the value of the software. And indeed these constraints do make the software somewhat more difficult to use than other group collaboration software applications. However, these rules were chosen for principled reasons that are specific to the goal of effective group coordination.

In general, these constraints are intended to empower users, which by necessity means that users have more responsibility for creating and maintaining the functionality of the system. The software itself does not do the work for you.

The following is an explanation of the principles behind each of these three design constraints and how to fulfill the same need by different means.

## 1. No Discussion Features

Out of all of these design constraints, the rule of no discussion features is likely to be the most counterintuitive. Isn't discussion a necessary part of the coordination process?

Yes and no.

Discussion is only helpful in as much as it surfaces relevant information. However, in the context of group coordination, it often does the opposite by diluting relevant information with tangential information that does not truly warrant the attention it consumes.

### What to use instead of discussion features

All three of Harmonic Team's primary data types (Notes, Decisions, Commitments) have a description field in which users can add links to other items. These links will then show up as backlinks on each linked item's page, meaning that all links are bidirectional.

Thus, backlinks can play a similar role as comments, but they require the new information to stand on its own merits rather than piggy-back on the relevance of the original item. This raises the bar for the relevance of new information.

## 2. No Notifications

Notifications as a software feature encourage passivity in users by interrupting the user's attention at random intervals and by deciding for the user what information they should pay attention to.

### What to use instead of notifications

Harmonic Team has a feature called cycles which allows users to see new information within a given time window. Deciding as a group on the expected frequency with which members will check for new information

## 3. No Text Search

The ability to query data through keyword search discourages proactive information synthesis and encourages hoarding piles of irrelevant information just in case it becomes relevant someday. If you can always just search through it later, why bother organizing it now?

### What to use instead of text search

Every user account in Harmonic Team includes a private scratchpad where users can quickly add whatever text information they wish to capture and reference in the future, including links.

Instead of post hoc search, you should proactively index and synthesize information using your private scratchpad as your short-term memory and shared notes as long-term memory.

It is best practice to regularly create summary notes that synthesize, index, and highlight relevant information, and filter out irrelevant information. Summarization is a necessary step in creating reliable group knowledge.
