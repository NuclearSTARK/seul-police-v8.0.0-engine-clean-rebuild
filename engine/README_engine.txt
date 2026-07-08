SEUL POLICE v8.0.0 engine folder

GitHub에 직접 업로드할 때는 engine 폴더를 그대로 올려야 합니다.
핵심 실행 파일은 engine/workEngine.js 입니다.

규칙:
- 기본 BASE_PATTERN: 1234
- C반 1발전 BASE_PATTERN: 1432
- 회전: 오른쪽 회전만 사용(1234 → 4123 → 3412 → 2341)
- 휴무는 회전 카운트 제외
- 근무자 선택 순서가 1,2,3,4의 사람 매핑입니다.
