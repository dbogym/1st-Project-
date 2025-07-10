# NBE5-7-1-Team01

## 커피를 찾을 수 없습니다, <span style="color: red;">404</span> Coffee Not Found
**404 Coffee Not Found**는 카페 메뉴의 효율적인
CRUD(Create, Read, Update, Delete) 운영 시스템을 구축하고,

고객 주문 데이터를 이메일 기준으로 통합 관리할 수 있는 플랫폼을 구현한 프로젝트입니다 !

<img src="https://github.com/user-attachments/assets/9fb40579-df74-4981-8de7-67d273249f9c" alt="Image" width="50%" />


---

## 🗓️ 개발기간
**2024.04.23 ~ 2024.04.28**

---

## 😈 팀원 소개
| 이름 | 주요 역할 | 추가 세부 역할 | 파트 |
|:------:|:---------:|:--------------:|:----:|
| [황성철](https://github.com/HwuanPage) | PM(프로젝트 매니저), UI 개발자 | 프로젝트 전체 관리 및 계획 수립, 전체 UI 개발 담당 | 전체 관리 |
| [신현우](https://github.com/newname99) | UI 개발자 | 사용자인터페이스(UI) 화면 개발 및 최종 화면 완성 | 메인 페이지, 관리자 페이지 |
| [진주열](https://github.com/JuYul-Jin) | 서버 개발자 | 주요 비즈니스 로직 보조 개발 및 API 구현 지원 | ITEM 클래스 |
| [정미광](https://github.com/mipangg) | 서버 개발자 | 주요 비즈니스 로직 보조 개발 및 API 구현 지원 | ORDERITEMS 클래스 |
| [고영민](https://github.com/dbogym) | 서버 개발자 | 주요 비즈니스 로직 보조 개발 및 DB 설계 및 연동 | ORDER 클래스 |

---

## 📍 주요 기능
| 구분 | 기능명 | 설명 |
|------|-------|------|
| 공통 | 상품 목록 조회 | 전체 상품 목록을 조회 (+ 카테고리별 필터링 기능 제공) |
| 고객 | 장바구니 관리 | 상품을 장바구니에 추가/삭제하고 수량 조절 및 총합 금액 확인 가능 |
| 고객 | 주문하기 | 이메일, 주소, 우편번호 입력 후 원하는 상품과 수량을 선택하여 주문 수행 |
| 고객 | 주문 내역 확인 | "결제하기" 클릭 시 주문 완료 알림창 확인 |
| 고객 | 주문 내역 조회 | 본인의 이메일을 기반으로 주문 내역 및 주문 상세 조회 가능 |
| 관리자 | 상품 등록 | 새로운 상품을 이름, 가격, 이미지, 카테고리와 함께 등록 가능 |
| 관리자 | 상품 수정 | 기존 상품의 정보 수정 가능 (ex. 상품의 이름/가격/설명/이미지 변경) |
| 관리자 | 상품 삭제 | 기존 상품 삭제 가능 |
| 관리자 | 주문 전체 조회 | 고객들의 주문 전체 리스트를 조회하고 상세 주문 내용 확인 가능 |
| 관리자 | 주문 상태 변경 | 주문 상태를 준비 중, 배송 중 등으로 변경 가능 (선택 사항) |

---

## 🔀 Flow Chart
<img src="https://github.com/user-attachments/assets/0b2f6918-bf4b-4e13-adf9-f1cd55de1b29" alt="Image" width="50%" />

---

## 💽 ERD
<img src="https://github.com/user-attachments/assets/e5938e48-36d3-4c2a-ba9f-5e433325e3d5" alt="Image" width="80%" />

---

## 🧩 Class Diagram
<img src="https://github.com/user-attachments/assets/8b98beb1-a665-4916-b4d5-59ee2379a080" alt="Image" width="60%" />

---

## 📄 API 명세서
<img src="https://github.com/user-attachments/assets/6626bf1c-6699-4694-8071-152e1aef2a19" alt="Image" width="100%" />

---

## 🛠️ 기술 스택
<img src="https://github.com/user-attachments/assets/27a7ae2b-f72b-4680-9536-c185f16b8eea" alt="Image" width="70%" />

---

## 🛒 주요 기능별 화면

<details>
<summary>고객 기능</summary>

### 📌 주문 내역 작성 (고객)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/de435ecf-55e4-43d4-9152-3457b7f3081e" />

### 📌 주문하기 (고객)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/ae609ee9-285d-458c-a5d6-bbdb53a75685" />

### 📌 주문 내역 조회 (고객)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/d31b6f3d-d9d1-4c40-8ab3-7897860bfc7f" />

### 📌 주문 내역 수정 (고객)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/96b64872-bfa9-41f6-be28-9d95fbb8d5e6" />

</details>

<details>
<summary>관리자 기능</summary>

### 📌 메뉴 아이템 추가 (관리자)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/3ec212f0-afa7-4186-98cf-2de939baa881" />

### 📌 메뉴 아이템 관리 (관리자)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/18966609-638e-4ff3-bdf0-e7149dae0b2d" />

### 📌 메뉴 아이템 수정 (관리자)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/a5dac0a7-256f-4ef2-9275-58dfbd3ca5d9" />

### 📌 주문 내역 조회 (관리자)
<img width="1608" alt="Image" src="https://github.com/user-attachments/assets/b737166d-8302-4d52-b908-d6a2f00e6a19" />

</details>

## 💢 트러블 슈팅

### 1. JPA 연관관계 무한 참조 문제

#### 🚨 문제상황
- `Orders`와 `OrderItems` 엔티티 간 양방향 연관관계로 인한 무한 참조 발생
- JSON 직렬화 시 `Orders` → `OrderItems` → `Orders` → ... 무한 루프 생성
- API 응답에서 StackOverflowError 또는 무한 JSON 생성으로 서버 성능 저하
- 주문 내역 조회 API 호출 시 응답이 무한대로 늘어나는 현상

#### 🔧 해결과정
1. **문제 원인 분석**: JPA 양방향 연관관계에서 JSON 직렬화 시 순환 참조 발생 확인
2. **해결책 검토**: `@JsonIgnore`, `@JsonManagedReference/@JsonBackReference`, DTO 패턴 등 비교
3. **적용 및 테스트**: `@JsonIgnore` 어노테이션을 적용하여 순환 참조 차단

    ```java
    // OrderItems.java - @JsonIgnore 어노테이션 적용
    @ManyToOne
    @JsonIgnore  // JSON 직렬화에서 제외하여 순환 참조 방지
    @JoinColumn(name = "orders_id")
    private Orders orders;
    ```

#### ✅ 결과
- JSON 직렬화 시 무한 참조 문제 완전 해결
- 안정적인 주문 내역 조회 API 구현 완료
- JPA 연관관계 매핑과 JSON 직렬화 이슈에 대한 깊이 있는 이해 습득
---
### 2. Git 협업 중 Merge Conflict 빈발

#### 🚨 문제상황
- 팀원 5명이 처음 진행하는 Git 협업에서 merge conflict가 빈번하게 발생
- 같은 파일을 동시에 수정하거나 커밋 순서 문제로 인한 충돌 지속
- 충돌 해결 방법을 모르는 팀원들로 인해 개발 진행 지연
- 잘못된 merge로 인한 코드 손실 및 되돌리기 작업 반복

#### 🔧 해결과정
1. **Git 워크플로우 학습**
    - Git 브랜치 전략 및 협업 방식 연구
    - 팀원들과 함께 Git 기본 명령어 및 개념 학습

2. **브랜치 전략 수립**
    ```bash
    # 브랜치 구조
    main         # 배포용 안정 브랜치
    develop      # 개발 통합 브랜치  
    feature/*    # 기능별 개발 브랜치
    ```

#### ✅ 결과
- merge conflict 발생률 감소
- 안정적인 Git 협업 환경 구축으로 개발 효율성 향상
- Pull Request를 통한 코드 리뷰 문화 정착으로 코드 품질 개선
- 팀원 전체의 Git 워크플로우에 대한 실무적 이해 및 활용 능력 습득

---


