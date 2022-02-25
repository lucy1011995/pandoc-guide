# How to Convert Mardown to Word

This guide will explain how to convert a markdown file to a word
file.

## Tools

- Pandoc
- terminal
- A markdown file

## Steps

1. **Open** a terminal
2. **Change** the directory in your terminal with the command

    ``` linux
    cd
    ```

3. **Navigate** to your markdown file in the terminal.
4. **Use** the pandoc command to covert your markdown file

    ``` linux
    pandoc -s source_file.md -o destination_file.docx
    ```

    **Note** if you want to convert images as well, used the following command

    ``` linux
    pandoc -s source_file.md -t markdown --extract-media=images -o destination_file.docx
    ```

5. **Clean** up the newly created file.

![cd Command](images/cd.jpg)

Figure 1: Using the cd command to switch directories.

{% include footer.md %}