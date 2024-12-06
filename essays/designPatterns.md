---
layout: essay
type: essay
title: "My Journey Building Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-12-5
published: true
labels:
  - Engineering
  - Design
  - Patterns
---



![designpatterns](https://github.com/user-attachments/assets/9c7fd4b5-5455-462d-80d4-fdb17e093e67)




# Building the House: The Story of Design Patterns

Imagine you’re tasked with building a mansion. Not just any mansion, but one that must stand strong against storms, welcome hundreds of guests, and feature secret passages, hidden libraries, and sprawling gardens. You have a team of builders, and each brings their own expertise. However, without a shared blueprint—a plan everyone understands—the mansion risks becoming a chaotic maze of disconnected rooms and weak foundations. This is where design patterns come into play.

**Design patterns are the blueprints of software development.** They are tried-and-true solutions to common problems, much like architectural designs for recurring challenges in construction. Just as a vaulted ceiling provides grandeur and better acoustics, or flying buttresses support massive structures, design patterns offer established strategies for organizing and structuring code. They don’t dictate *what* to build but rather *how* to approach the build in a way that is elegant, scalable, and maintainable.

## The Blueprint in Action: Building My Own House

In my software development journey, I’ve applied object-oriented programming (OOP) and design patterns to create effective and user-friendly solutions. For example, in an earlier project, I built a program that could look up a person’s name and return their phone number and address. To make the program easier to use and less complex, I implemented the **Facade pattern**. Much like a front desk in a building, the Facade pattern handled all the complicated details behind the scenes, allowing users to interact with a simple and intuitive interface without worrying about how the information was retrieved.

To efficiently navigate through lists of data, such as names and addresses, I used the **Iterator pattern**. This pattern allowed me to loop through the data without exposing how it was stored, making the code easier to read and maintain. It also provided flexibility, ensuring the program could handle changes, such as switching from a list to a database, with minimal effort.

In one of my recent projects, **HouseFinders**, I used OOP and design patterns to create a platform that connects users to housing options. To manage user-submitted information, I applied the **Proxy pattern**, which acted as a gatekeeper between the user and the housing database. Whenever users submitted data—such as property details or search criteria—the Proxy validated and cleaned the input before saving it to the database. For instance, if a user submitted incomplete information, like missing an address or price, the Proxy intercepted the submission, prompted the user to correct it, and prevented invalid data from entering the system. This approach kept the database secure and ensured reliable information for all users.

Using these patterns—Facade, Iterator, and Proxy—helped me build programs that are not only powerful but also easy to maintain. The Facade pattern simplified user interactions, the Iterator pattern streamlined data handling, and the Proxy pattern safeguarded the integrity of the database. These experiences have shown me how design patterns can solve specific challenges while making code simpler, more organized, and more effective.

## Why It Matters

What makes design patterns invaluable isn’t just their ability to solve problems but their capacity to provide a shared language. When discussing software architecture, I can say “I used a Factory Method here” or “This calls for a Strategy pattern,” and immediately, my peers understand the intent. 

Through design patterns, I’ve learned to approach problems with a builder’s mindset. I see the house before it’s built, recognizing that while the details may differ, the overall premise of construction remain the same.

## Closing the Door

So, what are design patterns? They’re the timeless blueprints for software development, offering different solutions to recurring problems. And how have I used them? Like an architect designing a house, I’ve used these patterns to build scalable, maintainable, and a variety of systems. Each project is a new structure, but the principles remain—solid foundations, thoughtful designs.

---

## Design Patterns Overview

Design patterns are established solutions to common problems in software design, serving as templates that can be applied in various situations to improve code readability, reusability, and maintainability. They are categorized into three main types:

1. **Creational Patterns**: Focus on object creation mechanisms, aiming to create objects in a manner suitable to the situation. Examples include the **Singleton** and **Factory Method** patterns.
2. **Structural Patterns**: Deal with object composition, ensuring that if one part changes, the entire structure doesn't need to. Examples include the **Adapter** and **Decorator** patterns.
3. **Behavioral Patterns**: Concerned with object interaction and responsibility delegation. Examples include the **Observer** and **Strategy** patterns.

 ---
 AI Use: I used AI to help me rewrite my technical essay to grammatically fix my work.







