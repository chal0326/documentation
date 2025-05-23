---
title: Forms Block
---

# Forms Block

Get or fill the value of a form element (input, select, checkbox, and radio).

- **Element selector** <br>
	[Element selector](../workflow/element-selector.md).

## Get form value
Get the value of the form element.

- **Assign to variable** <br>
	Whether assign the value into a [variable](../workflow/variables.md) or not.

- **Variable name** <br>
	Name of the variable to assign the value.

- **Insert to table** <br>
	Whether insert the value into the [table](../workflow/table.md) or not.

- **Select column** <br>
	The column where the value will be inserted.


## Form type

### Text field

- **Value** <br>
	The value for the text field element like \<input> and \<textarea> or an element that has `contenteditable` attribute.

- **Clear form value** <br>
	Clear the value of the text field element before inserting the new one.

- **Typing delay** <br>
	Add delay when inserting each of the characters of the value. When set to 0, the value is inserted at once.

### Select

- **Value** <br>
	The value for the \<select> element. To select a specific option for the select element, you can input it with the value of the option you want to select. You can find the option value by using the [Automa Element Selector](../workflow/element-selector.md) or [Chrome DevTools](https://developer.chrome.com/docs/devtools/).

	![Chrome DevTools](https://s3.ap-southeast-1.amazonaws.com/automa-pub/i/2024/12/02/18e1sr-pr.png)

### Checkbox & Radio

- **Selected** <br>
	Whether the checkbox or radio element is selected or not.

<!--@include: ../parts/blocks-interaction-note.md-->