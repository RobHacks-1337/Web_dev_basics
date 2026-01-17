# HTML Notes:
```note
html 
- predifined
- Doesnot recognize vertical space, only recognizes one horizontal space

HTML - HyperText Markup Language
	|-> Link & media
- tags
  |-> empty
	|- <br>,<hr>
	|- <img>,<input>
  |-> container : has opening and closing tag
	|- <html>,<head>,<title>,.......
- attributes
	|- src, href
	|- title,alt,height,width
- Document Object Model (DOM)
  |->html
	|-> head
		|- title
		|- Meta
		|- links
		|- Icons
	|-> body 
		|- heading 
		|- <p>, anchors, formatting(body) 
		|- lists 
		|- image,media
		|- table
		|- forms
```
---

# Some notes to remember:
```
<h-> tag le arko line ma laga pani use hunxa
Lists -> <ul>: unordered list <ol>: ordered list

## Creating a Table:
<table border="1px" cellspacing="0"> used to create a table  
	|-------------|---> creates a border 
		      |---> removes spaces betn cells
<tr>
<td colspan> -> to combine two columns
<td rowspan> -> to combine two rows 
```

## Creating a Form:
```
<fieldset></fieldset>
<form></form>
<legend></legend>
<textarea></textarea> -- displays a text box/area for user to interact
<label> -- If text describes an input use label
<div> -- used to grp for CSS styling 

-- To create buttons to select from
<label> <input type="radio" name="<grp_name>" value="<value1>">Value1 </label>
<label><input type="radio" name="<grp_name>" value="<value2>">Value2 </label>
		|------------|-----------------|-------> for radio buttons
			     |-----------------|-------> to group same category items together
					       |-------> to know which option has been selected after submission (for backend processing)
```
> The label tag makes the text associated with the input tag clickable  
> (Meaning clicking the Value1 also selects that radio button)   
> The name attrib with radio makes sure that only one option can be selected from that group.

```
<input type='Checkbox' name='' value=''> -- for checkbox

-- To create a dropdown options to select from
<select>
	<option value="" disabled selected>guide_text</option>	-- default 
	<option>option1</option>
	<option>option2</option>
	...
</select>
```
