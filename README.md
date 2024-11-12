# Font Awesome Icons for LMS

This repository provides a comprehensive reference for **Font Awesome 4 icons**, tailored for use within LMS (Learning Management Systems) like Moodle. It demonstrates how to integrate Font Awesome icons with Bootstrap components, showcasing examples of using icons in headings, buttons, and tables. The main HTML file, `Font-Awesome-Icons-for-LMS.html`, serves as a guide for using these icons effectively within an LMS environment.

## Features

- **Extensive Icon List**: A table featuring various icons from Font Awesome 4, including each icon’s preview, name, and corresponding HTML code.
- **Accessibility Focus**: Guidance on using `aria-hidden`, `role="img"`, and other attributes to ensure icons are accessible and screen-reader-friendly.
- **Bootstrap Examples**: Demonstrations of how to incorporate icons into Bootstrap-styled elements like buttons and headings.

## Getting Started

1. **Download the HTML File**:
    - Download `Font-Awesome-Icons-for-LMS.html` from this repository to view and interact with the full icon list.
2. Copy the HTML code into your LMS course site using the editor
3. Save and review the page to determine what is accessible from the Font Awesome Icon set.

## Usage

### Adding Icons
1. **Using the `<i>` Element**:
    - Each icon is represented by an `<i>` element with specific classes, such as:
      ```html
      <i class="fa fa-glass" aria-hidden="true"></i>
      ```
2. **Bootstrap Integration**:
    - For consistent styling, wrap icons within Bootstrap components. For example, a button:
      ```html
      <button class="btn btn-primary">
          <i class="fa fa-thumbs-up" aria-hidden="true"></i> Like
      </button>
      ```

### Accessibility Considerations
- **aria-hidden**: Add `aria-hidden="true"` to decorative icons to hide them from screen readers.
- **role="img"**: Use `role="img"` and `aria-label` for icons that convey specific meaning or functionality.

## Resources

- **Font Awesome Documentation**: Visit the [Font Awesome 4.7 documentation](https://fontawesome.com/v4/) for more information on customizing icons.
- **Bootstrap**: Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/) for styling elements in conjunction with Font Awesome.

## MIT License:
Created by: 2024 Corey Stroeder - [Relearning.ca](https://www.relearning.ca)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
* The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
* THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>
