# Board Game Template

## used

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Firebase](https://firebase.google.com/)
- [recoil](https://recoiljs.org/)
- [styled-components](https://www.styled-components.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [husky](https://typicode.github.io/husky/#/)

## How to use this template?

### create new project

```sh
yarn create next-app -e "https://github.com/prog-learning/board-game-template"
```

### install dependencies

```sh
yarn install
```

### setting room type

`types/index.ts`を自分の作成するゲームに合わせて変更してください。

### create `libs/game`

この主にフォルダ内にゲーム内における動作を定義して、実行を実装してください。
