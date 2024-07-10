# 꽃소금체

[배포처 바로가기](https://drive.google.com/drive/folders/1t3sqFePhmNGSFZcoIhvQqlf9r3Xr4Zfs)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Flower Salt`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Flower Salt';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/FlowerSalt.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/subsets/FlowerSalt-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/FlowerSalt/subsets/FlowerSalt-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Flower Salt", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
꽃소금체의 지적재산권은 SALT에게 있습니다. 
‘꽃소금체’는 개인 및 기업 사용자에게 무료 제공되며, 사용자들은 이를 다른이에게 자유롭게 배포할 수 있습니다. 
다만 어떠한 경우에도 복사 또는 배포에 다른 대가를 요구하는 것이 엄격하게 금지되어 있습니다. 
‘꽃소금체’는 지적재산권자 이외의 사용자가 수정해서 배포 및 판매할 수 없으며, 배포된 형태 그대로 사용해야 합니다. 
문의 @djsalt_official(instagram)
```
