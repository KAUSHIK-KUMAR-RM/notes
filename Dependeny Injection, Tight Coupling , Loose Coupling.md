Here’s an explanation in simple terms:

### **1. Dependency Injection**
- **What it is:** A design pattern where an object (or class) gets the things it needs (its dependencies) from an external source, rather than creating them itself.
- **Example:** Imagine a coffee machine that needs water. Instead of the coffee machine fetching water on its own, someone pours water into it. The coffee machine just focuses on making coffee.
- **Why it’s useful:** It makes the code flexible and easier to test because you can easily swap out parts (like providing a different kind of water or container).

---

### **2. Tight Coupling**
- **What it is:** When two parts of a system are so dependent on each other that a change in one part requires changes in the other.
- **Example:** If your coffee machine not only makes coffee but also knows how to fetch its own water from a specific tap, it’s tightly coupled. If the tap changes, the coffee machine breaks.
- **Why it’s bad:** It makes the system rigid and hard to modify because everything is interconnected.

---

### **3. Loose Coupling**
- **What it is:** When two parts of a system depend on each other as little as possible, often interacting through abstractions or interfaces.
- **Example:** If your coffee machine just says, "I need water," and doesn’t care where the water comes from, it’s loosely coupled. You can connect it to a bottle, a tank, or even a direct water supply without changing the machine itself.
- **Why it’s good:** It makes the system flexible, easier to maintain, and adaptable to changes.

---

### **How They Work Together**
- Dependency injection is a tool to **achieve loose coupling**. 
- Without dependency injection, tight coupling often occurs because classes create and manage their own dependencies directly. Dependency injection breaks this by letting an external system provide the dependencies.