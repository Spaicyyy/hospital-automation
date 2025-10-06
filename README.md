🏥 Hospital Automation Database Design

This repository contains the ER diagram and relational schema design for a hospital automation prototype.

## 📘 Entities
- *Doctor*
- *Patient*
- *Polyclinic*
- *Laboratory*
- *Test (Tahlil)*
- *Nurse*
- *Service*

## 🔗 Relationships
- Polyclinic → Doctor (1:N)
- Patient ↔ Polyclinic (N:M)
- Doctor ↔ Test (N:M)
- Test → Laboratory (1:N)
- Nurse → Service (1:N)
- Service → Polyclinic (1:N)

## 📁 Files
- hospital.drawio — ER Diagram file
- hospital.mwb — MySQL Workbench model
- hospital.sql — SQL table definitions

---

👤 Created by: Avaz Gurbanli
📅 Date: October 2025
