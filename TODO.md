Button Design System
Properties That The Button Component Can Be Passed
Property	Description	Type	Required
disabled	Sets the button to a disabled state	boolean	false
label 	The button text	string	true
onClickHandler	The action to be dispatched onClick	function	true
size	The size of the button	ButtonSizes	false
type	The type of button	ButtonTypes	false
Types
Type	Values	Default
ButtonSizes	SMALL MEDIUM LARGE	MEDIUM
ButtonTypes	PRIMARY SECONDARY TERTIARY	PRIMARY 

<Button
  label="Button">
/>
<Button
  size="small"
  label="Button"
  type="secondary">
/>
<Button
  size="large"
  label="Button"
  type="tertiary">
  onClickHandler={() => alert("You Clicked Me!")}
/>

