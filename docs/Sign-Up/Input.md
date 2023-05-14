---
title: Input
layout: default
parent: Signup
nav_order: 1
---
# Input Component

### Props 

| Prop Name       | type       | required | values                                    |
|:----------------|:-----------|:---------|:------------------------------------------|
| currVal         | `useState` |*         | useState[0]                               |
| changeCurrVal   | `useState` |*         | useState[1]                               |
| errorState      | `useState` |*         | useState[0]                               |
| setErrorState   | `useState` |*         |useState[1]                                |
| inputRef        | `useRef`   |*         | useRef                                    |
| label           | `string`   |          |                                           |
| size            | `string`   |          |default: `regular`, medium,<br> small, tiny|
| error           | `string`   |          |default:`Invalid Input`                    |
| placeHolder     | `string`   |          |                                           |
| fieldLength     | `int`      |          |default:`2`                                |

----
