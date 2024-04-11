## Spring Data JPA 설정

## application.properties
### spring.jpa.hibernate.ddl-auto=설정값
설정값의 종류

    - create : 기존 테이블 삭제 후 다시 생성(DROP + CREATE)
    - create-drop : create와 같으나 종료 시점에 테이블 DROP
    - update : 변경분만 반영(개발 환경에서만 사용할 것)
    - validate : 엔티티와 테이블이 정상적인지만 확인
    - none : DDL 처리에 관여하지 않음

### spring.jpa.properties.hibernate.format_sql=true
스프링 부트가 실행되면서 사용하는 SQL들의 포맷팅을 의미하는데 true인 경우 줄바꿈 

### spring.jpa.show-sql=true
실행 과정에서 만들어지는 SQL을 출력할 것인지 의미