# Theory of Computer Science (TCS) – JFLAP Self-Learning Assignment

**Student Name:** Prathamesh Shelar  
**Roll No:** 65  
**Class / Division:** D12A  
**Batch:** C
**Subject:** Theory of Computer Science (TCS) (26CMPC51)  
**Department:** Department of Computer Engineering  
**Institution:** Vivekanand Education Society's Institute of Technology (VESIT)  
**Faculty In-Charge:** Mr. Sanjay Mirchandani  
**Academic Submission Date:** 14 November 2026 (14-11-2026)  

---

## 📌 Executive Summary

This repository contains the complete practical portfolio for the **30-Hour JFLAP Self-Learning Assignment** in Theory of Computer Science. All 15 practical modules have been designed, simulated, and formally verified across the Chomsky Hierarchy—spanning **Finite Automata, Transducers (Mealy & Moore), Context-Free Grammars & Pushdown Automata, Parsing Algorithms (CYK & LL(1)), and Single/Multi-Tape Turing Machines**.

Every single `.jff` file strictly adheres to standard JFLAP XML specifications, and all files follow the institutional naming convention:
`Roll_No._Name_Topic_DOP` $\implies$ `65_Prathamesh_Shelar_<Topic>_14-11-2026.jff`

---

## 📋 Master Practical Index & Verification Tracker

| No. | Directory | Topic / Concept Covered | Primary JFLAP File(s) | Machine / Formal Type | Verification Status |
|:---:|:---|:---|:---|:---:|:---:|
| **01** | [`01_DFA`](./01_DFA/) | Deterministic Finite Automata (Binary Divisible by 3) | [`65_Prathamesh_Shelar_DFA_14-11-2026.jff`](./01_DFA/65_Prathamesh_Shelar_DFA_14-11-2026.jff) | DFA | **Validated & Verified** |
| **02** | [`02_NFA`](./02_NFA/) | Non-Deterministic Finite Automata (Contains `101`) | [`65_Prathamesh_Shelar_NFA_14-11-2026.jff`](./02_NFA/65_Prathamesh_Shelar_NFA_14-11-2026.jff) | NFA | **Validated & Verified** |
| **03** | [`03_NFA_to_DFA`](./03_NFA_to_DFA/) | NFA to DFA Subset Construction (Ends in `ab`) | [`65_Prathamesh_Shelar_NFA_Source_14-11-2026.jff`](./03_NFA_to_DFA/65_Prathamesh_Shelar_NFA_Source_14-11-2026.jff), [`65_Prathamesh_Shelar_DFA_Converted_14-11-2026.jff`](./03_NFA_to_DFA/65_Prathamesh_Shelar_DFA_Converted_14-11-2026.jff) | FA Conversion | **Validated & Verified** |
| **04** | [`04_DFA_Minimization`](./04_DFA_Minimization/) | DFA Minimization using Equivalence Partitioning (Ends `01`) | [`65_Prathamesh_Shelar_DFA_Original_14-11-2026.jff`](./04_DFA_Minimization/65_Prathamesh_Shelar_DFA_Original_14-11-2026.jff), [`65_Prathamesh_Shelar_DFA_Minimized_14-11-2026.jff`](./04_DFA_Minimization/65_Prathamesh_Shelar_DFA_Minimized_14-11-2026.jff) | FA Minimization | **Validated & Verified** |
| **05** | [`05_RE_to_DFA`](./05_RE_to_DFA/) | Regular Expression to DFA Conversion (`(a+b)*abb`) | [`65_Prathamesh_Shelar_RE_14-11-2026.jff`](./05_RE_to_DFA/65_Prathamesh_Shelar_RE_14-11-2026.jff), [`65_Prathamesh_Shelar_DFA_from_RE_14-11-2026.jff`](./05_RE_to_DFA/65_Prathamesh_Shelar_DFA_from_RE_14-11-2026.jff) | RE / FA | **Validated & Verified** |
| **06** | [`06_DFA_to_Grammar`](./06_DFA_to_Grammar/) | DFA to Right-Linear Grammar Conversion (Starts 0, Ends 1) | [`65_Prathamesh_Shelar_DFA_Source_14-11-2026.jff`](./06_DFA_to_Grammar/65_Prathamesh_Shelar_DFA_Source_14-11-2026.jff), [`65_Prathamesh_Shelar_Grammar_Converted_14-11-2026.jff`](./06_DFA_to_Grammar/65_Prathamesh_Shelar_Grammar_Converted_14-11-2026.jff) | FA $\to$ Grammar | **Validated & Verified** |
| **07** | [`07_Mealy_Machine`](./07_Mealy_Machine/) | Mealy Machine (Sequence Detector for `101` with Overlap) | [`65_Prathamesh_Shelar_Mealy_14-11-2026.jff`](./07_Mealy_Machine/65_Prathamesh_Shelar_Mealy_14-11-2026.jff) | Mealy Transducer | **Validated & Verified** |
| **08** | [`08_Moore_Machine`](./08_Moore_Machine/) | Moore Machine (Binary Stream Residue Modulo 3 Evaluator) | [`65_Prathamesh_Shelar_Moore_14-11-2026.jff`](./08_Moore_Machine/65_Prathamesh_Shelar_Moore_14-11-2026.jff) | Moore Transducer | **Validated & Verified** |
| **09** | [`09_CFG`](./09_CFG/) | Context-Free Grammar ($L = \{ a^n b^{2n} \mid n \ge 1 \}$) | [`65_Prathamesh_Shelar_CFG_14-11-2026.jff`](./09_CFG/65_Prathamesh_Shelar_CFG_14-11-2026.jff) | Grammar (Type 2) | **Validated & Verified** |
| **10** | [`10_PDA`](./10_PDA/) | Pushdown Automata ($L = \{ w c w^R \mid w \in \{a,b\}^* \}$) | [`65_Prathamesh_Shelar_PDA_14-11-2026.jff`](./10_PDA/65_Prathamesh_Shelar_PDA_14-11-2026.jff) | DPDA | **Validated & Verified** |
| **11** | [`11_CNF_Conversion`](./11_CNF_Conversion/) | Chomsky Normal Form Conversion ($a^n b^n$) | [`65_Prathamesh_Shelar_CFG_Original_14-11-2026.jff`](./11_CNF_Conversion/65_Prathamesh_Shelar_CFG_Original_14-11-2026.jff), [`65_Prathamesh_Shelar_CNF_Converted_14-11-2026.jff`](./11_CNF_Conversion/65_Prathamesh_Shelar_CNF_Converted_14-11-2026.jff) | CNF Normalization | **Validated & Verified** |
| **12** | [`12_CYK_Parsing`](./12_CYK_Parsing/) | Cocke-Younger-Kasami (CYK) Dynamic Programming Parsing | [`65_Prathamesh_Shelar_CYK_14-11-2026.jff`](./12_CYK_Parsing/65_Prathamesh_Shelar_CYK_14-11-2026.jff) | CYK Parser | **Validated & Verified** |
| **13** | [`13_LL1_Parsing`](./13_LL1_Parsing/) | LL(1) Predictive Parsing for Arithmetic Expressions | [`65_Prathamesh_Shelar_LL1_Grammar_14-11-2026.jff`](./13_LL1_Parsing/65_Prathamesh_Shelar_LL1_Grammar_14-11-2026.jff) | LL(1) Parser | **Validated & Verified** |
| **14** | [`14_Single_Tape_TM`](./14_Single_Tape_TM/) | Single-Tape Turing Machine (Binary Incrementer $w + 1$) | [`65_Prathamesh_Shelar_Single_Tape_TM_14-11-2026.jff`](./14_Single_Tape_TM/65_Prathamesh_Shelar_Single_Tape_TM_14-11-2026.jff) | Turing Machine | **Validated & Verified** |
| **15** | [`15_Multi_Tape_TM`](./15_Multi_Tape_TM/) | 2-Tape Turing Machine (Binary String Duplication $w \to ww$) | [`65_Prathamesh_Shelar_Multi_Tape_TM_14-11-2026.jff`](./15_Multi_Tape_TM/65_Prathamesh_Shelar_Multi_Tape_TM_14-11-2026.jff) | Multi-Tape TM | **Validated & Verified** |

