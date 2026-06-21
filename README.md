# AI Engineering Study

AI Engineering을 공부하면서 수업 내용, 논문/자료 리뷰, 구현 실험, 프로젝트 기록을 함께 정리하는 저장소입니다.

목표는 단순히 공부한 내용을 모아두는 것이 아니라, 학과 수업에서 배운 개념을 바탕으로 관련 자료를 더 찾아보고 직접 구현과 실험까지 이어가는 과정을 남기는 것입니다.

## Study Map

| Area | Scope | Repository role |
| --- | --- | --- |
| Data Structures & Algorithms | 리스트, 큐, 스택, 힙, 트리와 알고리즘 구현 연습 | 구현 기초와 문제 풀이 기록 |
| Time Series Analysis | 통계 기반 시계열 분석부터 RNN 기반 모델까지 | 시계열 예측 개념과 모델 비교 |
| Machine Learning | 지도/비지도 학습, 수학적 근거, 모델 작동 원리 | Linear model부터 SVM까지 직접 구현하며 이해 |
| Deep Learning | RNN, CNN, Attention, Transformer | 모델 구조와 프로젝트 적용 기록 |
| Natural Language Processing | 기본 NLP부터 LLM까지 | 텍스트 처리, 모델 구조, DRT 정책 제안 프로젝트 기록 |
| Reinforcement Learning | MDP, DP, TD, Q-learning, SARSA, Deep RL | 의사결정 문제와 학습 알고리즘 정리 |
| Computer Vision | 이미지 처리, 인식 모델, 자율주행 인지 | CV 개념과 자율주행 프로젝트 연결 |

## Repository Structure

```text
ai-engineering-study/
├─ README.md
├─ coursework/
│  ├─ README.md
│  ├─ data-structures-algorithms/
│  ├─ time-series-analysis/
│  ├─ machine-learning/
│  ├─ deep-learning/
│  ├─ natural-language-processing/
│  └─ reinforcement-learning/
├─ paper-reviews/
├─ implementations/
├─ projects/
│  ├─ README.md
│  └─ 01-classification-baseline/
├─ experiment-logs/
├─ notes/
├─ references/
└─ .gitignore
```

## How This Repository Is Organized

| Section | Purpose |
| --- | --- |
| `coursework/` | 학과 수업에서 배운 개념을 정리합니다. |
| `paper-reviews/` | 직접 찾아본 논문, 기술 글, 자료를 읽고 요약합니다. |
| `implementations/` | 논문이나 개념을 직접 코드로 구현해본 기록을 남깁니다. |
| `projects/` | 하나의 질문이나 목표를 가진 프로젝트를 폴더 단위로 정리합니다. |
| `experiment-logs/` | 실험 조건, 결과, 실패 원인, 다음 시도를 기록합니다. |
| `notes/` | 프로젝트와 별개로 정리한 AI Engineering 개념 노트입니다. |
| `references/` | 강의, 문서, 논문, 글 등 참고 자료를 모읍니다. |

## Project Records

| Project | Related area | Status | Description |
| --- | --- | --- | --- |
| [`01-classification-baseline`](./projects/01-classification-baseline) | Machine Learning | Planned | 분류 문제를 기준으로 데이터 분할, 학습, 평가 흐름을 정리하는 첫 프로젝트입니다. |
| Vehicle Trajectory Prediction | Deep Learning / Autonomous Driving | To be organized | 차량 궤적 예측 과제를 모델링 관점에서 정리할 예정입니다. |
| DRT Policy Recommendation | NLP / LLM / Transportation | In progress | DRT 운행 정책 제안 프로젝트와 논문화 과정을 정리할 예정입니다. |
| Road Topology & Ego-lane Inference | Computer Vision / Autonomous Driving | To be organized | 도로 topology 인식과 ego 차량 차선 판단 프로젝트를 정리할 예정입니다. |

## Study Workflow

```text
coursework -> notes -> paper review -> implementation -> experiment log -> project report
```

## Source Policy

- 강의자료나 외부 저장소 내용을 그대로 복사하지 않습니다.
- 참고한 자료는 `references/` 또는 각 프로젝트의 `references.md`에 출처를 남깁니다.
- README와 노트는 내가 이해한 방식으로 다시 설명합니다.
- 구현 파일은 직접 작성한 코드와 참고한 코드를 명확히 구분합니다.

## Current Status

초기 구조를 잡은 상태입니다. 앞으로 수업 기반 학습 기록과 직접 찾아본 자료, 구현 실험을 함께 추가할 예정입니다.
