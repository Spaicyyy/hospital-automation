🏥 Hospital Automation Database Design

## 📘 Entities
- *Doktor*
- *Hasta*
- *Poliklinik*
- *Labaratuvar*
- *Tahlil*
- *Hemsire*
- *Servis*

## 🔗 Relationships
- Poliklinik → Doktor (1:N)
- Hasta ↔ Poliklinik (N:M)
- Doktor ↔ Tahlil (N:M)
- Tahlil → Labaratuvar (1:N)
- Hemsire → Servis (1:N)
- Servis → Poliklinik (1:N)
  
---

👤 Created by: Avaz Gurbanli
📅 Date: October 2025
