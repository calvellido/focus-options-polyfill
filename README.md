# focus-options-polyfill

JavaScript polyfill for `focusOptions`, an optional property passed to `HTMLElement.focus()` that contains the `preventScroll` boolean, which controls whether the browser should prevent a focused element from being scrolled into view.


## Current support

https://caniuse.com/#feat=mdn-api_htmlelement_focus_preventscroll_option


## Docs

* WHATWG Spec

  https://html.spec.whatwg.org/multipage/interaction.html#dom-focusoptions-preventscroll

* MDN Web Docs - focus

  https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/focus


## Intents to implement

* Chrome/Chromium: Chrome Platform Status issue 734166 - Prevent scrolling in HTMLElement.focus()

  https://www.chromestatus.com/feature/5745122025144320

* Edge: Issue 14314565 - Enable ability to prevent scrolling in Element.focus()

  https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/14314565/

* Firefox: Bug 1374045 - Consider adding support for customizing scrolling behavior with Element.focus

  https://bugzilla.mozilla.org/show_bug.cgi?id=1374045

* Safari: WebKit Bug 178583 - Enable ability to prevent scrolling in Element.focus()

  https://bugs.webkit.org/show_bug.cgi?id=178583


## Dev and testing

To check this polyfill you can do:

```bash
npm run dev
```

to launch a small page that will check browser/polyfill behaviour.
