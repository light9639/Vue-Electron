# **:zap: Vue-Electron 기본 템플릿**
![다운로드1](https://user-images.githubusercontent.com/95972251/191026345-a470fb05-4201-486b-b35d-1de87ce75425.png)

## :white_check_mark: Vue CLI 설치

- 우선 Vue cli를 전역으로 설치합니다.

- 기존 vue/cli가 @vue/cli로 변경되었기 때문에, 이전 버전이 설치되어 있다면 삭제 후에 설치해 주세요 `npm uninstall vue/cli`

```bash
npm i -g @vue/cli
```

- 설치가 완료되면 다음 명령으로 설치 버전을 확인합니다.

```bash
vue --version
```

## :tada: Vue 프로젝트 생성

```bash
vue create vue-electron
```

- 다음 명령어로 프로젝트를 실행합니다.

```bash
yarn serve
```

- http://localhost:8080으로 접속하면 화면이 나옵니다.

## ✒️ 프로젝트에 Electron Builder 추가

- Electron Builder는 기존 프로젝트를 Electron으로 바꿔주고 쉽게 build를 할 수 있게 돕습니다.<br>
Vue CLI Plugin으로 제공하는 Electron을 사용하면 쉽게 설치가 가능합니다.<br>
https://nklayman.github.io/vue-cli-plugin-electron-builder/

```bash
vue add electron-builder
```

## :rocket: Electron 실행

- 이제 Electron이 추가된 프로젝트를 실행합니다.(package.json 참고)

```bash
yarn electron:serve
```

## 📋 Electron Build
- 다음 명령으로 App을 Build 할 수 있습니다.

```bash
yarn electron:build
```

## **:paperclip: 출처**
- 출처 : https://codegear.tistory.com/83
