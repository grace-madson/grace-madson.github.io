---
layout: essay
type: essay
title: "What does the weather have to do with design patterns?"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: false
labels:
  - Design Patterns
---

<img class="img-fluid" src="../img/design-patterns.jpg">

## Intro
Building a building requires careful planning and execution. Imagine starting construction without laying a solid foundation first. It would be like constructing walls without ensuring they fit the blueprint's specifications. Just as blueprints are essential for efficient building, design patterns are crucial when developing apps. They offer standardized solutions to common problems, ensuring the app's robustness.

## The Journey of App Dev
In our journey developing Manoa Mentoring, we stumbled upon the implementation of design patterns without even realizing it! For instance, when we use "propType," we're actually employing the prototype design pattern. It's like using a cookie cutter to make multiple cookies from a single recipe. Similarly, our use of the observer design pattern becomes evident through the publish and subscribe function, akin to a weather reporter updating people with the latest news.

Reactive data, another pattern we've integrated, dynamically adjusts the app when new data, like a user registering, is added. Think of it as a train station announcing delays, ensuring passengers stay informed. Reactive programming allows for seamless updates, enhancing user experience.

Furthermore, our adoption of the MVC (Model-View-Controller) pattern ensures clear separation of concerns. The Model represents data and business logic, the View handles user interface elements, and the Controller acts as an intermediary, facilitating communication between the Model and the View. This separation enhances maintainability and scalability, crucial for a growing application like Manoa Mentoring.

Lastly, the singleton pattern, exemplified by its global recognition, is akin to having a passport facilitating travel worldwide. In our app, singletons ensure there's only one instance of certain objects, maintaining consistency and avoiding resource wastage.

## Conclusion
While some may find design patterns confusing, they often manifest naturally during software development. Although there are numerous design patterns in Manoa Mentoring, listing them all would be tedious. Concepts like reactive data and MVC simply make sense in a user-friendly web application, where non-technical users interact with a straightforward UI.

In essence, design patterns are the backbone of efficient and maintainable software development, seamlessly woven into the fabric of our app's architecture, ensuring a smooth user experience and paving the way for future enhancements and scalability.
