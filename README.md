## Route53 도메인 레코드 등록하기
![ㅇ](https://github.com/chomming/aws-tomcat/assets/81208053/97b7ea4f-0f55-4283-9292-ca290dfbaa90)

## 대상 그룹에 인스턴스와 포트 등록하기
- 일반적으로 대상 그룹 하나에 포트 하나 지정함

## ALB에 리스너 및 규칙 추가하기
- 포트 HTTP:80
  - HTTPS로 리다이렉션하기
- 포트 HTTPS:443
  - 소스 IP 지정 : 특정 IP만 접속 가능하도록 지정
    - 보안 그룹으로 지정해도 됨
