# Long-Horizon Symbolic Planning for IKEA Furniture Assembly

This project explores symbolic task planning for IKEA furniture assembly using scene graphs, component metadata, and predefined motion primitives.

---

## 🛠️ Project Overview

We use scene graphs to represent subassemblies, with attachment edges derived from VLM-inferred component relationships (e.g., screws, brackets). These are used to define symbolic goals in a planning domain.

- Scene graphs are built from IKEA manuals
- Relationships like `attached_to` or `passes_through` are inferred
- Motion primitives (e.g., `pick`, `insert`, `screw_by_hand`) are defined in PDDL
- We use a symbolic planner to generate valid action sequences

---

## 🧩 Key Features

- 🔍 VLM-based metadata extraction (e.g., screw types, usage)
- 🧠 Scene graph construction for each assembly step
- 🏗️ PDDL domain and problem generation
- 🤖 Planning using off-the-shelf planners (e.g., Fast Downward)

---

## 🖼️ Example Subassembly Scene Graph


---

## 📝 Current Progress

- [x] Manual2Skill Integration
- [x] Scene Graph Generation
- [x] Component Metadata Inference
- [x] Attachment Edge Extraction
- [x] PDDL domain/problem generation
- [ ] Plan execution with simulated robot

---

## 📂 Project Structure

