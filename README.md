# spring-security-jwt
### https://www.bezkoder.com/spring-boot-security-postgresql-jwt-authentication/ 참고
| Methods | Urls              | Actions       |
|---------|-------------------|---------------|
| POST    | /api/auth/signup  | 계정 가입         |
| POST    | /api/auth/signin  | 계정에 로그인       |
| POST    | /api/auth/signout | 계정을 로그아웃      |
| GET     | /api/test/all     | 공개 콘텐츠 검색     |
| GET     | /api/test/user    | 사용자 콘텐츠에 액세스  |
| GET     | /api/test/mod     | 중재자의 콘텐츠에 액세스 |
| GET     | /api/test/admin   | 관리자 콘텐츠에 액세스  |


- Security :  Spring Security를 ​​설정하고 Security Object를 구현
- Controller :  가입/로그인 요청 및 승인된 요청을 처리
- Repository : JpaRepository 에는 데이터베이스와 상호 작용 하도록 Spring Data JPA를 확장하는 인터페이스
- Domain : 인증( ) 및 권한 부여( ) 에 대한 두 가지 주요 모델을 정의
- DTO : 요청 및 응답 객체에 대한 클래스를 정의