---

## 📂 Standard Repository Architecture

Each practical directory follows a consistent academic standard:
1. **Native JFLAP File(s) (`.jff`):** Validated XML models loadable directly into JFLAP with zero warnings or parsing exceptions.
2. **Comprehensive Report (`README.md`):**
   - Precise Problem Statement & Linguistic Characterization.
   - Formal Mathematical Tuple Specifications (5-tuple, 6-tuple, or 7-tuple).
   - Operational Logic, Stack Behavior, and Transition Tables.
   - Instantaneous Descriptions (IDs) and step-by-step trace deductions.
   - Comprehensive Test Suite with Accepted vs Rejected classifications.
   - GUI execution instructions for JFLAP.
3. **Formal Test Log (`validation_log.md`):** Complete test matrix detailing input vectors, expected vs observed outputs, and pass/fail indicators.

---

## 🚀 How to Run and Test in JFLAP

### Prerequisites:
- Java Runtime Environment (JRE 8 or above).
- Official JFLAP `.jar` distribution (available from [jflap.org](https://www.jflap.org/)).

### Execution Steps:
1. Launch JFLAP:
   ```bash
   java -jar JFLAP.jar
   ```
2. In JFLAP, click **File $\to$ Open** and choose any `.jff` file from this repository.
3. To test multiple strings simultaneously:
   - Click **Input $\to$ Multiple Run**.
   - Input test vectors as documented in the practical's `README.md` and click **Run Inputs**.
4. To observe step-by-step state animations:
   - Click **Input $\to$ Step with State...** and advance through input transitions.

---

## 👨‍🎓 Author Information
- **Student Name:** Prathamesh Shelar
- **Roll Number:** 65
- **Division / Batch:** D12A / C
- **Department:** Computer Engineering, Vivekanand Education Society's Institute of Technology (VESIT)
- **Course:** Theory of Computer Science (26CMPC51)
- **Academic Year:** 2026 – 2027
