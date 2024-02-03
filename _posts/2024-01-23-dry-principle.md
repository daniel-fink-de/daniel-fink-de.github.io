---
title: "Misinterpretation of the DRY principle"
date: 2024-01-23
permalink: /posts/2024/01/misinterpretation-dry-principle/
tags:
  - software-patterns
---

Ever heard about the "Don't repeat yourself" (DRY) principle? 👂

According to [Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself), this is “a principle of software development aimed at reducing repetition of information which is likely to change.“ 🔄

I fully commit myself to this pattern and see its advantages, such as easier maintenance and less code (and thus fewer tests to write) 👨‍💻 Yet, I think that this principle is often misinterpreted as “Don’t have code duplications” 🤔

Why is this distinction important 🤨 [Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) formulates it pretty well: “When the DRY principle is applied successfully, a modification of any single element of a system does not require a change in other logically unrelated elements.“ 🕵‍♀️

The key point here is “logically unrelated elements.” If we focus only on code duplications, we are likely to couple logically unrelated elements together, leading to unwanted side effects. In the end, it does require a change in logically unrelated elements. A simple example would be a helper class used by two separate modules. The helper class itself lives in a shared module. This helper class may do the very same job for the two modules now, but they evolve over time, such that this may not be the case in the future 💥

Additionally, when these principles are taught in school together with OOP, natural choices for reducing code for juniors are abstractions and inheritances. However, this introduces additional complexity, which directly contradicts another famous principle, the “Keep it simple, stupid!” ([KISS](https://en.wikipedia.org/wiki/KISS_principle)) principle 😅

➡ My conclusion is that when I am repeating myself, I first make sure that the repetitions lay in the same module before I start refactoring it 🛠️