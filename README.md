# focus-options-polyfill

JavaScript polyfill for `focusOptions`, an optional property passed to `HTMLElement.focus()` that contains the `preventScroll` boolean, which controls whether the browser should prevent a focused element from being scrolled into view.


## Docs

* WHATWG Spec

  https://html.spec.whatwg.org/multipage/interaction.html#dom-focusoptions-preventscroll

* MDN Web Docs - focus

  https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/focus


## Intents to implement

      
* Chrome Platform Status - Prevent scrolling in HTMLElement.focus()

  https://www.chromestatus.com/feature/5745122025144320
      
* Edge Bug 14314565 - Enable ability to prevent scrolling in Element.focus()

  https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/14314565/

* Mozilla Bug 1374045 - Consider adding support for customizing scrolling behavior with Element.focus

  https://bugzilla.mozilla.org/show_bug.cgi?id=1374045
