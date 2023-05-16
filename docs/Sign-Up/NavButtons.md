---
title: NavButtons
layout: default
parent: Signup
---
# NavButtons Component

## Props 

| Prop Name       | type       | required | values                                    |
|:----------------|:-----------|:---------|:------------------------------------------|
| onNext        | `function` |*         | function()                                  |
| onPrevious    | `function` |*         | function()                                  |
| next          | `String`   |          | default: `Next`, `Submit`                   |
| showPrevious  | `bool`     |          | default: `true`                             |


## What They Do

`onNext` - Function that fires when you click the next button <br>
`onPrevious` - Function that fire when you click the previous button<br>
`Next` - What the text of the Next button will be *Can be any string but should only be Next or Submit* <br>
`showPrevious`- Bool value that triggers whether the previous button will be showing or not <br>

