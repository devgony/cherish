#20.09.26

basic functions test

- keep obj in url and use it as a condition of checked
- total price calculation
- connect to calling
- capture html elements as a picture and save
- share with kakao

# branched to 'test'

# Main logic

1. 견적확인하기 클릭 시 2페이지로 이동
2. 2페이지에서 공유하기 누를 시 세부정보, 최종금액 기억한 상태로 공유
3. 다시 선택하기 누를 시 1페이지, 선택정보는 초기화

# QnA

1. 제공내역 아래 문구 추가 필요
2. 1페이지 선택 항목들의 기본값은? 필수 항목의 경우 페이지 렌더링 직후 이미 선택되어있어도 상관없는가?
   - 필수 아닌 항목만 default 가 "선택안함" 임
3. 도메인 어떻게 할 것인가?
   - 현재는 카카오의 멍청함 때문에 자세히 보기 아래 조그만 app 버튼은 최상위 도메인만 가리킴

# 추가 수정 필요사항

1. 폰번호 변경
2. Web title 변경
3. 사업자 이름(카카오API) 변경
