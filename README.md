# 🗂️ Memory Cards — Open Anki Web

**누구나 웹에서 바로 사용하는 스마트 플래시카드 & Anki 대안 웹앱**  
최신 망각 곡선 알고리즘인 **FSRS (Free Spaced Repetition Scheduler)**와 **Supabase 클라우드 실시간 동기화**를 탑재하여, 모바일과 PC 어디서나 나만의 단어장과 암기 카드를 학습할 수 있습니다.

👉 **웹에서 바로 사용하기:** [https://EternalOlive.github.io/memory-cards-web/](https://EternalOlive.github.io/memory-cards-web/)

---

## ✨ 핵심 기능

1. **⚡ 설치 없는 웹 플래시카드 (PWA)**
   - 브라우저만 있으면 스마트폰, 태블릿, PC 어디서나 즉시 사용 가능합니다.
   - 모바일 홈 화면에 추가하면 앱스토어 설치 없이 전체화면 네이티브 앱처럼 동작합니다.

2. **🔄 모바일 ↔ PC 실시간 자동 연동 (Supabase)**
   - 복잡한 깃허브 토큰이나 설정 없이, **Google 계정 로그인** 한 번으로 모든 기기에서 학습 진도가 실시간 동기화됩니다.
   - 비로그인 상태에서도 브라우저 로컬 저장소를 통해 즉시 사용할 수 있습니다.

3. **🧠 과학적인 복습 주기 (FSRS 알고리즘)**
   - Anki의 최신 엔진과 동일한 FSRS 알고리즘을 적용하여 최적의 복습 주기(Again / Hard / Good / Easy)를 계산합니다.

4. **📚 자유로운 멀티 덱(Deck) & 일괄 가져오기(Import)**
   - 원하는 주제별로 덱을 무제한 생성/삭제/관리할 수 있습니다.
   - 엑셀, 스프레드시트, 메모장에서 `단어 [Tab] 뜻` 형태로 복사한 텍스트를 붙여넣기만 하면 수백 장의 카드가 1초 만에 자동 생성됩니다.
   - 'Speaking Matrix 영어회화 100제' 등 기본 샘플 덱 원클릭 탑재 지원.

---

## 📱 스마트폰/태블릿에서 앱으로 설치하기

1. 모바일 브라우저로 [https://EternalOlive.github.io/memory-cards-web/](https://EternalOlive.github.io/memory-cards-web/) 에 접속합니다.
2. **홈 화면에 추가**:
   - **아이폰 / 아이패드 (Safari):** 하단 중앙 공유 버튼(네모+화살표) → **[홈 화면에 추가]**
   - **안드로이드 / 갤럭시 (Chrome):** 우측 상단 메뉴(점 3개) → **[홈 화면에 추가]** 또는 **[앱 설치]**

---

## 🛠️ 기술 스택

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (No Build / Single-File WebApp)
- **Algorithm:** `ts-fsrs` (Free Spaced Repetition Scheduler v5.4.1)
- **Backend / Database:** Supabase (PostgreSQL, Row Level Security, Auth)
- **Hosting:** GitHub Pages
