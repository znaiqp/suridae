# 수리대
스마트팜 농가와 수리 업체를 연결하는 UX 프로토타입입니다. 실제 수리 요청을 보내는 서비스가 아닙니다.

## 실행
별도 빌드는 필요 없습니다. 압축을 푼 폴더에서 `python3 -m http.server 8000`을 실행하고 http://localhost:8000 을 엽니다. 일부 아이콘 등은 외부 CDN을 사용합니다.

## GitHub에 올리기
저장소를 복제한 폴더의 최상위에 이 두 파일을 복사합니다. 기존 index.html이나 README.md가 있다면 덮어쓰기 전에 내용을 확인하세요.

```sh
git add index.html README.md
git commit -m "Add Suridae UX prototype"
git push
```

웹으로 공유하려면 저장소 Settings → Pages에서 배포할 브랜치와 /(root)를 선택하세요.
