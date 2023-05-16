---
title: TextArea
layout: default
parent: Signup
---

# Textarea Component

## Props 

| Prop Name       | type       | required | values                                    |
|:----------------|:-----------|:---------|:------------------------------------------|
| currVal         | `useState` |*         | useState[0]                               |
| changeCurrVal   | `useState` |*         | useState[1]                               |
| errorState      | `useState` |*         | useState[0]                               |
| setErrorState   | `useState` |*         | useState[1]                               |
| inputRef        | `useRef`   |*         | useRef                                    |
| label           | `string`   |          |                                           |
| size            | `string`   |          |default: `regular`, medium,<br> small, tiny|
| error           | `string`   |          |default:`"Invalid Input"`                  |
| placeHolder     | `string`   |          |                                           |
| fieldLength     | `int`      |          |default:`2`                                |

## What They Do

`currVal` - State variable to store the input as the user modifies it <br>
`changeCurrVal` - State function variable to alter the 'currVal' state variable on Change<br>
`errorState` - State variable that alters whether the error shows or not<br>
`setErrorState`- State function variable to turn the error message on and off<br>
`inputRef` - Reference variable that points to the input box<br>
`label` - Label displayed above the input <br>
`size` - How long the input box will be<br>
`error` - The message that will display if there is an error in the input<br>
`placeHolder` - The placeholder text of input field<br>
`fieldLength` - Minimum number of characters input must be to pass. <br>