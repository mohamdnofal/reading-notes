# FORM

**CHAPTER 7:**

***Types of form control***

*1-ADDING TEXT:*

- A-Text input (single-line).

- B- Password input

- C- Text area (multi-line).

*2- Making Choices:*

- A-Radio buttons

- B-Checkboxes

- C- Drop-down boxes

*3- Submitting Forms:*

- A- Submit buttons

- B-Image buttons

*4- Uploading Files:*

- File upload

**How Forms Work.**

1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, `VB.net`, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received.

**Form Structure:**

1.`<form>`
Form controls live inside a Top of Form
Top of Form
Top of Form
Form controls live inside a `<form>` element. This element should always carry the action attribute and will usually have a method and id attribute too.

- A- Action
Every `<form>` element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

- B- Method
Forms can be sent using one of two methods: get or post.
With the get method, the values from the form are added to the end of the URL specified in the action attribute.
With the post method the values are sent in what are known as HTTP headers.
If the method attribute is not used, the form data will be sent using the get method.

- C- Id

**Text Input:**

The >input< element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

- A- type="text":

    When the type attribute has a value of text, it creates a single-line text input.

- B-Name:

    When users enter information into a form, the server needs to know which form control each piece of data was entered into.

- C-Size:

    The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input (measured by the number of characters that would be seen)

- D-Maxlength:

    You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter.

**Password Input**

1.Type="password":

- When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user's shoulder, they cannot see sensitive data such as passwords.

