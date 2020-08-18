# MoGakCo Project

## 개요

* google map api 를 이용한 지도 기반 개발자 모임 예약 모바일 앱

## 구성

REST ful

* Spring server 와 Android retrofit 연결

* 안드로이드 앱
  * Google mapView API
  * retrofit 을 이용하여 서버에 rest request 요청
* 서버
  * DB 처리 (데이터, 로그 저장)
  * RESTful API -> json 이용. (Jackson libirary)

## VO

1. user.class
   * id (pk)
   * password
   * email (이메일 인증)
   * location - 도로명 주소 이용.
   * 





