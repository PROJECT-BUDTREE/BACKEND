## Git workflow

< 주의 > 절대 master에 merge 하지 말것 !!!!!!!

```
master   (배포용)
             │
             ├── develop   (개발 진행용)
                            ├── feat/user
                            ├── feat/survey
                            ├── feat/post
```

## Commit 양식

- feat : 새로운 기능 추가
- fix : 버그 수정
- env : 개발 환경 관련 설정, 엔티티 or config 추가
- refactor : 코드 리팩토링 (더 효율적인 코드로 변경 등)
- comment : 주석 추가/수정
- docs : 내부 문서 추가/수정
- Rename : 파일 및 폴더명 수정
- Remove : 파일 및 폴더 삭제

ex) env : 프로젝트 초기 환경 세팅
