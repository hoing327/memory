# [Design Brief] Starter Pack - Neo-Future Visual System

## 1. 프로젝트 개요
* **목적**: Starter Pack의 핵심 가치(속도, 도구, 시스템)를 시각적으로 극대화하여 전환율을 높이는 UI/UX 설계.
* **핵심 키워드**: Neo-Future, Translucency (투명성), Electric Energy.
* **타겟 디자인 컨셉**: 고도의 기술력을 상징하는 네온(Neon) 컬러와 깊이감을 주는 글래스모피즘(Glassmorphism)의 결합.

## 2. 비주얼 시스템 가이드라인

### 🎨 Color Palette (Neo-Future Core)
| 구분 | 색상명 | Hex Code | 적용 포인트 |
| :--- | :--- | :--- | :--- |
| **Primary** | Neon Cyan | `#00F3FF` | 주요 CTA 버튼, 강조 텍스트, 네온 글로워 효과 |
| **Secondary** | Electric Purple | `#7000FF` | 포인트 그래픽, 그라데이션 보조색 |
| **Background** | Space Black | `#0A0A0B` | 메인 배경 (심도 있는 어두운 톤) |
| **Glass Surface** | Frost White | `rgba(255, 255, 255, 0.1)` | 글래스모피즘 패널의 기본 베이스 |

### 🖋 Typography (Systemic & Bold)
* **Headline**: Inter / Montserrat (Bold) - 강렬하고 현대적인 느낌.
* **Body**: Pretendard / Inter (Medium/Regular) - 가독성 중심.

### ✨ Visual Effects (Framer Motion & CSS)
1. **Glassmorphism**: `backdrop-filter: blur(12px)`, `border: 1px solid rgba(255, 255, 255, 0.1)` 적용하여 입체감 확보.
2. **Neon Glow**: Hover 시 버튼 및 아이콘에 `box-shadow`를 활용한 발광 효과 극대화.
3. **Motion Dynamics**: Framer Motion을 활용한 Staggered Entrance 애니메이션 및 호버 시 변화하는 네온 강도 구현.

## 3. 주요 화면 구성 (Starter Pack)
* **Hero Section**: 글래스 패널 위로 흐르는 네온 파티클 배경과 강력한 헤드라인 배치.
* **Feature Cards**: 3개 영역(도구, 시스템, 교육)을 각각의 글래스모피즘 카드에 담고, 호버 시 테두리 발광 효과 부여.
* **CTA Section**: "Starter Pack 시작하기" 버튼에 지속적인 Pulse 애니메이션 적용.