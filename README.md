# svg-sprite 
SVG 파일을 스프라이트 형태로 변환하는 스크립트입니다.

## 의존성
- svg-sprite
- xmldom

## 사용 방법
1. 패키지 설치 -> `pnpm install`
2. 변환하고자하는 SVG 파일을 icons 파일로 붙여넣은 후 터미널 `node main.js` 입력
3. `./symbol/svg/sprite.symbol.svg` 파일의 결과값 확인 및 사용

## 결과 예시
```js
<svg xmlns="http://www.w3.org/2000/svg" width="0" height="0">
    <symbol viewBox="0 0 24 24" id="account" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M14.999 19.128a9.379 9.379 0 0 0 2.625.372 9.336 9.336 0 0 0 4.121-.952 4.124 4.124 0 0 0-7.533-2.493m.787 3.073v-.003c0-1.113-.286-2.16-.787-3.07m.787 3.073v.106A12.318 12.318 0 0 1 8.623 21c-2.33 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07m-2.213-9.68a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z"
        stroke="fill"
        strokeWidth="1.5"
        strokeLinecap="round"
        strokeLinejoin="round"
      />
    </symbol>
    <symbol viewBox="0 0 24 24" id="account" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M14.999 19.128a9.379 9.379 0 0 0 2.625.372 9.336 9.336 0 0 0 4.121-.952 4.124 4.124 0 0 0-7.533-2.493m.787 3.073v-.003c0-1.113-.286-2.16-.787-3.07m.787 3.073v.106A12.318 12.318 0 0 1 8.623 21c-2.33 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07m-2.213-9.68a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z"
        stroke="fill"
        strokeWidth="1.5"
        strokeLinecap="round"
        strokeLinejoin="round"
      />
    </symbol>
</svg>
```
