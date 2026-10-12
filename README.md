# Confusing-Stack-and-Heap
## 🧠 Quick Memory Guide: When to Stack and When to Heap?

* **Heap Memory (`new` objects & instance fields):**
  * Whenever you use the `new` keyword (e.g., `new Student()`, `new Employee()`), the object is created on the **Heap**.
  * **Instance variables** (variables declared inside a class but outside methods) live inside their object on the **Heap**.
  * Heap objects stay alive until the Garbage Collector removes them.

* **Stack Memory (Method frames & local variables):**
  * **Local variables** (declared inside a method like `marks` or `bonus`) live on the **Stack**.
  * **Method execution frames** (keeping track of which method is running) live on the **Stack**.
  * Reference variables (like `student`, `emp`) also live on the **Stack**, but they point to the actual object residing on the **Heap**.
  * Stack data is automatically deleted the moment the method finishes executing.
