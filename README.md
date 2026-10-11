# 2026 ETRI Summer Internship

2026년 한국전자통신연구원(ETRI) 하계 인턴십에서 수행한 **voxel-based 3D spatial intelligence** 연구와 학술 발표 성과를 정리한 포트폴리오입니다.

두 연구는 3차원 공간을 규칙적인 voxel grid로 표현하고, Deep Learning을 이용해 도시 객체의 semantic class 또는 두 객체 사이의 spatial relation을 추론한다는 공통 주제를 가집니다.

## Research Summary

| Research | Venue / Date | Role | Main Task |
|---|---|---|---|
| [3D CNN 기반 도심 3차원 데이터 의미론적 분할을 위한 복셀라이제이션 기법별 성능 비교](./01-KOREA-AI-2026-Voxel-Semantic-Segmentation/) | KOREA AI 2026, 한국통신학회 인공지능 학술대회 · 2026-09-29 | 공동 제1저자 (Co-first author) | Voxel color representation과 spatial composition에 따른 Sparse 3D CNN semantic segmentation 성능 비교 |
| [Comparative Analysis of Deep Learning Models for Voxel-Based 3D Spatial Relation Operations](./02-KAIA-2026-Voxel-Spatial-Relations/) | KAIA 2026, 한국인공지능학회 하계학술대회 · 2026-08-06 | 제1저자 (First author) | MLP, 3D CNN, Voxel Transformer 기반 6-class spatial relation classification 비교 |

## Research Themes

- 3D Point Cloud 및 Voxelization
- 3D Semantic Segmentation
- Sparse 3D CNN
- Voxel-based Spatial Relation Classification
- Voxel Transformer
- Digital Twin 및 3D Spatial Information

## Repository Structure

```text
.
├── 01-KOREA-AI-2026-Voxel-Semantic-Segmentation/
│   ├── README.md
│   ├── assets/       # README에 사용한 핵심 발표 슬라이드
│   └── materials/    # 논문, 원본 PPTX, GitHub 미리보기용 PDF
├── 02-KAIA-2026-Voxel-Spatial-Relations/
│   ├── README.md
│   ├── assets/       # 전체 포스터 및 구역별 이미지
│   └── materials/    # 논문, 원본 포스터 PPTX, 1면 포스터 PDF
└── .gitignore
```

## Materials Policy

- 이 저장소에는 연구 포트폴리오에 필요한 논문, 발표자료, 포스터와 설명용 이미지만 포함합니다.
- 원본 dataset, model checkpoint, 실험 cache 및 대용량 중간 산출물은 포함하지 않습니다.
- PDF 미리보기와 README 이미지는 원본 발표자료의 시각적 구성을 유지해 변환한 자료입니다.
- 논문·발표자료의 저작권과 인용 권리는 각 저자, 학회 및 관련 기관의 정책을 따릅니다.

## Acknowledgement

두 연구는 ETRI에서 수행한 2026년 하계 인턴십 연구 경험을 기반으로 합니다. 관련 연구에는 국토교통부와 국토교통과학기술진흥원의 지원 과제 `RS-2025-02317649`가 명시되어 있습니다.
