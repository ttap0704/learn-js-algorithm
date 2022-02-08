### 프로젝트 폴더 구조

```bash
├── .storybook              // 스토리북 설정
├── node_modules
├── public
│   └── index.html
├── src
│   ├── assets              // image, css, ..etc
│   │   ├── scss
│   │   ├── ...
│   │   └── images
│   ├── components          // form별 컴포넌트 관리
│   │   ├── layout
│   │   ├── button
│   │   ├── ...
│   │   └── common
│   ├── pages               // page별 폴더 관리
│   │   ├── student
│   │   ├── attendance
│   │   └── ...
│   ├── store               // redux
│   │   ├── common
│   │   └── model
│   ├── stories             // 스토리북 컴포넌트 관리
│   ├── tools               // 자주쓰는 함수 및 코드 정리
│   ├── types               // 타입 정리
│   ├── App.tsx
│   └── Index.tsx
├── .eslintrc.js
├── package.json
├── tsconfig.json
├── webpack.config.js
├── prettierrc
└── ...
``` 
