# Web Development for Beginners

## Lesson 1.0: Git & Introduction HTML

### Table of Contents

1. Introduction to HTML
   - Structure of an HTML Document
   - Basic HTML Tags
   - HTML Attributes
2. Introduction to Git
   - Setting up Git
   - Basic Git Commands
   - Working with Repositories

## Section 1: Introduction to HTML

HTML (HyperText Markup Language) is the standard language for creating web pages. It is used to describe the structure of web pages using markup.

### Structure of an HTML Document

An HTML document is structured as follows:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
    <a href="https://www.example.com">This is a link</a>
</body>
</html>
```

### Basic HTML Tags

Here are some basic HTML tags you will frequently use:

- `<html>`: Wraps the entire document.
- `<head>`: Contains meta information and links to external resources.
- `<title>`: Defines the title of the page.
- `<body>`: Contains the content of the page.
- `<h1>`, `<h2>`, ..., `<h6>`: Heading tags, ranging from largest to smallest.
- `<p>`: Paragraph tag.
- `<a>`: Anchor tag, used to create hyperlinks.
- `<img>`: Image tag, used to embed images.

Please find more HTML tags in our [HTML Tags CheetSheet](./htmlcheatsheet.pdf)

### HTML Attributes

HTML elements can have attributes to provide additional information. For instance:

```html
<a href="https://www.example.com" target="_blank">Open link in a new tab</a>
<img src="image.jpg" alt="An example image" width="500" height="300">
```

## Section 2: Introduction to Git

Git is a distributed version-control system used to track changes in source code during software development. It helps coordinate work among multiple developers.

### Setting up Git

To start using Git, you need to install it on your system. Follow the [official documentation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for installation instructions.

### Basic Git Commands

Here are some basic Git commands you will frequently use:

- `git init`: Initializes a new Git repository.
- `git clone [URL]`: Clones an existing repository from the specified URL.
- `git add [file/directory]`: Adds files or directories to the staging area.
- `git commit -m "[message]"`: Records changes to the repository with a message describing the changes.
- `git push [remote] [branch]`: Pushes changes to the specified remote repository and branch.
- `git pull [remote] [branch]`: Pulls changes from the specified remote repository and branch.

### Working with Repositories

To create and work with repositories, follow these steps:

1. **Initialize a Repository**: Create a new repository with `git init`.
2. **Add Files**: Add files to the repository with `git add`.
3. **Commit Changes**: Commit your changes with `git commit -m "Your message here"`.
4. **Remote Repository**: If working with a remote repository, set it up using `git remote add origin [URL]`.
5. **Push Changes**: Push your changes to the remote repository with `git push origin master`.

---

We hope this documentation will assist you in your learning process. Happy coding!