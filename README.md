
# 01: Code Refractor

The purpose of this project is to understand the value of web accessibility and the usage of semantic HTML. Web accessibility ensures that people with dissabilities can access websites using assistive technoligies like video captions, screen readers, and braille keyboards. Using more specific tags in your HTML makes it easier for you and others undertand your code.

## Task Given

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Solution

To fit the criteria in <code>index.html</code>,

 in line 8:

    <title>Horiseon | Your Marketing Agency</title>

the title was changed to something more meaningful for the user.

in line 13:

    <header class="header">

<code>div</code> was changed to <code>header</code>.

<details>
    <summary markdown="span">Click to show screenshot of HTML code.</summary>
    <img alt="image of HTML code" src="assets/images/Screenshot-1.png">
</details>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Deployed Link

* [See Live Site](#)


## Authors

* **YOUR NAME** 

- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/)
- [Link to LinkedIn](https://www.linkedin.com/)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License 

## Acknowledgments

* Hat tip to anyone whose code, libraries, packages, or UI was used  / inspired from
* Inspiration
* etc
