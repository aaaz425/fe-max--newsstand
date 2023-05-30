# 뉴스스탠드 프로젝트 📰 

네이버의 `뉴스스탠드` 영역을 구현해본다  
키워드 : `TypeScript` `Vite` `Dom APIs` `Crawling` `Css Grid` `em` `rem`

## 📗 설계

사용언어: `TypeScript`, `Scss`  
폰트: `Pretendard`  
개발 서버: `Vite`  
feature list: https://github.com/aaaz425/fe-max--newsstand/wiki/feature-list

- 정돈되지 않았던 개발 습관을 버리고, build 및 설계 과정을 체계화 시킨다
- github의 `wiki` 탭과 `issue` 탭을 적극 활용한다
- `wiki` 탭의 feature list에 명시한 순서대로 작업을 진행한다
  - 작업 순위가 낮은것 부터 진행하고, 같은 작업 순위라면 우선 순위가 높은 것 부터 진행한다
- `issue` 탭을 활용하여 현재 진행중인 작업과 예상 완료일을 관리해본다
- 폴더 및 파일 구조를 신경쓴다
- `prettier`, `eslint` 와 `tsconfig` 같은 설정을 신경쓴다
- `vite` 개발 서버를 활용하여 json 데이터를 정적 파일로써 fetch 과정 없이 사용한다
- 정적인 요소와 동적인 요소를 구분하여 동적인 요소만 ts로 작업한다

### 📗 프로젝트 의존성

```json
  "devDependencies": {
    "@types/node": "^20.2.3",
    "@typescript-eslint/eslint-plugin": "^5.59.6",
    "@typescript-eslint/parser": "^5.59.6",
    "eslint": "^8.41.0",
    "eslint-config-prettier": "^8.8.0",
    "eslint-plugin-prettier": "^4.2.1",
    "prettier": "2.8.8",
    "sass": "^1.62.1",
    "ts-node": "^10.9.1",
    "typescript": "^5.0.4",
    "vite": "^4.3.2"
  }
```

1. 의존성 설치

  ```
    npm install
  ```

2. TypeScript 컴파일 명령어

  ```
    tsc
  ```

3. Scss 컴파일 명령어

  ```
    npm run style
  ```

4. Vite 개발 서버 오픈 명령어

  ```
    npm run dev
  ```
