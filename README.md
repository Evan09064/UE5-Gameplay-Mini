# UE5 Gameplay Mini — In progress (C++ + Blueprints)

**Status:** WIP (planning + scaffolding).  
**Goal:** A tiny third-person showcase focused on **movement feel** and a **simple AI**:  
- Dash + double-jump (tuned CharacterMovement).  
- Interact (pickup).  
- Guard AI with **Behavior Tree + NavMesh** (patrol → chase).  
- BP-exposed tunables for designers; core logic in C++.

## Tech
Unreal Engine 5.x · C++ · Blueprints · NavMesh/AIController · Behavior Tree/Blackboard

## Where to look (to be created)
- `Source/<ProjectName>/Character/` — movement & ability logic (C++).  
- `Source/<ProjectName>/AI/` — AIController + services/tasks (C++).  
- `Content/AI/` — BT/BB assets (Blueprint).  

## Roadmap
- [ ] Project scaffold (UE 5.x Third Person)  
- [ ] Dash (BP → migrate to C++)  
- [ ] Double-jump & coyote time  
- [ ] Interact (pickup)  
- [ ] AI: patrol → investigate(last seen) → chase (BT + BB)  
- [ ] Perf pass + small 60–90s clip

## How to run (TBD)
UE **5.x**. Open `<ProjectName>.uproject` → Play. (Will add exact version + steps after initial scaffold.)

## Devlog
**Day 0 — Planning:** repo created, scope locked (dash/double-jump/interact + BT patrol→chase), folders scaffolded.
