# Paper-review

# 🧠 Segment Anything 논문 리뷰

> **Paper**: [Segment Anything (SAM)](https://arxiv.org/abs/2304.02643)  
> **Authors**: Kirillov et al. (Meta AI Research, 2023)  
> **Code**: [GitHub Repo](https://github.com/facebookresearch/segment-anything)

---

## 📌 요약

**Segment Anything Model (SAM)**은 범용적인 이미지 분할 모델로, 사용자 프롬프트(점, 박스, 마스크 등)를 기반으로 어떤 객체든 실시간으로 분할할 수 있습니다.  
특징적으로, 거대한 분할 데이터셋(SA-1B)을 통해 학습되었으며, 다양한 응용에서 **zero-shot segmentation**을 지원합니다.

---

## 🛠️ 아키텍처

- Vision Transformer 기반 **이미지 인코더**
- **프롬프트 인코더**: 점, 박스, 마스크 등을 벡터화
- **마스크 디코더**: 다중 마스크 후보를 출력 + 품질 점수 제공

---

## 🔍 실험 및 성능

- SA-1B 데이터셋으로 사전학습
- 다양한 도메인에서 우수한 zero-shot 성능
- 기존 segmentation 모델들과의 비교에서 경쟁력 있음

---

## 💬 개인 의견

- "무엇이든 분할한다"는 점에서 범용성이 뛰어남
- 프롬프트 기반 접근이 실용적이며


