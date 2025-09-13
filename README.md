# Angular Task Management Demo App(services and DI)
This is a simple demo application built with Angular to illustrate the concepts of services, custom service tokens, dependency injection, and value injection.

---

## Features
Task Management: Add tasks to a to-do list.

Status Tracking: Each task has a status (e.g., open, in-progress, done).

Filter Tasks: View tasks by their status (all, open, in-progress, done).

Manual Status Update: Change the status of any task directly from the list.

Reactive Updates: The UI updates automatically when tasks or statuses change.

---

## Core Angular Concepts Used
Services: All business logic for handling tasks (add, update, filter, etc.) is encapsulated in Angular services.

Custom Service Tokens: Demonstrates how to create and inject custom tokens for more flexible or testable service architecture.

Dependency Injection: Services and tokens are injected where needed using Angular’s DI system.

Injecting Services & Values: The app shows both how to inject complete services and how to inject simple values.

---

## Example Usage
Click Add Task to create a new to-do item.

Use the filter options (buttons or dropdown) to view tasks by their status.

Change the status of any task (for example, from "open" to "done") to track progress.

---

## Why This App?
This demo is designed for learners to understand how Angular handles:

Centralized logic with services.

Passing dependencies using DI (constructor or inject syntax).

Filtering and status management using reactive techniques and Angular best practices.
