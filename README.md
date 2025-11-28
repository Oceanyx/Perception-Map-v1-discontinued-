# Perception Map — Version 1 (Discontinued)

This was my first attempt at making a tool for mapping perception.
V1 helped me figure out what the project actually *was*, but the structure didn’t hold up, so I’m documenting it here before moving on to V2.

---

## 🎯 What V1 Tried to Do

The idea:

When you notice a perception happening — a reaction, a thought, a shift — you could break it down into three categories:

* **Private** — internal sensations, emotions
* **Public** — behaviors, interactions
* **Abstract** — interpretations, frameworks, concepts

The UI was a big canvas with three circles.
You dragged nodes into whichever circle fit, and connected them if they related.

It worked… kind of. But the structure ended up being too rigid for how perception actually flows.

---

## 🧩 What Nodes Contained

Each node stored:

* plain text (the content)
* a domain (based on circle placement)
* an optional lens (e.g., “psychological,” “relational”)
* an optional interpretation or reflection

Simple, but very manual.

---

## 🛑 Why I Ultimately Stopped Working on V1

### 1. The spatial layout became confusing

Perception isn’t literally spatial, but the UI forced it to be.

### 2. It took too much mental effort

You had to think about *how* to map before mapping anything.

### 3. It pushed interpretation too early

Some perceptions just need to be noticed — not analyzed right away.

### 4. No way to see patterns across multiple moments

Everything stayed inside one canvas. No “bigger picture.”

### 5. Architecture couldn’t scale

One playground = one moment, with no system for organizing or saving instances.

All of that led to starting V2 from scratch instead of patching V1.

---

## 🎥 Video Overview (Placeholder)

> **[Add Video Here]**
> I’ll include a walkthrough explaining what worked, what didn’t, and why I rebuilt everything.

---

## 🔍 What I Learned (and What Shaped V2)

* Domains should be tags, not physical zones.
* Not every node needs a lens or interpretation.
* The UI should *never* pressure insight.
* Insights come from linking across instances, not over-processing one.
* Flexibility beats structure every time.

---

## 📦 Project Status

* **V1:** Archived — used for reference only
* **V2:** Being redesigned from the ground up
* **This repo:** Documentation + starter scaffold

---

# 🧪 Perception Map — Starter Scaffold

This repo includes a minimal setup so the playground can run.

---

## 🛠 How to Run

1. `npm install`
2. `npm run dev`

Tech stack:

* ⚡ **Vite**
* ⚛️ **React**
* 🎨 **Tailwind**
* 🧭 **React Flow**
* 💾 **Dexie** (local IndexedDB)

---

## ✏️ Notes

This starter is intentionally barebones.
You can expand `CanvasView` however you want:

* add lens visuals
* add domain overlays
* build link/connection logic
* create a proper node editing panel
* experiment with UI layouts

It’s just the starting point — not the full tool.
