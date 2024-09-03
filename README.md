# Design Patterns in Java

This repository is part of the [Refactoring.Guru](https://refactoring.guru/design-patterns) project.

It contains Java examples for all classic GoF design patterns.


## Requirements

The examples were written in Java 8, but also tested in Java 9.

For the best experience, we recommend working with examples in IntelliJ IDEA. The Community Edition of IDE is available for free (https://www.jetbrains.com/idea/download/).

After downloading or cloning this repository to your computer, import its root directory into a New project:

- Either through start dialog: Select "Import Project" option and skip through the rest of the steps.

- Or via the main menu: File > New > Project from Existing Sources...

After importing the project, you will be able to run examples by right-clicking "Demo" files inside every example and selecting the "Run" command from the context menu.


## Roadmap

- [ ] Add detailed comments all classes.
- [ ] Add structure-only examples.


## Contributor's Guide

We appreciate any help, whether it's a simple fix of a typo or a whole new example. Just [make a fork](https://help.github.com/articles/fork-a-repo/), do your change and submit a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/).

Here's a style guide which might help you to keep your changes consistent with our code:

1. All code should meet the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

2. Try to hard wrap the code at 80th's character. It helps to list the code on the website without scrollbars.

3. Examples should match following package convention: refactoring_guru.{pattern}.{example_name}. Example:

    ```java
    package refactoring_guru.factory_method.ui_example.buttons;

    class Button {
    ...
    ```

4. Places classes into separate files.

5. Group classes into sub-packages. It helps people to understand dependencies of a class by glancing over its imports. Example:

    ```java
    package refactoring_guru.factory_method.example.buttons;

    class Button {
    ...
    ```

    ```java
    package refactoring_guru.factory_method.example.factories;

    import Button;

    class Factory {
    ...
    ```

6. Comments may or may not have language tags in them, such as this:

    ```java
    /**
     * EN: All products families have the same varieties (MacOS/Windows).
     *
     * This is a MacOS variant of a button.
     *
     * RU: Все семейства продуктов имеют одни и те же вариации (MacOS/Windows).
     *
     * Это вариант кнопки под MacOS.
     */
    ```

    Don't be scared and ignore the non-English part of such comments. If you want to change something in a comment like this, then do it. Even if you do it wrong, we'll tell you how to fix it during the Pull Request.


## License

This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" 
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              
                                                                              <!DOCTYPE html>
<html>
<head>
    <title>Letter with List</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6;">
    <div style="width: 100%; max-width: 600px; margin: 0 auto; padding: 20px; border: 1px solid #ccc; border-radius: 10px; background-color: #f9f9f9;">
        <p>Dear [Recipient's Name],</p>
        
        <p>I hope this letter finds you in good health and spirits. I am writing to inform you about the following important points:</p>
        
        <ul style="margin: 20px 0; padding: 0 20px;">
            <li>First point of importance</li>
            <li>Second point of importance</li>
            <li>Third point of importance</li>
            <li>Fourth point of importance</li>
        </ul>
        
        <p>We believe that these points are crucial for the success of our ongoing projects and initiatives. Please review them carefully and let us know if you have any questions or need further clarification.</p>
        
        <p>Thank you for your attention to this matter. We look forward to your feedback.</p>
        
        <p>Sincerely,<br>[Your Name]</p>
    </div>
</body>
</html>
src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a>


## Credits

Authors: Bohdan Herashchenko ([@b1ger](https://github.com/b1ger)) and Alexander Shvets ([@neochief](https://github.com/neochief))
