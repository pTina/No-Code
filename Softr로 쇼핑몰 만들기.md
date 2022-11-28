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

## 4. form
외부로 보낼 폼 양식
- FEATURES
    - Destination
        - Send to data source
        - Add to Mailchimp
        - Add to Mailerlite
        - Send to Zapier
        - Send to Make
        - Forward to your email

        DB를 활용할 것이 아닌 경우 테스트로 'Forward to your email' 옵션 사용하는 것이 제일 편함
        사용자가 입력한 폼 내용을 이메일로 전달받을 수 있음

    - 폼 작성 요령
        - Input Type
            - Email, Text, Long text, Url, Dropdown, Phone number, File, Multiselect Dropdown, Hidden, Date, DateTime, Checkbox, Rating, Address
        - Map to

            값과 쌍으로 연결될 Key값으로 생각하면 됨
        - Label

            화면에 표시될 내용
        - Placeholder

            빈값일 때 input 공간에 표시될 내용
        - Required

            활성화 또는 비활성화

            (값이 반드시 필요한 경우 활성화)

        
        Input type에 따라 유효성 검사 가능해보임
#

### 작업목록
2022-11-18: 제품 상세보기 페이지 만들기(item-detail)


2022-11-23: 구매 페이지 만들기


2022-11-25

Zapier 사용해보기

구글 드라이브, 엑셀, softr로 제작한 앱 연결

주문서 정보다 담긴 JSON을 스프레드 시트에 저장하는 것까지 완료

2022-11-29

Zapier 사용하여 JSON 문자열 처리

Text in Formatter by Zapier, Utilities in Formatter by Zapier 사용하였음

주먹구구식 방법으로 하여 문자열 처리만 8단계가 나왔음


#

### 이슈

2022-11-12~ 이미지, 텍스트가 제대로 보이지 않음

2022-11-14: ITEM FIELDS에 Content값을 '사진'으로 변경하여 해결함

(DB의 field값을 한글로 변경함으로써 Content값을 변경하지 않아서 발생한 오류임)

2022-11-23: 주문서 페이지

선택한 제품의 제품명을 자동으로 가져올 수 있는 방법을 찾지 못했음

(custom code 기능 사용하여 코드를 추가하면 될 것 같아보임 개인적인 예상)

2022-11-25: 스프레드시트에 저장된 JSON 데이터 처리 해야함

2022-11-29: 실제 스프레드시트에 값이 제대로 입력되지 않음, Zapier에서 테스트 했을 때는 제대로 입력되었음



#
### 결과물
1.이솝_tina

https://zachery211.softr.app



