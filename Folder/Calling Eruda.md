---
aliases:
  - developer
  - console
  - devtools
  - elements
---
# Panggil Eruda

Ubah syntax kodeblok berikut menjadi `js-engine` untuk pemicu aktif dan undo supaya hanya satu eruda yang muncul.

```js-eng*** unfold file:"call eruda"
javascript:(function () { var script = document.createElement('script'); script.src="//cdn.jsdelivr.net/npm/eruda";
document.body.appendChild(script); script.onload = function () { eruda.init() } })();
```
