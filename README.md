# colcolor
python script to colorize (shell colors) columns by value

    usage: colcolor [-h] [-H] <filenames>
    
      -h: First line is header. (Tries to autodetect even when not set.)
      -H: Print this help message.
    
    Reads from files (or stdin if missing or '-') and colorcodes each column
    by value.

A picture is really best here:

![An image displaying usage](https://user-images.githubusercontent.com/5131911/172989557-91cfb0bd-f8b9-45a1-b3e6-c303f2253762.png)

Cool bits:
 * Parses and understands k/m/g/t
 * Each column gets its own scaling
 * Makes it much easier to scan lists of numbers (especially when with k/m/g/t units) for "what's big/small"

I haven't bothered with any "installation"; it's a stand-alone (python3) script.

BSD licensed to avoid spreading code without a specified license ;)

Happy to look at pull requests! I've been tinkering with it for years and realized I never "put it out there."

 - Eric
