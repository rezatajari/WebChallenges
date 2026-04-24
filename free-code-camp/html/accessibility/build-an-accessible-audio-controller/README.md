# Build an Accessible Audio Controller

README – ARIA Labeling & Accessible UI Challenge

## Overview

This document focuses on building accessible audio controls using semantic HTML and ARIA attributes.
The challenge is to understand how interface elements like buttons and sliders become usable for all users, including those who rely on assistive technologies.

---

## What This HTML Document Demonstrates

### 1. Clear Section Title

The content starts with a heading that announces the purpose of the interface.
This helps screen readers and users quickly understand what the controls relate to.

### 2. Basic Interactive Elements

Two interactive buttons are presented:

* Play
* Mute

Each uses a semantic button element, which is automatically keyboard-accessible.

### 3. Grouped Volume Controls

A volume slider is presented inside a container with two descriptive labels:

* One identifies what the control is
* One explains what it does

This shows how visual and non-visual users rely on text-based descriptions.

### 4. Use of ARIA Attributes

The slider uses an attribute that associates multiple descriptive elements with a single control.
This ensures that assistive technologies read out both the label and the purpose.

---

## Learning Goals

### Accessible Control Design

Understand how:

* Semantic buttons improve usability
* Labels and descriptions support screen reader users
* ARIA attributes connect meaningful text to controls
* Range inputs become accessible with proper referencing

### Real-World Application

These techniques apply directly to:

* Media players
* Sliders and knobs
* Control panels
* Any custom UI element requiring accessibility support

---

## Task for the Learner

Analyze this UI and explain:

1. Why the slider needs both a label and a description
2. How ARIA labelling improves accessibility
3. What would happen if the slider were missing its descriptive text

---
