
# 📚 Zotero 소개 및 단계별 설치·사용 가이드라인

> **핵심 원칙**: *"검색 플랫폼은 여러 개, 관리 플랫폼은 하나 (Zotero)"*

---

## 💡 Zotero 소개 (Introduction)

**Zotero**는 연구자와 대학원생을 위한 대표적인 무료·오픈소스 서지 및 연구 문헌 관리 프로그램입니다.

- **멀티플랫폼 지원**: Windows, macOS, Linux 운영체제를 모두 지원합니다.
- **통합 Research Library 구축**: 단순한 참고문헌 자동 생성기(Reference Generator)를 넘어, 수집한 문헌과 PDF를 체계적으로 분류하고 주석과 노트를 관리하는 나만의 '연구 라이브러리'를 구축하도록 돕습니다.
- **다양한 수집 및 호환성**: 웹 브라우저 Connector를 통한 원클릭 수집, DOI 번호를 활용한 자동 서지 검색, RISS 및 DBpia의 RIS 표준 파일 가져오기(Import)를 완벽히 지원합니다.
- **문서 작성 도구 연동**: MS Word, Google Docs, LibreOffice 등과 연동하여 본문 내 인용(In-text Citation) 삽입 및 APA 7th 등 다양한 양식의 참고문헌(Bibliography)을 1초 만에 자동 생성합니다.

---

## 🛠️ 스텝 바이 스텝 설치 및 설정 가이드 (Step-by-Step Setup)

### **Step 1: Zotero Desktop 설치 (필수)**
1. 공식 웹사이트 [zotero.org](https://www.zotero.org)에 접속합니다.
2. **[Download]** 버튼을 클릭하여 본인의 운영체제(Windows / macOS / Linux)에 맞는 Zotero Desktop 설치 프로그램을 다운로드하고 설치를 완료합니다.

### **Step 2: Zotero Connector 브라우저 확장 프로그램 설치 (필수)**
1. 동일한 다운로드 페이지에서 사용 중인 웹 브라우저(Chrome, Edge, Firefox, Safari 등)용 **Zotero Connector**를 설치합니다.
2. 설치 후 브라우저 우측 상단 확장 프로그램 메뉴에서 Zotero Connector 아이콘을 툴바에 고정(Pin)합니다.

### **Step 3: Zotero 계정 가입 및 동기화 설정 (선택 / 권장)**
1. [zotero.org](https://www.zotero.org) 상단 메뉴에서 무료 회원가입을 진행합니다.
2. Zotero Desktop 앱을 실행하고 `Settings(Preferences) → Sync` 메뉴로 이동하여 생성한 계정으로 로그인합니다.
   *(참고: 로컬 컴퓨터 내 라이브러리 저장 용량은 무제한이며, 계정 연동 시 300MB의 클라우드 파일 동기화 용량이 기본 제공됩니다)*.

### **Step 4: 워드프로세서(Word / Google Docs) 연동 확인**
1. Zotero Desktop이 실행된 상태에서 MS Word나 Google Docs를 실행합니다.
2. 상단 툴바 메뉴에 **Zotero** 탭이 자동으로 생성되었는지 확인합니다.
   *(만약 메뉴가 보이지 않을 경우 Zotero Desktop의 `Settings → Cite → Word Processors` 탭에서 플러그인을 재설치합니다)*

---

## 🔄 Zotero 문헌 관리 워크플로우 실습 (5-Step Workflow)

수업 및 연구 과정에서 반복할 수 있는 **Search → Select → Store → Verify → Organize → Cite**의 6단계 실습 흐름입니다.

```text
[검색 DB (RISS/DBpia/Scholar)] 
             │
             ▼
[Zotero Store (Connector / RIS / DOI)] 
             │
             ▼
[Verify & Organize (메타데이터 검증 / 중복병합 / 태그)] 
             │
             ▼
[Read & Record (PDF 하이라이트 & 노트 연동)] 
             │
             ▼
[Cite (Word / Google Docs 인용 및 참고문헌 생성)]
```

### 1. Collection 생성
Zotero 앱 좌측 상단 폴더 아이콘을 눌러 연구 주제별 컬렉션을 생성합니다 (예: `My Topic – Seminar 2026`).

### 2. 다양한 경로를 통한 문헌 수집 (Store)
- **방법 A (Connector)**: Google Scholar, DBpia 등의 논문 상세 페이지에서 브라우저 상단 Zotero Connector 아이콘을 클릭하여 저장합니다.
- **방법 B (RIS Import)**: Connector 미작동 시 RISS나 DBpia에서 'EndNote/Mendeley용 RIS 파일'로 내보낸 후 Zotero의 `File → Import` 메뉴로 불러옵니다.
- **방법 C (Identifier/DOI)**: Zotero 상단 마술봉 아이콘(`Add Item by Identifier`)에 해외 논문의 DOI 번호를 입력해 서지 정보를 불러옵니다.

### 3. 메타데이터 검증 및 라이브러리 정리 (Verify & Organize)
- **"Never cite before checking metadata"**: Zotero에 저장된 서지 항목(저자명, 출판연도, 논문 제목 대소문자, 학술지명, Volume/Issue, Page, DOI)을 우측 패널에서 직접 검증하고 수정합니다.
- **중복 제거 및 태그**: 좌측 `Duplicate Items`에서 중복 수집된 항목을 병합(Merge)하고, 하단 태그 창에서 `theory`, `empirical` 등 검색 키워드를 등록합니다.

### 4. PDF 읽기 및 노트 기록 (Read & Record)
- Zotero 내장 PDF 뷰어에서 주요 문장을 하이라이트한 뒤, 우클릭하여 **`Add to Note`**를 누르면 서지 정보와 직접 연동되는 아이템 노트가 생성됩니다.

### 5. 인용 및 참고문헌 자동 생성 (Cite)
- MS Word 또는 Google Docs에서 Zotero 탭의 **`Add/Edit Citation`**을 눌러 본문 내 인용을 삽입하고, **`Add/Edit Bibliography`**를 클릭해 APA 7th 양식의 참고문헌 목록을 자동 생성합니다.
```

📌
