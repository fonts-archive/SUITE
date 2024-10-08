# 스위트

[배포처 바로가기](https://sunn.us/suite/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SUITE`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'SUITE';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Light.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Light.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Medium.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Medium.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Medium.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Medium.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 600;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-SemiBold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-SemiBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-SemiBold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-SemiBold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Bold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 800;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-ExtraBold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-ExtraBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-ExtraBold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-ExtraBold.ttf') format('truetype');
}
@font-face {
  font-family: 'SUITE';
  font-weight: 900;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Heavy.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Heavy.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Heavy.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/SUITE-Heavy.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/subsets/SUITE-dynamic-subset.css"
  type="text/css"
/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SUITE/subsets/SUITE-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SUITE", -apple-system, BlinkMacSystemFont, "Segoe UI",
  Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
SUITE―스위트는 오픈소스입니다. SIL Open Font License에 따라 개인 또는 기업이 영리적, 비영리적 목적으로 자유롭게 사용할 수 있습니다. 
단, SUITE를 단독 판매하면 안 됩니다. SUITE에 대한 제안 및 문의는 이메일로 보내주세요.
```
