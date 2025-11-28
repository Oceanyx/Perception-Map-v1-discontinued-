# Perception Map — Version 1 (Discontinued)

*A personal cognitive-mapping tool exploring how we perceive, interpret, and experience internal events.*

---

## 📌 Summary

Perception Map V1 was the first attempt to create a structured, visual interface for breaking down a user’s perception into three distinct domains:

* **Private** — Inner sensations, feelings, intuitions
* **Public** — Outward expressions, interactions, social dynamics
* **Abstract** — Conceptual frameworks influencing interpretation

This early version used a spatial “three-circle playground” where each domain had its own area. Users created nodes inside these circles to document perception elements and draw connections between them.

V1 established core concepts but revealed architectural and cognitive limitations that led to its discontinuation.

---

## 🎯 Purpose of V1

The intention behind V1 was:

> To help users visually dissect a moment of perception by placing internal and external elements into a map of three domains.

It aimed to make invisible mental processes *visible, manageable, and reflectable*.

---

## 🛠️ Key Features in V1

### ✔ Domain-Based Playground

A canvas divided into three circles representing Private, Public, and Abstract.

### ✔ Node Creation

Each node included:

* Text body
* Domain tag (based on placement)
* Optional lens (interpretive framework)
* Optional interpretation

### ✔ Visual Connections

Users could draw links between nodes to illustrate relationships or influences.

### ✔ Minimal Node Detail Panel

Selecting a node opened a side panel for editing text, tags, interpretations, and metadata.

---

## 🚧 Why Version 1 Was Discontinued

### 1. High Cognitive Load

The system required too much mental effort: choosing domains, interpreting nodes, manually linking elements.

### 2. Rigid Spatial Domains

Tying domains to physical locations made complex or overlapping experiences difficult to map.

### 3. Forced Interpretation

The UI accidentally pressured users to interpret everything, even when they had no clarity yet.

### 4. Missing Meta-Pattern Structure

There was no way to represent cross-instance insights, recurring themes, or high-level patterns.

### 5. Not Scalable

The architecture didn’t support multiple perception instances, persistent storage, syncing, or larger cognitive maps.

---

## 📼 Placeholder for V1 Demo Video

> **[INSERT VIDEO HERE]**
> *A walkthrough describing V1, its goals, design, and why it was ultimately restructured.*

---

## 📚 Lessons from V1

V1 clarified several principles that led to the redesigned V2 architecture:

* Domains should be **attributes**, not **locations**.
* Interpretation should be **optional**.
* Mapping must support **real-time experience**, not abstract diagramming.
* Meta-patterns must exist **across** nodes and moments.
* The tool needs a more **fluid**, **user-centered**, and **scalable** system.

---

## 🚀 Status

* **Version:** V1 (Discontinued)
* **Purpose:** Documentation / Portfolio
* **Successor:** *Perception Map V2* (In development)

---

# Perception Map — Starter

This repository also includes the **starter scaffold** used to run the Perception Map Playground during development.

## 🔧 How to Run

1. Install dependencies:

   ```bash
   npm install
   ```
2. Run dev server:

   ```bash
   npm run dev
   ```

## 🧰 Tech Stack

This project uses:

* **Vite**
* **React**
* **Tailwind CSS**
* **React Flow** (for node-based visual mapping)
* **Dexie** (IndexedDB wrapper for local storage)

## 📁 Project Notes

The starter includes minimal files required to get the playground working.
You can extend `CanvasView` to add:

* Lens styling
* Domain overlays
* Visual connection logic
* Node detail enhancements
* Pattern-level mappings
