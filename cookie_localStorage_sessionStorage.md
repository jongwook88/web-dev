# Cookie & LocalStorage & SessionStorage
- 쿠키 = 로컬스토리지 = 세션스토리지 = 캐싱기법
- 보안에 취약. 중요한 정보는 저장하면 안됨

## Cookie
- 서버단에서 사용하기 위해 사용되는 캐싱기법 (서버전달Y)
- 저장용량 : 저장할 수 있는 용량이 작다 4kb
- 저장방식 : 클라이언트에 파일로 저장됨
- 라이프사이클 : 서버에서 생성되어짐.
    - 만료날짜(쿠키에 포함되어 있음)가 되면 만료됨
    
## Session
- 클라이언트와 통신을 위해 사용되는 캐싱기법
- 저장용량 : 서버에 따라 다름
- 저장방식 : 서버에 저장됨
- 라이프사이클 : 클라이언트에서 요청 시 생성
    - 브라우저가 닫히면 세션 만료

## LocalStorage
- 클라이언트단에서 사용하기 위해 사용되는 캐싱기법 (서버전달N)
- 저장용량 : 5mb
- 저장방식 : 클라이언트에 파일로 저장됨
- 라이프사이클 : 자바스크립트로 세팅
    - 만료날짜 없음
    
## SessionStorage
- 클라이언트단에서 사용하기 위해 사용되는 캐싱기법 (서버전달N)
- 라이프사이클 : 자바스크립트로 세팅
    - 브라우저가 닫히면 데이터 만료