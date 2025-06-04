# ⚙️ Flash Sort Algorithm – Performance Variants (C++)

This project implements multiple variants of the **Flash Sort** algorithm in C++ to analyze and compare:

- **Execution time**
- **Number of comparisons**

Each variant serves a different measurement purpose, such as counting comparisons or measuring runtime only.

---

## 📁 File Overview

| File                             | Description                                      |
|----------------------------------|--------------------------------------------------|
| `selectionFlashSort.cpp`         | Standard Flash Sort implementation              |
| `selectionFlashSortWithCount.cpp`| Flash Sort with explicit comparison counter     |
| `selectionFlashSortWithoutCount.cpp` | Flash Sort variant without counting logic   |
| `code_count_compare.cpp`         | Test harness for comparison count measurement   |
| `code_time_consuming.cpp`        | Test harness for runtime measurement            |
| `command5.cpp`                   | Wrapper/command handling for experiments         |

---

## 🚀 How to Compile

Use a C++ compiler (e.g., `g++`) to compile any of the variants.

```bash
g++ selectionFlashSortWithCount.cpp -o flashsort_count
g++ code_time_consuming.cpp -o flashsort_time
```

---

## 📊 Experiment Use Cases

- **Count comparisons**:
  ```bash
  ./flashsort_count
  ```

- **Measure time consumption**:
  ```bash
  ./flashsort_time
  ```

---

## 📝 Notes

- Designed for academic purposes as part of a data structures & algorithms or algorithm analysis course.
- All files are self-contained for easy testing and benchmarking.

---

## 👨‍💻 Author
GitHub: [wa1mpls](https://github.com/wa1mpls)

---
