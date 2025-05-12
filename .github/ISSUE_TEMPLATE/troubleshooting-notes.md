---
name: Troubleshooting-Notes
about: 새로운 이슈 작성
title: ''
labels: 버그-심각
assignees: ''

---

# 2025-04-16 API 토큰 인증 오류

## 🐞 에러 내용
로그인 후 API 요청 시 `401 Unauthorized` 오류 발생

## 🔍 원인 분석
- 서버에서는 토큰 검증 로직이 있음
- 클라이언트에서 토큰을 Authorization 헤더에 담지 않음

## ✅ 해결 방법
- axios 인스턴스에 default header 설정 추가

## 회고
-
