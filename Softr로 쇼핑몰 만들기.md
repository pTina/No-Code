## 주제
쇼핑몰 제작하기
(선택 브랜드: 이솝)

## 준비물
웹페이지에 사용할 리소스
Airtable 회원가입

## Airtable 데이터베이스 기본 사용법
좌측 상단쪽에 Tools > Manage fields 메뉴통해 데이터베이스 관리 가능
#
## 시작하기
무료 템플릿 중 'Fashion E-commerce'선택

Airtable 로그인 후 API key를 입력하면 자동으로 데이터베이스 생성까지 해줌

데이터베이스에 제품 등록을 하면 앱에 자동으로 보여짐
DB수정할 때마다 실시간 적용되긴 함

### page이름: list4 설정하기
## 1. DATA


* Airtable 연동 가능

* LIST SETTING
    - Sort by
    : DB의 Field별로 정렬가능(순차 or 역순)
    -  Items per page
    : 한 페이지에 보여줄 최대 아이템 갯수
    -Items per row 
    : 한 행에 보여줄 아이템 갯수(3 or 4)
* EMPTY STATE

    아마도 불러오기 실패했을 때 보여줄 메세지 지정

* Link text
    - 링크가 연결될 텍스트 지정
    - Add action
        - Open page
            내부 페이지 연결하여 해당 페이지 열기
        - Scroll to section
            해당 영역으로 이동됨
        - Open external url
            외부 url 연결

## 2. FEATURES

### INLINE FILTERS
* Filter Settings
    - 필터를 설정할 수 있음
    - 기본 값으로 설정할 필드값을 Label에 입력해주는 것이 바람직한 것 같음
    - Filter by: 카테고리, Options는 자동으로 해당 필드값이 가질 수 있는 값으로 채워짐(핸드, 바디)
    - Show as: List | Dropdown(요거 선택)
    - Allow multiselect(중복선택 여부): 체크 | 체크하지 않음

#

## 3. Add Block
추가할 수 있는 블럭 종류
1. static
- header
- Hero
- Feature
- Feature Grid
- CTA
- Partner
- Gallery
- pricing
- Team
- Testimonial
- FAQ
- Custom Code (유료)
- Other
    - Simple text 블럭을 추가하여 styles의 padding값을 최대로 지정하여 배경이미지를 넣는것이 Simple imgae or Simple image full width 보다 괜찮은 것 같다.

2. dynamic

    제품상세 등과 같은 데이터와 연동되어 동적으로 값이 바뀌어야 하는 레이아웃
    - Form
    - User Accounts
    - Payment
    - List
    - List Details
    
        제품상세페이지 만들 때 사용할 수 있음
        종류가 다양하지 않아서 아쉬움
        사실 맘에 드는게 별로 없었음(선택지 4개 - 무료)
    - Table
    - Calendar
    - Kanban
    - Chart
    - Organiztional Chart
    - Comments
    - Map   

#


### 작업목록
2022-11-18: 제품 상세보기 페이지 만들기(item-detail)

#

### 이슈

2022-11-12~ 이미지, 텍스트가 제대로 보이지 않음

2022-11-14: ITEM FIELDS에 Content값을 '사진'으로 변경하여 해결함

(DB의 field값을 한글로 변경함으로써 Content값을 변경하지 않아서 발생한 오류임)

#
### 결과물
1.이솝_tina

https://zachery211.softr.app



