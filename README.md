# SHA-256 Implementation - Computational Theory Project

This repository contains a complete from-scratch implementation of the SHA-256 cryptographic hash algorithm, following the NIST FIPS 180-4 specification.

## Problems Overview

1. **Binary Words and Operations** - Implementation of SHA-256 logical and rotation functions
2. **Fractional Parts of Cube Roots** - Generation of SHA-256 constants from prime cube roots
3. **Padding** - Message padding and block parsing according to SHA-256 specification
4. **Hashes** - Complete SHA-256 hash computation function
5. **Passwords** - Password cracking demonstration and security analysis using rainbow tables

## Getting Started

### Prerequisites
* Python 3.8 or higher
* Git

### Setup

1. Clone the repository:
```bash
   git clone https://github.com/PatrickClerkin/Computational-Theory-Project.git
   cd Computational-Theory-Project
```

2. Install dependencies:
```bash
   pip install numpy jupyter
```

3. Run the notebook:
```bash
   jupyter notebook problems.ipynb
```

## Dependencies

* `numpy` - For 32-bit unsigned integer operations and mathematical functions
* `jupyter` - For notebook environment

## References

* **NIST FIPS 180-4 Secure Hash Standard**
* **OWASP Password Storage Cheat Sheet**
* Full references included in the notebook

## Author

Patrick Clerkin