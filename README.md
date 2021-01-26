# Typescript로 블록체인 만들기

## nomadcoders.co의 Typescript로 블록체인 만들기 강좌

[강좌](https://nomadcoders.co/typescript-for-beginners/)

### 0.2 Setting Typescript Up

1. 타입스크립트는 js파일로 컴파일 후 실행하게 된다. 명령어는 `tsc`이다.
   - 컴파일 옵션은 tsconfig.json에 작성한다.
   - tsc 명령어를 입력하면 js와 js.map 파일이 생긴다.
   - node는 ts파일을 모른다.
2. node 명령어를 만들어 실행한다. 이 때, 컴파일 후 js 파일을 실행해야 한다.
   - package.json에서 start 명령어와 prestart 명령어를 작성하면 start 명령어 실행전에 prestart를 실행한다.
