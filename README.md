# Universe Database 🌌

A relational database project built with PostgreSQL as part of the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-database/).

## 📋 About

This project models a universe with tables representing galaxies, stars, planets, moons, and comets, with proper relationships between them.

## 🗄️ Tables

- **galaxy** — 6 galaxies with descriptions and properties
- **star** — 6 stars referencing their galaxies
- **planet** — 12 planets referencing their stars
- **moon** — 20 moons referencing their planets
- **comet** — 3 comets referencing their galaxies

## 🛠️ Technologies

- PostgreSQL
- SQL (DDL & DML)

## 📌 Concepts Applied

- Primary and foreign keys
- Auto-incrementing IDs
- Data types: INT, NUMERIC, TEXT, BOOLEAN, VARCHAR
- Constraints: NOT NULL, UNIQUE
