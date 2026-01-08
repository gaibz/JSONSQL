# Contributing to JSONSQL

First of all, thank you for your interest in contributing to **JSONSQL** 🎉

This repository is maintained as a **SPECIFICATION / CONTRACT** repository.  
Contributions are welcome, but they must respect the nature and stability of the specification.

---

## Scope of This Repository

This repository focuses on:

- Defining and maintaining the **JSONSQL specification**
- Providing clear, stable, and unambiguous documentation
- Offering examples that demonstrate correct usage of the specification

This repository does **NOT** provide:
- Reference implementations
- Parsers or execution engines
- Framework-specific libraries

---

## Types of Contributions Welcome

We welcome contributions in the following areas:

### ✅ Specification Improvements
- Clarifying ambiguous wording
- Improving explanations or structure
- Adding well-defined examples
- Fixing inconsistencies or mistakes

### ✅ Documentation Enhancements
- README improvements
- Better examples
- Diagrams or explanations that improve understanding

### ✅ Community Libraries Listing
- Adding links to JSONSQL-compatible libraries
- Improving the "Library" section documentation

---

## Contributions That Require Extra Caution

Because JSONSQL is a **contract**, some changes require special care:

- Adding new fields
- Modifying existing semantics
- Changing operator behavior
- Introducing breaking changes

Such contributions will be reviewed very carefully and may be postponed or rejected to preserve backward compatibility.

---

## Versioning Policy

- JSONSQL follows **semantic versioning**
- Breaking changes require a **major version** increment
- Additive, backward-compatible changes may be included in minor updates
- Editorial or clarification changes may be applied as patches

---

## How to Contribute

### 1. Fork the Repository
Create a fork of this repository to your own GitHub account.

### 2. Create a Branch
Use a descriptive branch name:

```text
docs/clarify-where-clause
spec/add-json-operator
examples/add-aggregate-query
```

### 3. Make Your Changes

* Keep changes focused and minimal
* Avoid unrelated refactors
* Ensure examples follow the specification exactly

### 4. Submit a Pull Request

When submitting a PR, please include:

* A clear description of **what** is being changed
* The **reasoning** behind the change
* Whether the change is **breaking** or **non-breaking**

---

## Pull Request Review Process

* All pull requests are reviewed by the repository owner(s)
* Changes to the specification may require discussion before approval
* Maintainers may request revisions or clarifications

Please be patient — specification work prioritizes correctness over speed.

---

## Code of Conduct

All contributors are expected to:

* Be respectful and professional
* Engage in constructive discussion
* Focus on improving the specification, not personal preferences

Harassment, disrespectful behavior, or disruptive communication will not be tolerated.

---

## Attribution

Contributors may be acknowledged in the project documentation or contributor listings, where appropriate.

---

## Final Note

JSONSQL is designed to be **stable, predictable, and boring (in a good way)**.

If you are unsure whether a change fits the scope of this repository, feel free to open an issue for discussion before submitting a pull request.

Thank you for helping improve JSONSQL 🚀

