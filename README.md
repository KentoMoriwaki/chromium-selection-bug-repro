Reproduction of a bug: wrong text ranges are selected with Japanese IME while editing contenteditable including absolute-positioned element

https://user-images.githubusercontent.com/3349436/151820539-f6283866-d042-4cbe-8f6c-ee6594fbc8d9.mov

## Steps to reproduce

1. Visit https://kentomoriwaki.github.io/chromium-selection-bug-repro/
1. Input any word with or without IME anywhere in "Hello"
1. Move cursor to "World" and input any word with IME

---

Reported to https://bugs.chromium.org/p/chromium/issues/detail?id=1292516
