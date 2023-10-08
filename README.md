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

## Step 2 - How to take screenshots
A screenshot is when you capture a part of yourt screen from laptop, desktop or phone.
This is not to be confused with take a photo with your phone.

**DON'T DO THIS**

This is what a screenshot from  your computer should look like

Here are the hotkeys and methods for taking screenshots on both macOS and Windows operating systems:

Mac (macOS):

Capture the Entire Screen:

Press Command (⌘) + Shift + 3. This will take a screenshot of the entire screen, and the image will be saved to your desktop.
Capture a Selected Portion of the Screen:

Press Command (⌘) + Shift + 4. After pressing this hotkey, you can click and drag to select the portion of the screen you want to capture. Release the mouse button, and the screenshot will be saved to your desktop.
Capture a Specific Window:

Press Command (⌘) + Shift + 4, followed by the Spacebar. Then, click on the window you want to capture. The screenshot of that window will be saved to your desktop.
Capture the Touch Bar (on MacBook Pro with Touch Bar):

Press Command (⌘) + Shift + 6. This captures the content displayed on the Touch Bar and saves it to your desktop.
Windows:

Capture the Entire Screen:

Press PrtScn (Print Screen) key. This will capture the entire screen to your clipboard.
Capture the Active Window:

Press Alt + PrtScn. This captures only the active window (the one in focus) and copies it to your clipboard.
Capture a Selected Portion of the Screen (Windows 10 and later):

Press Windows + Shift + S. This will open the Snip & Sketch tool, allowing you to select a portion of the screen to capture. The screenshot will be copied to your clipboard.
Capture a Selected Portion of the Screen (Windows 7 and earlier):

Press PrtScn to capture the entire screen or Alt + PrtScn to capture the active window. Then, open an image editing program like Paint and paste (Ctrl + V) the screenshot. You can then edit and save it.
Capture a Game or Full Screen Application (Windows 10 and later):

Press Windows + Alt + PrtScn. This captures the screen in fullscreen games and saves it as a file in the "Screenshots" folder within the "Videos" library.
Just like capturing a moment with a camera, taking screenshots is a way to capture and remember what's on your screen. These hotkeys make it quick and easy to capture what you need on both Mac and Windows.

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
