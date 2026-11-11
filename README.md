# 한통도시락 이동 설정

목적지: https://smartstore.naver.com/hantongbox

운영: 카페24 DNS + redirect.name. GitHub Pages는 사용하지 않으며 이 저장소는 정적 이동 페이지 백업입니다.

- linechurch.net A: 45.55.126.223
- www CNAME: alias.redirect.name
- _redirect.linechurch.net TXT: Redirects to https://smartstore.naver.com/hantongbox
- _redirect.www.linechurch.net TXT: Redirects to https://smartstore.naver.com/hantongbox

HTTP·HTTPS와 www 주소, 기존 하위 경로 모두 목적지 첫 화면으로 이동합니다. 2026-11-11 실제 브라우저 확인.
