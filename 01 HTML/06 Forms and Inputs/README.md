# Forms and Input

## Form

The `<form>` HTML element represents a document section containing interactive controls for submitting information.

It is possible to use the **`:valid`** and **`:invalid`** CSS pseudo-classes to style a `<form>` element based on whether the **`elements`** inside the form are valid.

Example:

```
    <form action="" method="get" class="form-example">
        <div class="form-example">
            <label for="name">Enter your name: </label>
            <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
            <label for="email">Enter your email: </label>
            <input type="email" name="email" id="email" required />
        </div>
        <div class="form-example">
            <input type="submit" value="Subscribe!" />
        </div>
    </form>
```

## Input

The **`<input>`** HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The **`<input>`** element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.

### Types of input tags:-

| Input Type | Description                                              | Example                   |
| ---------- | -------------------------------------------------------- | ------------------------- |
| text       | Single-line text input field.                            | `<input type="text">`     |
| password   | Single-line password input field (characters masked).    | `<input type="password">` |
| email      | Text input specifically for email addresses.             | `<input type="email">`    |
| search     | Text input for search box.                               | `<input type="search">`   |
| number     | Text input that accepts only numeric values.             | `<input type="number">`   |
| checkbox   | Checkable box allowing multiple selections.              | `<input type="checkbox">` |
| radio      | Checkable button allowing single selection from a group. | `<input type="radio">`    |
| date       | Input field for selecting a date.                        | `<input type="date">`     |
| time       | Input field for selecting a time.                        | `<input type="time">`     |
| color      | Input field for selecting a color.                       | `<input type="color">`    |
| file       | Input field for uploading files.                         | `<input type="file">`     |
| range      | Input field for selecting a value from a range.          | `<input type="range">`    |

### Attributes of an input element:-

| Attribute    | Description                                                                         | Example                               |
| ------------ | ----------------------------------------------------------------------------------- | ------------------------------------- |
| type         | Specifies the type of input element                                                 | `<input type="text">`                 |
| name         | Name of the input element                                                           | `<input name="username">`             |
| value        | Initial value of the input element                                                  | `<input value="John Doe">`            |
| placeholder  | Placeholder text in the input field                                                 | `<input placeholder="Email">`         |
| required     | Specifies whether input is required                                                 | `<input required>`                    |
| disabled     | Specifies whether input is disabled                                                 | `<input disabled>`                    |
| readonly     | Specifies whether input is readonly                                                 | `<input readonly>`                    |
| size         | Specifies the visible width of input                                                | `<input size="30">`                   |
| maxlength    | Maximum length of input value                                                       | `<input maxlength="50">`              |
| minlength    | Minimum length of input value                                                       | `<input minlength="5">`               |
| pattern      | Specifies a regex pattern for validation                                            | `<input pattern="\d{3}-\d{2}-\d{4}">` |
| autofocus    | Specifies that the input element should automatically get focus when the page loads | `<input autofocus>`                   |
| checked      | Specifies whether a checkbox or radio button is initially selected                  | `<input type="checkbox" checked>`     |
| autocomplete | Specifies whether input should have autocomplete enabled                            | `<input autocomplete="on">`           |
| form         | Specifies the form the input element belongs to                                     | `<input form="form1">`                |

## Label element

The `<label>` HTML element represents a caption for an item in a user interface.
You pass the id of a tag in the for attribute in the `<label>` tag to connect both of them.

Example:-

```
<label for="email">Email</label>
<input type="email" id="email" name="email" placeholder="xyz@gmail.com">
```

## Semantic Input elements

**_Note:- These semantic input elements will also contain the attributes of the input elements along with som of its own attributes_**

- **`textarea`**:- textarea is used to take a large amount of textual data from the user.

```
   <textarea></textarea>
```

- **`select`**:- select elements is like a dropdown that contains a lot of options to select from. It contains more elements to work with.

  - **`options`**:- Contains a value and shows the options to the user.

    ```
    <!-- size attribute to show number of options at a time -->
    <!-- multiple attribute if enabled will allow user to select multiple options with control click -->
    <select size="size" multiple>
            <options disabled>Default Info</options>
            <options value="data">Info</options>
    </select>
    ```

  - **`optgroup`**:- To seperate the options into different groups. It has a label attribute to show a heading to the user.
    ```
    <select>
            <options disabled>Default Info</options>
            <optgroup label="label">
                <options value="data">Info</options>
                <options value="data">Info</options>
            </optgroup>
            <optgroup label="label">
                <options value="data">Info</options>
                <options value="data">Info</options>
            </optgroup>
    </select>
    ```

- **`button`**:- button element is more of an effective way to make buttons rather than using the `input` element.

```
   <button type="submit">Click</button>
   <!-- types :- submit | reset | button -->
```
