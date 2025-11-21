# Build a Tech Conference Schedule Table

README – HTML Table Structure Challenge

## Overview

This document represents a conference schedule organized using an HTML table.
The purpose of this challenge is to help you analyze how a well-structured table communicates information clearly using captions, headers, row scopes, and column scopes.

---

## What This HTML Document Demonstrates

### 1. Use of a Table Caption

The schedule includes a caption that describes the purpose of the table.
This teaches the importance of labeling tables for accessibility and clarity.

### 2. Column Headers

The header row defines four columns:

* Time
* Track A
* Track B
* Track C

Each header uses a column scope to indicate that it applies to the content below it.

### 3. Row Headers

Every row begins with a time value marked with a row scope.
This shows how screen readers and assistive tools understand table orientation.

### 4. Standard Schedule Rows

Each time slot includes three entries corresponding to the three tracks.
This structure reflects typical conference scheduling where multiple sessions run in parallel.

### 5. Merged Rows (colspan)

Some rows merge all track columns into a single cell:

* Break
* Lunch Break

This helps you understand how table merging is used for events that affect all tracks simultaneously.

---

## Learning Goals

### Semantic Table Structure

Understand how:

* Captions describe the table
* `<thead>` and `<tbody>` improve structure
* Headers with scopes enhance accessibility
* Merged cells organize non-standard schedule items

### Real-World Application

This table mirrors how event organizers publish schedules online.
Learning how the structure works prepares you for:

* Timetables
* Calendars
* Dashboards
* Conference or multi-track event layouts

---

## Task for the Learner

Study the structure and explain:

1. Why the table uses scopes for headers
2. When and why `colspan` is applied
3. How the organization improves readability and accessibility