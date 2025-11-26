# Datastar attributes Cheatsheet 

What Datastar attributes can accept values, which don't and which accept sets/pairs (`{ ... }`) and what modifiers can be used. 
See [all modifiers and their tags per attribute](/attribute-modifier-tags-cheatsheet).

## Free attributes

| Attribute | Accepts value | Accepts value sets | Modifiers |
| --- | --- | --- | --- |
| data-attr | ✅ | ✅ | none |
| data-bind | ✅ | ❌ | __case (camel / kebab / snake / pascal) |
| data-class | ✅ | ✅ | __case (camel / kebab / snake / pascal) |
| data-computed | ✅ | ✅ | __case (camel / kebab / snake / pascal) |
| data-effect | ✅ | ❌ | none |
| data-ignore | ❌ | ❌ | __self |
| data-ignore-morph | ❌ | ❌ | none |
| data-indicator | ✅ | ❌ | __case (camel / kebab / snake / pascal) |
| data-init | ✅ | ❌ | __delay (.Nms / .Ns), __viewtransition |
| data-json-signals | ✅ | ✅ (filter object) | __terse |
| data-on | ✅ | ❌ | __once, __passive, __capture, __case (camel / kebab / snake / pascal), __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing), __viewtransition, __window, __outside, __prevent, __stop |
| data-on-intersect | ✅ | ❌ | __once, __half, __full, __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing), __viewtransition |
| data-on-interval | ✅ | ❌ | __duration (.Nms / .Ns / .leading), __viewtransition |
| data-on-signal-patch | ✅ | ❌ | __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-on-signal-patch-filter | ✅ | ✅ (filter object) | none |
| data-preserve-attr | ✅ (space-separated attribute names) | ❌ | none |
| data-ref | ✅ | ❌ | __case (camel / kebab / snake / pascal) |
| data-show | ✅ | ❌ | none |
| data-signals | ✅ | ✅ | __case (camel / kebab / snake / pascal), __ifmissing |
| data-style | ✅ | ✅ | none |
| data-text | ✅ | ❌ | none |

## Pro attributes

| Attribute | Accepts value | Accepts value sets (`{ ... }`) | Modifiers |
| --- | --- | --- | --- |
| data-animate | ✅ | ❌ | none |
| data-custom-validity | ✅ | ❌ | none |
| data-on-raf | ✅ | ❌ | __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-on-resize | ✅ | ❌ | __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-persist | ✅ | ✅ (filter object, optional key via data-persist:mykey) | __session |
| data-query-string | ✅ | ✅ (filter object) | __filter, __history |
| data-replace-url | ✅ | ❌ | none |
| data-rocket | ❌ | ❌ | none |
| data-scroll-into-view | ❌ | ❌ | __smooth, __instant, __auto, __hstart, __hcenter, __hend, __hnearest, __vstart, __vcenter, __vend, __vnearest, __focus |
| data-view-transition | ✅ | ❌ | none |
