# **NPC & Crew Member System**

_This file tracks development of recruitable NPCs, crew roles, and task systems._

---

## **Base NPC Setup**
- [ ] Create `NPCBase.gd` with common stats (name, role, level)
- [ ] Create base NPC scene with idle/walk animations
- [ ] Add proximity interaction trigger

---

## **Recruitment Mechanics**
- [ ] `CrewData.gd` - autoload crew storage
- [ ] Add join conditions (quests, bribes, charm stat)
- [ ] Add "Join My Crew" dialogue line
- [ ] Notification on join + particle/sound FX

---

## **Crew Roles & Progression**
- [ ] Define roles: Fighter, Crafter, Farmer, Guard, Healer
- [ ] Role-based stats and level-up logic
- [ ] XP gain per task/battle
- [ ] Traits (e.g. “Fast Learner”, “Slacker”)

---

## **Crew Management Menu**
- [ ] Crew List UI
- [ ] View Stats / Level / Traits
- [ ] Assign Role dropdown
- [ ] Assign Gear / Loadout
- [ ] Combat toggle (Join Fight / Stay at Base)

---

## **Crew Behavior Systems**
### **Combat Crew**
- [ ] Pathfinding to follow player
- [ ] Attack nearby enemies
- [ ] Use skills (cooldowns, distance checks)
- [ ] Retreat when low HP

### **Passive Crew**
- [ ] Task zones (farm, craft, guard post)
- [ ] Timed rewards based on role efficiency
- [ ] Add recovery timer if overworked

---

## **Equipment & Bonding**
- [ ] Equip crew with weapons, armor, accessories
- [ ] Bonus stats based on gear
- [ ] Friendship system (dialogue, quests)
- [ ] Loyalty system (can leave/betray if neglected)

---

## **Saving & Persistence**
- [ ] Save crew data: name, level, traits, gear, location
- [ ] Load crew on game start
- [ ] Optional: JSON snapshot for backups

---

## **Future Ideas**
- [ ] Unique recruit-only NPCs
- [ ] Crew quarters with upgrades
- [ ] Crew vs. Crew PvP battles
- [ ] Morale system + interactions between crew