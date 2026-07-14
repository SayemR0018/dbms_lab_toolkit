# DBMS Interactive Laboratory Toolkit Matrix
An interactive, high-performance, single-file laboratory development application designed for database management systems engineering. This toolkit combines real-world schema configurations, relational querying frameworks, and an interactive ER drawing environment into a single unified workspace.

🌐 **Live Production Deployment:** [https://SayemR0018.github.io/dbms_lab_toolkit/](https://SayemR0018.github.io/dbms_lab_toolkit/)

---

## 🎓 Academic Context
This repository houses the compiled interactive laboratory resources, structural datasets, DDL/DML templates, and procedural implementation blocks developed for:
*   **Course:** CSE 3522 / CSI 222 : Database Management Systems Laboratory
*   **Institution:** United International University (UIU)

### 📜 Original Content Attribution
The baseline educational courseware curriculum, procedural examples, relational datasets, and system tutorials compiled within this application are credited to:
*   **Original Creator:** **Johirul Islam**
*   **Role:** Part-Time Faculty, Department of Computer Science & Engineering
*   **Institution:** United International University (UIU)

---

## ⚡ Application Architecture & Features

### 1. Minimalistic Header Terminal
*   **Tool-Panel Tabs:** Seamlessly toggle view states between the comprehensive **Tutorial Hub** and the graphic **ER Diagram Learner** canvas.
*   **Theme Engine:** Deep dark cyberpunk and light mode styling configurations managed via responsive CSS variables.

### 2. Fully Insulated Multi-Segment Tutorial Hub
The tutorial manual isolates four core development modules into separate view containers using dedicated JavaScript view-swapping logic to prevent DOM nesting or loading bugs:
*   **Segment 01: Web & Database Connectivity** — Cross-platform configuration guides mapping XAMPP Apache settings, local ports, PHP MySQLi (Procedural & OOP), PDO strings, SQL Server ODBC installations, and C# .NET C# `SqlConnection` stacks.
*   **Segment 02: Views, Functions & Procedures** — Virtual view layers, built-in system lookup functions, scalar user-defined functions (UDF), table-valued function patterns, precompiled Stored Procedures with input/output parameters, and structured transaction error handling (`TRY/CATCH` & `DECLARE HANDLER`).
*   **Segment 03: Core Database Constraints** Side-by-side DDL panels comparing Primary Keys (`IDENTITY` vs `AUTO_INCREMENT`), `ON DELETE CASCADE` constraints, uniqueness behaviors, composite keys, `NOT NULL` configurations, default filters, and database validation bounds alongside explicit rule violation queries.
*   **Segment 04: SQL JOIN & Query Tutorial** Deep-dive reference tracking projections, WHERE comparison operators, wildcard string pattern matching (`LIKE`), `BETWEEN` ranges, `GROUP BY` aggregates, `HAVING` filters, `NULL` safety routines, mathematical joins (INNER, LEFT, RIGHT, CROSS, and FULL OUTER join fallbacks), `CASE` expressions, and subqueries.

### 3. Graphic ER Diagram Learner Tool
A visual modeling suite inside the browser allowing users to dynamically design database constraints using Chen Notations:
*   **Interactive Controls:** Spawn Strong Entities, Weak Entities, Simple Attributes, Key Attributes, Derived Attributes, Multivalued Attributes, Partial Keys, and Relationships onto an active SVG background grid.
*   **Deterministic Logic Engine:** Translates graphic component positions and linkage fields automatically into a clear, live text description parsing entity assignments, dependency definitions, and participation rules.

---

## 📁 Repository Structure
```text
DBMS_WEBSITE/
│
├── index.html        # Centralized application codebase (HTML5, CSS3, ES6 JavaScript)
├── assests/          # Original laboratory reference manual backups
│   ├── Web & Database Connectivity.html
│   ├── DBMS Lab-3522 _ Database Tutorial.html
│   ├── SQL Constraints Tutorial — MS SQL Server vs MySQL.html
│   └── SQL JOIN & Query Tutorial — SQL Server & MySQL.html
└── README.md         # Deployment and academic documentation
```

---

## 👤 Developer Profile
<p align="left">
  <strong>Engineer:</strong> Sayem Rahman<br>
  <strong>ID:</strong> 0112330018<br>
  <strong>Program:</strong> BS in Computer Science and Engineering (BSCse)<br>
  <strong>Institution:</strong> United International University (UIU)
</p>
