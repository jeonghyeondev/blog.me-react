# blog.me-react

react blog project

open url [http://localhost:3000](http://localhost:3000)

## Blog-frontend

### `yarn start`

## Blog-backend

### `yarn start:dev`

## Extra files

### .prettierrc

```javascript
{
 "singleQuote": true,
 "semi": true,
 "useTabs": false,
 "tabWidth": 2,
 "trailingComma": "all",
 "printWidth": 80
}
```

### jsconfig.json

```javascript
{
 "compilerOptions": {
  "target": "es6"
 }
}
```

### package.json

```javascript
{
  "name": "blog-frontend",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "@testing-library/jest-dom": "^5.11.4",
    "@testing-library/react": "^11.1.0",
    "@testing-library/user-event": "^12.1.10",
    "axios": "^0.21.0",
    "immer": "^8.0.0",
    "koa-static": "^5.0.0",
    "qs": "^6.9.4",
    "quill": "^1.3.7",
    "react": "^17.0.1",
    "react-dom": "^17.0.1",
    "react-helmet-async": "^1.0.7",
    "react-redux": "^7.2.2",
    "react-router-dom": "^5.2.0",
    "react-scripts": "4.0.1",
    "redux": "^4.0.5",
    "redux-actions": "^2.6.5",
    "redux-devtools-extension": "^2.13.8",
    "redux-saga": "^1.1.3",
    "sanitize-html": "^2.2.0",
    "styled-components": "^5.2.1",
    "web-vitals": "^0.2.4"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "proxy": "http://localhost:4000"
}
```

### .env

```javascript
PORT=4000
MONGO_URL=mongodb://localhost:27017/blog
```
