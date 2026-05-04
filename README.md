# ML Research Coding Skills
A practical instruction set for LLM-assisted machine learning research coding.

---

## 🇰🇷 Korean

이 저장소는 LLM을 활용한 머신러닝 연구 과정에서의 코딩 방식을 개선하기 위한 지침서입니다.

지침서는 LLM이 연구 맥락을 기반으로 요구사항을 정리하고, 이를 최소한의 코드로 정확하게 구현하는 것을 목표로 합니다.

이 프로젝트는 **andrej-karpathy-skills**에서 영감을 받아
머신러닝 연구 환경에 맞게 재구성되었습니다.

코드 작성은 사용자가 명시적으로 요청한 경우에만 수행하며, 그 전에는 요구사항 정리와 실험 설계를 우선합니다.

### 핵심 철학

* 구현 전에 요구사항을 명확히 정의한다
* 모호한 아이디어를 실험 가능한 형태로 변환한다
* 불필요한 기능이나 추상화를 추가하지 않는다
* 필요한 부분만 수정한다
* 재현 가능한 실험 흐름을 우선한다

### 배경

이 지침서는 “LLM이 코드를 성급하게 작성하는 문제”를 해결하기 위해 만들어졌습니다.

특히 다음과 같은 문제를 줄이기 위한 목적을 가집니다:

* 요구사항이 불명확한 상태에서의 코드 생성
* 실험 설계 없이 구현부터 시작하는 패턴
* 불필요하게 복잡한 구조
* 과도한 일반화 및 추상화


### 사용 방법

`ML_RESEARCH_CODING_GUIDELINES.md`의 내용을
다음과 같은 환경에서 시스템 프롬프트 또는 지침으로 사용하면 됩니다:

* ChatGPT Custom Instructions
* Claude Project Instructions
* Cursor Rules
* GitHub Copilot Workspace 설정
* 로컬 LLM 에이전트

---

## 🇺🇸 English

This repository provides a guideline for improving how LLMs are used in machine learning research coding.

This guideline helps LLMs structure requirements based on the research context and implement them accurately with minimal code.

This project is inspired by **andrej-karpathy-skills** and is adapted for machine learning research workflows.

Code should only be written when explicitly requested by the user. Before that, the focus should be on clarifying requirements and designing experiments.

### Core Principles

* Clearly define requirements before implementation
* Convert vague ideas into testable experiment designs
* Do not add unnecessary features or abstractions
* Make only necessary changes
* Prioritize reproducible experimental workflows

### Background

This guideline was created to address the issue of LLMs generating code too quickly.

In particular, it aims to reduce the following problems:

* Generating code with unclear requirements
* Starting implementation without experimental design
* Unnecessarily complex structures
* Over-generalization and excessive abstraction


### How to Use

Use the contents of `ML_RESEARCH_CODING_GUIDELINES.md` as a system prompt or instruction in the following environments:

* ChatGPT Custom Instructions
* Claude Project Instructions
* Cursor Rules
* GitHub Copilot Workspace settings
* Local LLM agents

---

## License

MIT License
