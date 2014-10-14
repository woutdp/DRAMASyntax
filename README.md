# DRAMA Syntax Highlighter
## Overview
This is a DRAMA syntax highlighter for Sublime Text 3. The DRAMA language created by the teachers at KU Leuven is based on assembly. It was designed for learning assembly.

There was no syntax highlighting available so I created my own. The syntax coding isn't 100% correct since it's a bit different than most languages. The syntax coding was created with the monokai color scheme in mind, but will look fine with most color schemes.

## Installation
**Manual:** In linux, execute the following commands:

```
cd ~/.config/sublime-text-3/Packages/
git clone https://github.com/woutdp/DRAMASyntax.git
```

If you're in Windows go to C:/program files/sublime text 3/Packages/ folder and download as ZIP. Change the .zip extension to .sublime-package. This should also do the trick.

**Package Control:** This package will be added to package control in a couple of weeks/days. When you download it through package control you will automatically get the latest updates and patches.

## Usage
After installing, open up a DRAMA file in Sublime and go to View->Syntax and select DRAMA. You should now see the text highlighted in color.

![Example](https://cloud.githubusercontent.com/assets/3637265/4618550/d310c914-530a-11e4-87b2-d8798f6735be.png)

## Update
**Manual:** In linux, execute the following commands:

```
cd ~/.config/sublime-text-3/Packages/
git pull
```

If you're in Windows, reinstall the package by following the install instructions.

**Package Control:** Package control will update automatically.

## Bug report
If you find any bugs, please let me know or post an issue here on github. If you fixed a bug submit a pull request and let me know.
