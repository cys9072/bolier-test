# publishing boilerplate (퍼블리싱 보일러플레이트 ver.1)

BoilerPlate 폴더 기본구조

```
Root
|─ assets
    ├── css
    │   └── main.css
    │   └── normalize.css
    │   └── reset.css
    │   └── common.css
    │   └── style.css
    ├── doc
    ├── img
    │   └── (추가폴더 가능)
    │   └── icon (아이콘)
    |        └── favicon.ico
    |        └── icon.png
    |        └── tile-wide.png
    |        └── tile.png
    └- font
├── js
│   ├── main.js
│   ├── plugins.js
│   └── vendor
│       └── modernizr.min.js
├── .editorconfig
├── 404.html
├── README.md
├── robots.txt
├── index.html
```

<br/>
<br/>
<br/>

## 각 파일 설명

[normalize.css](#normalize) <br/>
[main.css](#normalize) <br/>
[reset.css](#reset) <br/>
[common.css](#common) <br/>
[style.css](#style) <br/>
[doc](#doc) <br/>
[main.js](#mainjs) <br/>
[editorconfig](#editorconfig) <br/>
[404page](#404) <br/>
[robot](#robot) <br/>

<br/>
<br/>
<br/>

## Css

> ### normalize
>
> - 브라우저마다 다른 스타일을 가진 요소들을 통합.(ver. 8.0.1)

> ### main
>
> - 기본 타이포그래피 설정 + 원하지 않은 text-shadow 삭제 + 헬퍼 클래스 제공

> ### reset
>
> - 최초 font family 지정
> - 기본 태그 스타일 reset

> ### common
>
> - 변하지 않는 값 지정
> - root에 공통되는 색상, 버튼, 링크, 스타일링 지정

> ### style
>
> - 스타일 작성

<br/>
<br/>
<br/>

## Doc

> ### doc
>
> - 최초 boilerplate 설명 파일, 해당 파일은 삭제 해도 무방

<br/>
<br/>
<br/>

## Font

> ### font
>
> - woff 확장자의 font 파일

<br/>
<br/>
<br/>

## Js

> ### mainjs
>
> - 프로젝트에서 쓰이는 js 파일
>
> ### vendor
>
> - 외부라이브러리 및 프레임 워크 파일이 저장되는 폴더

<br/>
<br/>
<br/>

## Etc

> ### editorconfig
>
> - 다른 IDE나 에디터에 코딩 스타일 유지. 해당 부분은 [플러그인 설치](https://editorconfig.org/#download)가 각 에디터 마다 필요한데, 해당 부분은 굳이 필요하지 않으면 삭제 예정

> ### 404
>
> - 기본 404 페이지, style은 head 안에서 작업 하기로 한다.

> ### robot
>
> - 웹 사이트에 어떤 것을 크롤링 할 수 있는지에 대한 지시.
> - User-agent: \* (모든 웹 로봇에 적용)
> - Disallow: (해당 값이 없으면, 모든 페이지가 크롤링됨, + '/' 넣을 시 모든 페이지가 크롤링 되지 않음)
>
> - [robotstxt.org](https://www.robotstxt.org/)
> - [ `robots.txt` 파일 사용 및 컨트롤](https://developers.google.com/search/reference/robots_txt)

## html5boilerplate 8.0 기반으로 작성. (해당 readme는 전체 파일의 사용법 요약본)

- 원본파일은 [여기](https://github.com/h5bp/html5-boilerplate#quick-start)
