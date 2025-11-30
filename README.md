# **Context-Free Grammar Based Key Generator (TOA Project)**

This project demonstrates how **Context-Free Grammars (CFGs)** can be used to generate pseudo-random keys for lightweight encryption. It also includes a simple web interface and a Jupyter Notebook explaining the grammar, the algorithm, and experimental outputs.

---

## **📌 Project Contents**

### **1. Jupyter Notebook (`Automata_Project.ipynb`)**

Includes:

* Explanation of CFG design
* Key generation process
* Step-by-step outputs with short explanations
* Additional experimental results
* Small encryption demonstration using generated keys

### **2. Web Demo (`website.html`)**

A simple webpage that:

* Generates pseudo-random keys using the defined grammar
* Displays rule expansions
* Shows a diagram of the grammar
* Includes short explanations for each output step

---

## **🧩 Concept Summary**

The system uses a custom grammar:

* **Non-terminals:** S, A, B
* **Terminals:** symbols (letters/digits)
* **Productions:**

  * S → AB
  * A → aA | bA | c
  * B → xB | yB | z

By recursively expanding non-terminals, the system produces a structured but unpredictable key.

The generated key is then used to perform:

* Simple XOR-based encryption (Notebook demonstration only)

---

## **🚀 How to Run**

### **Run the Notebook**

Open `Automata_Project.ipynb` in:

* Jupyter Lab
* Google Colab
* VS Code (Jupyter extension)

### **Run the Web Demo**

Just open the file:

```
website.html
```

in any browser.

---

## **📘 Learning Outcome**

This project demonstrates:

* Applications of **formal languages** in cybersecurity
* How CFGs can generate structured randomness
* Basic integration of automata theory with encryption principles
