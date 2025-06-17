#RO

# 🚆 Proiect Bază de Date – Managementul Transportului Feroviar de Pasageri

Acest proiect constă într-o bază de date relațională realizată în Oracle SQL, destinată gestionării unui sistem de transport feroviar pentru pasageri. Sunt gestionate informații despre trenuri, vagoane, pasageri, rute, bilete și angajați.

Baza de date poate fi utilizată de companii feroviare pentru a urmări rutele disponibile, biletele vândute, angajații activi, stațiile intermediare și date statistice despre capacități, reduceri și bonusuri.

> ⚠️ **Toate datele folosite în acest proiect sunt fictive. Orice asemănare cu persoane reale este pur întâmplătoare.**

---

## 📦 Fișiere incluse
- `script.sql` – Crearea și popularea tuturor tabelelor
- `SCRIPT_proiect_BD.txt` – Script extins cu constrângeri
- `database_schema.png` – Schema bazei de date
- `ProjectDocumentation.pdf` Documentație completă
- `CERINTE_PROIECT.doc` – Cerințele inițiale

---

## 🧩 Tabele și relații
- `RUTE`, `TRENURI`, `VAGOANE`
- `PASAGERI`, `BILETE`, `PERSONAL_TREN`
- `STATII`, `REGIONALA`, `STATII_RUTE` (relații N:M)
- Chei primare, chei externe, constrângeri `CHECK` și `NOT NULL`

---

## 🛠 Funcționalități implementate
- JOIN, subcereri, funcții, interogări de agregare
- Triggers (validare și audit)
- Views, secvențe, sinonime, indici
- Proceduri și funcții PL/SQL
- Pachete și cursori pentru afisare date dinamice

---

## 👨‍🎓 Autor
**Georgescu Ionuț-Bogdan**  
Facultatea de Cibernetică, Statistică și Informatică Economică  
Academia de Studii Economice (ASE) București  

#EN
# 🚆 Oracle SQL Project – Railway Passenger Management System

This project is a relational database system designed to manage passenger transportation via railway. Built with Oracle SQL, it handles data about trains, routes, tickets, passengers, wagons, stations, and staff.

It can be used by railway companies to monitor available routes, ticket sales, train staff, station itineraries, and statistical data regarding capacities, discounts, and bonuses.

> ⚠️ **All data used in this project are fictional and created for educational purposes only. Any resemblance to real individuals is purely coincidental.**

---

## 📦 Included Files
- `script.sql` – Table creation and data insertion
- `SCRIPT_proiect_BD.txt` – Extended script with constraints
- `INTEROGARI_PROIECT_BD.txt` – Complex SQL and PL/SQL queries
- `database_schema.png` – Entity-Relationship schema
- `ProjectDocumentation.pdf` and `proiect_sgbd.docx` – Full documentation
- `README_EN.docx` – English README version
- `CERINTE_PROIECT.doc` – Initial requirements (in Romanian)

---

## 🧩 Main Tables and Relationships
- `RUTE`, `TRENURI`, `VAGOANE`
- `PASAGERI`, `BILETE`, `PERSONAL_TREN`
- `STATII`, `REGIONALA`, `STATII_RUTE` (junction table)
- Primary keys, foreign keys, CHECK and NOT NULL constraints

---

## 🛠 Features Implemented
- JOINs, subqueries, functions, aggregation queries
- Triggers for validation and audit
- Views, sequences, synonyms, indexes
- PL/SQL procedures and functions
- Package definitions and dynamic cursors

---

## 👨‍🎓 Author
**Georgescu Ionuț-Bogdan**  
Faculty of Cybernetics, Statistics and Economic Informatics  
Bucharest University of Economic Studies

