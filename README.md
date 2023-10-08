# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __*Cloud Engineer*__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to repliacte or research issues.

- In order to creates codeblocks in markdown you need to use three backticks ( ``` )
- Not to be confused with quotation ( ' )

```
# Calculates the factorial
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

result = factorial(5)
print("Factorial of 5 is:", result)
```
- When you can you should attempt to apply syntax highlighting to your codeblocks

 ```python
# Calculates the factorial
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

result = factorial(5)
print("Factorial of 5 is:", result)
```
Make note of where the backtick button is located.
It should appear above the tab key.

<img width="200px" src="https://github.com/yeofrancis/github-docs-example/assets/82499575/3972518a-a8a6-4e7b-8566-9d4c4a534561" />

Use codeblocks for both Code and Errors that appear in the console.

```bash
ZeroDivisionError: division by zero
```
```
Error: Missing required argument

  on main.tf line 4, in resource "aws_instance" "example":
   4: resource "aws_instance" "example" {
```
> Here is an example of using codeblocks for an error that appear in Python and Terraform.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extend Markdown to have a list where you can check off items.  [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3
      
## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Heart Eyes | `:heart_eyes:` | :heart_eyes: |

## Step 5 - How to create table

You can use the following markdown format to create tables:
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Heart Eyes | `:heart_eyes:` | :heart_eyes: |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet) 
- [GFM - Tables (with exytensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
