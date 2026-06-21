# 01. Classification Baseline

분류 문제를 기준으로 AI Engineering의 기본 흐름을 정리하는 프로젝트입니다.

목표는 좋은 성능을 바로 내는 것이 아니라, 데이터 준비부터 모델 학습, 평가, 결과 기록까지의 과정을 명확히 이해하는 것입니다.

## Research Question

분류 모델을 만들 때 최소한 어떤 과정을 거쳐야 결과를 믿을 수 있을까?

## Scope

| Step | Description |
| --- | --- |
| Data | 데이터 구조 확인, train/validation/test 분할 |
| Baseline | 간단한 기준 모델 만들기 |
| Training | loss와 metric을 기록하며 학습하기 |
| Evaluation | accuracy 외에 confusion matrix, precision, recall 확인하기 |
| Report | 실험 조건과 결과를 정리하기 |

## Folder Structure

```text
01-classification-baseline/
├─ README.md
├─ src/
├─ notebooks/
├─ data/
├─ results/
├─ report.md
└─ references.md
```

## Status

Planned

## Notes

- 사용할 데이터셋은 아직 정하지 않았습니다.
- 처음에는 작은 공개 데이터셋으로 baseline 흐름을 이해하는 것을 우선합니다.
- 모델보다 실험 기록 방식과 평가 흐름을 먼저 정리합니다.
