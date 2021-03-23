# 참고 URL : https://tailwindcss.com/docs/guides/create-react-app

# tailwind 설치
    - npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat @tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9

# craco 설치
    - npm install @craco/craco
    - package.json 파일 수정
    - `carco.config.js` 파일 생성

# configuration 파일 생성
    - npx tailwindcss init
    - tailwind.config.js 파일 작성
        - purge: 항목 수정

# Import
    - src/index.css 파일 수정
    - src/index.js 파일 수정