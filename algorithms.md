---
layout: default
title: Algorithms & Data Structures
---

# Algorithms & Data Structures Enhancement

## Artifact

MisManaged

---

## Overview

Rather than building a new application from scratch, I chose to revisit MisManaged because it gave me the opportunity to improve an existing solution using the knowledge I gained throughout the Computer Science program. The application manages inventory information for small businesses, but the real focus of this enhancement was improving the way the application organized and processed data. By simplifying algorithms, improving inventory management logic, and introducing more appropriate data structures, I was able to make the application more efficient while creating code that is easier to understand and maintain.

---

## Enhancement Narrative

Overview

I chose my MisManaged inventory management application from CS-360, Mobile Architecture and Programming. The app lets users manage inventory items, update quantities, and receive notifications when inventory levels become low. The project was originally created in 2025 and hasn’t been interacted with since.

Justification

I selected this artifact because it provided a good opportunity to demonstrate algorithmic thinking within a practical application. The original version stored and displayed inventory data, it did not identify which items required immediate attention without sending the user a notification.

For this enhancement, I implemented a low inventory detection feature that compares an item's current quantity against a minimum inventory threshold. The application now filters low stock items, prioritizes them by quantity, and displays warnings when inventory levels become too low. I also expanded the InventoryItem data structure to include minimum quantity values and updated the user interface to display low-stock information, rather than solely relying on the notification itself.

Implementing this somewhat small but mighty addition has shown myself that I’m actually capable of handling a real programming task through and through while also applying algorithms, data structures, and data retrieval techniques to improve the functionality and usefulness of an application.

Course Outcomes

This enhancement primarily supports the outcome of designing and evaluating computing solutions using algorithmic principles and computer science practices. By implementing filtering, prioritization, and threshold-based inventory monitoring, I was able to improve the application's ability to process and present meaningful information.

Reflection

This enhancement helped me better understand how algorithms can be used to improve the overall value of an application rather than simply store data. One challenge was updating multiple parts of the application and remembering what went where, including the database, data model, and user interface, while ensuring everything continued to work correctly.

## Downloads

###  Original Artifact

[Download Original MisManaged](./MisManaged.zip)

###  Enhanced Artifact

[Download Enhanced Artifact](./Enhancement%20Two%20mismanaged_jr%20CS499.zip)

###  Enhancement Narrative

[Read Enhancement Narrative](./CS%20499%20Enhancement%20Two%20Narrative.docx)

---

## Continue Exploring

 [Software Engineering](software-engineering.md)

 [Database Enhancement](databases.md)

 [Home](index.md)
