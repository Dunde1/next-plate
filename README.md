# next-plate

- Boilerplate using next.js

---

## Add packages 🗃

### eslint

- config
  - no-console
  - React import required in jsx, tsx test files


- references
  - [blog :: eslint와 prettier의 기초 설정법](https://pravusid.kr/typescript/2020/07/19/typescript-eslint-prettier.html)
  - [설정 참고 문서](https://github.com/typescript-eslint/typescript-eslint/tree/main/packages/eslint-plugin#supported-rules)
  - [커스텀 룰 리스트](https://typescript-eslint.io/rules/)

### prettier

- references
  - [설정 참고 문서](https://prettier.io/docs/en/configuration.html)

### jest

- references
  - [blog :: next.js에서 jest 설치](https://yoonho-devlog.tistory.com/175)
  - [identity-obj-proxy 오류 해결](https://stackoverflow.com/questions/52814985/undefined-returned-when-using-identity-obj-proxy-with-typescript-with-jest)
  - [공식 문서](https://jestjs.io/)

### husky

- config
  - `pre-commit`: `jest`를 사용하여 커밋 전 관련 파일 테스트 수행


- references
  - [공식 문서](https://typicode.github.io/husky/#/)