2.`Name:

- The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.

3.Size, maxlength:

- It can also carry the size and maxlength attributes like the the single-line text input.

**Text Area:**

- Textarea:

    The >textarea< element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag.
    Any text that appears between the opening `<textarea>` and closing `</textarea> `tags will appear in the text box when the page loads.
    If the user does not delete any text between these tags, this message will get sent to the server along with whatever the user has typed. (Some sites use JavaScript to clear this information when the user clicks in the text area.)

**Radio Button:**


- 1- type="radio":

Radio buttons allow users to pick just one of a number of options.

- 2-name:

The name attribute is sent to the server with the value of the option the user selects. When a question provides users with options for answers in the form of radio buttons, the value of the name attribute should be the same for all of the radio buttons used to answer that question.

- 3-Value:

The value attribute indicates the value that is sent to the server for the selected option. The value of each of the buttons in a group should be different (so that the server knows which option the user has selected).

- 4- checked:

The checked attribute can be used to indicate which value (if any) should be selected when the page loads. The value of this attribute is checked. Only one radio button in a group should use this attribute.

**Checkbox:**

- 1-type="checkbox"

 Checkboxes allow users to select (and unselect) one or more options in answer to a question.

- 2-name:

The name attribute is sent to the server with the value of the option(s) the user selects. When a question provides users with options for answers in the form of checkboxes, the value of the name attribute should be the same for all of the buttons that answer that question.

- 3-value:

The value attribute indicates the value sent to the server if this checkbox is checked.

- 4-checked:

The checked attribute indicates that this box should be checked when the page loads. If used, its value should be checked.

**Drop Down List Box:**

A drop down list box (also known as a select box) allows users to select one option from a drop down list. The>select< element is used to create a drop down list box It contains two or more >option< elements.

- A-name:

The name attribute indicates the name of the form control being sent to the server, along with the value the user selected.

- B- >option<

The `<option>` element is used to specify the options that the user can select from. The words between the opening `<option>` and closing `</option>` tags will be shown to the user in the drop down box.

- C-value:

The `<option>` element uses the value attribute to indicate the value that is sent to the server along with the name of the control if this option is selected.

- D-selected:

The selected attribute can be used to indicate the option that should be selected when the page loads. The value of this attribute should be selected.
If this attribute is not used, the first option will be shown when the page loads. If the user does not select an option, then the first item will be sent to the server as the value for this control.
The function of the drop down list box is similar to that of the radio buttons (in that only one option can be selected).

**Multiple Select Box:**


- Size:

You can turn a drop down select box into a box that shows more than one option by adding the size attribute. Its value should be the number of options you want to show at once. In the example you can see that three of the four options are shown.

- multiple:

You can allow users to select multiple options from this list by adding the multiple attribute with a value of multiple

**File Input Box:**

If you want to allow users to upload a file (for example an image, video, mp3, or a PDF), you will need to use a file input box.

- type="file":

This type of input creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.


**Submit buttons:**

- type="submit"

The submit button is used to send a form to the server.
- name

It can use a name attribute but it does not need to have one.

- Value:

The value attribute is used to control the text that appears on a button


**Image Button:**

- type="image"

If you want to use an image for the submit button, you can give the type attribute a value of image. The src, width, height, and alt attributes work just like they do when used with the `<img>` element.

**Button & hidden Controls:**

`<button>`:

- The `<button>` element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.

`<input>`:

- type="hidden"

These form controls are not shown on the page (although you can see them if you use the View Source option in the browser). They allow web page authors to add values to forms that users cannot see.

**Labelling Form Controls:**

`<label>`:

When introducing form controls, the code was kept simple by indicating the purpose of each one in text next to it. However, each form control should have its own`<label>` element as this makes the form accessible to vision-impaired users.

- for:

The for attribute states which form control the label belongs to. Note how the radio buttons use the id attribute. The value of the id attribute uniquely identifies an element from all other elements on a page.

**Grouping Form Elements:**

`<fieldset>`:

You can group related form controls together inside the `<fieldset>` element. This is particularly helpful for longer forms.
Most browsers will show the fieldset with a line around the edge to show how they are related. The appearance of these lines can be adjusted using CSS.

`<legend>`:

The `<legend>` element can come directly after the opening `<fieldset>` tag and contains a caption which helps identify the purpose of that group of form controls.

---

# Lists, Tables & Forms

---
**CHAPTER 14:**

**Boxes:**

Every box has three available properties that can be adjusted to control its appearance:

- 1-***Border:***

    Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

- 2-***Margin:***

    Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes

- 3-**Padding:**

    Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

- 4-***White space & Vertical Margin:***

    The padding and margin properties are very helpful in adding space between various items on the page.

**Border:**

***Border Width:***

- The border-width property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values:

- a-thin.

- b-medium.

- c-thick.

***Border Style:***

You can control the style of a border using the border-style property. 
This property can take the following values:

- a-solid a single solid line.
- b-dotted a series of square dots.
- c-Dashed a series of short lines.
- d-double two solid lines.
- e-groove appears to be carved into the page.
- f-ridge appears to stick out from the page.
- g- inset appears embedded into the page outset looks like it is coming out of the screen.
- h-hidden / none no border is shown.

***Border Color:***

You can specify the color of a border using either RGB values, hex codes or CSS color names.
p.one {
border-color: #0000lll;}

***Shorthand border:***

The border property allows you to specify the width, style and color of a border in one property (and the values should be coded in that specific order).

- Margin:

The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems.

You can specify values for each side of a box using:

1- margin-top

2- margin-right

3- margin-bottom:

 margin-left
You can also use the shorthand (where the values are in clockwise order: top, right, bottom, left):

 margin: 1px 2px 3px 4px;

***Centering Content:***

If you want to center a box on the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto.
In order to center a box on the page, you need to set a width for the box (otherwise it will take up the full width of the page).

***IE6 Box Model:***

- When you specify the width of a box, any padding or margin should be added to the width of it. Internet Explorer 6, however, has a quirk whereby it includes the padding and margins in the width of the box. The way around this is to ensure that you provide a DOCTYPE declaration for the HTML page.

***Change Inline/Block:***

- Display:

The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page. The values this property can take are:

- 1-inline:

This causes a block-level element to act like an inline element.

- 2-block:

This causes an inline element to act like a block-level element.

- 3-inline-block:

This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.

- 4-none:

This hides an element from the page. In this case, the element acts as though it is not on the page at all (although a user could still see the content of the box if they used the view source option in their browser).

***Hiding Boxes:***

- Visibility:

The visibility property allows you to hide boxes from users but It leaves a space where the element would have been. This property can take two values: 

- 1- hidden:

This hides the element.

- 2-visible:

This shows the element.

***Border Images:***

- border-image:

The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.
This property requires three pieces of information:

1- The URL of the image.

2- Where to slice the image.

3- What to do with the straight edges.

***Box Shadows:***

- box-shadow:

The box-shadow property allows you to add a drop shadow around a box.
It must use at least the first of these two values as well as a color:

1- Horizontal offset:

 Negative values position the shadow to the left of the box.

2- Vertical offset:

Negative values position the shadow to the top of the box.

3- Blur distance:

 If omitted, the shadow is a solid line like a border.

4- Spread of shadow:

 If used, a positive value will cause the shadow to expand in all directions, and a negative value will make it contract.

***Rounded Corners:***

- border-radius:

CSS3 introduces the ability to create rounded corners on any box, using a property called border-radius. The value indicates the size of the radius in pixels.