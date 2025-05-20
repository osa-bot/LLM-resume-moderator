# LLM-resume-moderator

---

[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

Built with:

![fastapi](https://img.shields.io/badge/FastAPI-009688.svg?style={0}&logo=FastAPI&logoColor=white)
![openai](https://img.shields.io/badge/OpenAI-412991.svg?style={0}&logo=OpenAI&logoColor=white)
![pydantic](https://img.shields.io/badge/Pydantic-E92063.svg?style={0}&logo=Pydantic&logoColor=white)

---

## Overview

LLM-resume-moderator automates the review of Russian language resumes, ensuring they meet specific criteria and assessing their overall quality. It offers a fast and efficient way to screen candidates without needing pre-trained data, helping recruiters identify suitable applicants quickly.

---

## Table of Contents

- [Core features](#core-features)
- [Installation](#installation)
- [Examples](#examples)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Citation](#citation)

---
## Core features

1. **Resume Moderation**: Analyzes resumes against predefined criteria, assessing relevance and overall quality using LLMs.
2. **Zero-Shot Classification**: Classifies resumes without requiring prior training on domain-specific data, leveraging zero-shot inference capabilities of large language models.
3. **API Endpoint**: Provides a REST API endpoint for submitting resumes and receiving moderation results with reasoning.

---

## Installation

Install LLM-resume-moderator using one of the following methods:

**Build from source:**

1. Clone the LLM-resume-moderator repository:
```sh
git clone https://github.com/LISA-ITMO/LLM-resume-moderator
```

2. Navigate to the project directory:
```sh
cd LLM-resume-moderator
```

3. Install the project dependencies:

```sh
pip install -r requirements.txt
```

---

## Examples

Examples of how this should work and how it should be used are available [here](https://github.com/LISA-ITMO/LLM-resume-moderator/tree/main/examples).

---

## Documentation

A detailed LLM-resume-moderator description is available [here](https://github.com/LISA-ITMO/LLM-resume-moderator/tree/main/data/docs).

---

## Contributing

- **[Report Issues](https://github.com/LISA-ITMO/LLM-resume-moderator/issues)**: Submit bugs found or log feature requests for the project.

---

## Citation

If you use this software, please cite it as below.

### APA format:

    LISA-ITMO (2025). LLM-resume-moderator repository [Computer software]. https://github.com/LISA-ITMO/LLM-resume-moderator

### BibTeX format:

    @misc{LLM-resume-moderator,

        author = {LISA-ITMO},

        title = {LLM-resume-moderator repository},

        year = {2025},

        publisher = {github.com},

        journal = {github.com repository},

        howpublished = {\url{https://github.com/LISA-ITMO/LLM-resume-moderator.git}},

        url = {https://github.com/LISA-ITMO/LLM-resume-moderator.git}

    }

---
