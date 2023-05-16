---
title: CheckBox
layout: default
parent: Signup
---
# Zen Payments CheckBox Component



## Props 

| Prop Name       | type       | required | values                                    |
|:----------------|:-----------|:---------|:------------------------------------------|
| currVal         | `useState` |*         | useState[0]                               |
| changeCurrVal   | `useState` |*         | useState[1]                               |
| errorState      | `useState` |*         | useState[0]                               |
| inputRef        | `useRef`   |*         | useRef                                    |
| label           | `string`   |          |                                           |
| error           | `string`   |          |default:`"Invalid Input"`                  |


## What They Do

`currVal` - State variable to store the check value <br>
`changeCurrVal` - State function variable to alter the 'currVal' state variable onCheck <br>
`errorState` - State variable that alters whether the error shows or not<br>
`inputRef` - Reference variable that points to the input box<br>
`label` - Label displayed above the input <br>
`error` - The message that will display if there is an error in the input<br>
