---
layout: default
title: Databases
---

# Database Enhancement

## Artifact

MisManaged

---

## Overview

Revisiting MisManaged for a second enhancement allowed me to focus on an area of software development that often goes unnoticed by end users but is essential to every application: the database. While users typically interact with buttons and screens, every action depends on reliable data storage behind the scenes. 

During this enhancement, I expanded the SQLite database by introducing additional inventory fields, updating database queries, and improving how information was stored and retrieved throughout the application. These changes strengthened both the functionality of the application and my understanding of how thoughtful database design supports reliable software.

---

## Enhancement Narrative

Overview

The artifact selected for the database category is my MisManaged inventory management application from CS-360, Mobile Architecture and Programming. The application allows users to create accounts, manage inventory items, and receive inventory related notifications. I originally created the project in 2025 and am revisiting it for two of the three enhancements for this capstone course.

Justification

I selected this artifact because it provided an opportunity to expand the application's database design and improve how inventory information is stored and retrieved. The added bonus of working on something I’m genuinely proud of is nice. The original version of the application stored inventory quantities and minimum inventory thresholds but did not provide a way to organize inventory items into categories. For this enhancement, I modified the database schema by adding a category field to the inventory table. I updated the database contract, table creation logic, CRUD operations, and data model to support the new field. I also implemented category based queries that allow users to retrieve and filter inventory records based on a selected category. To support these changes for the user, I updated the user interface to allow category selection when creating items and category filtering when viewing inventory. When adding a new item, you use the left category spinner to assign that item’s category, and when searching for specific items within categories, you filter with the right spinner.

Course Outcomes

This enhancement primarily supports the outcome of demonstrating the ability to use well founded techniques, and tools in computing practices to implement computer solutions. By modifying the database schema and creating category based retrieval methods, I improved both the functionality and usability of the application.

Reflection

This enhancement reinforced the importance of database design in application development. A relatively small change to the database structure required updates throughout the whole application, including the schema, data model, queries, and UI. One challenge was ensuring that all database operations continued to function correctly after adding the new category field, which involved more java than I first assumed. Overall, the enhancement helped me better understand how database design decisions affect the overall functionality and maintainability of an application.

## Downloads

###  Original Artifact

[Download Original MisManaged](./MisManaged.zip)

###  Enhanced Artifact

[Download Enhanced Artifact](./Enhancement%20Three%20MisManagedJR%20CS%20499.zip)

###  Enhancement Narrative

[Read Enhancement Narrative](./CS%20499%20Enhancement%20Three%20Narrative.docx)

---

## Continue Exploring

 [Algorithms & Data Structures](algorithms.md)

 [Home](index.md)
