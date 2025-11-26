# Datastar attributes Cheatsheet 

These overviews tell wat Datastar attributes accept values, sets/pairs, or none and what modifiers can be used.

## Free attributes

| Attribute | Accepts value | Accepts value sets (`{ ... }`) | Modifiers |
| --- | --- | --- | --- |
| data-attr | yes | yes | none |
| data-bind | yes | no | __case (camel / kebab / snake / pascal) |
| data-class | yes | yes | __case (camel / kebab / snake / pascal) |
| data-computed | yes | yes | __case (camel / kebab / snake / pascal) |
| data-effect | yes | no | none |
| data-ignore | no | no | __self |
| data-ignore-morph | no | no | none |
| data-indicator | yes | no | __case (camel / kebab / snake / pascal) |
| data-init | yes | no | __delay (.Nms / .Ns), __viewtransition |
| data-json-signals | yes | yes (filter object) | __terse |
| data-on | yes | no | __once, __passive, __capture, __case (camel / kebab / snake / pascal), __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing), __viewtransition, __window, __outside, __prevent, __stop |
| data-on-intersect | yes | no | __once, __half, __full, __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing), __viewtransition |
| data-on-interval | yes | no | __duration (.Nms / .Ns / .leading), __viewtransition |
| data-on-signal-patch | yes | no | __delay, __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-on-signal-patch-filter | yes | yes (filter object) | none |
| data-preserve-attr | yes (space-separated attribute names) | no | none |
| data-ref | yes | no | __case (camel / kebab / snake / pascal) |
| data-show | yes | no | none |
| data-signals | yes | yes | __case (camel / kebab / snake / pascal), __ifmissing |
| data-style | yes | yes | none |
| data-text | yes | no | none |

## Pro attributes

| Attribute | Accepts value | Accepts value sets (`{ ... }`) | Modifiers |
| --- | --- | --- | --- |
| data-animate | yes | no | none |
| data-custom-validity | yes | no | none |
| data-on-raf | yes | no | __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-on-resize | yes | no | __debounce (.Nms / .Ns / .leading / .notrailing), __throttle (.Nms / .Ns / .noleading / .trailing) |
| data-persist | yes | yes (filter object, optional key via data-persist:mykey) | __session |
| data-query-string | yes | yes (filter object) | __filter, __history |
| data-replace-url | yes | no | none |
| data-rocket | presence (used as data-rocket:component-name on templates) | no | none |
| data-scroll-into-view | presence | no | __smooth, __instant, __auto, __hstart, __hcenter, __hend, __hnearest, __vstart, __vcenter, __vend, __vnearest, __focus |
| data-view-transition | yes | no | none |
