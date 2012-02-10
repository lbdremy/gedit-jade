# gedit-jade

## Installation

### For Gedit2: Local or global installation

 Installation based on the user

```
mkdir -p ~/.local/share/mime/packages
mkdir -p ~/.local/share/gtksourceview-2.0/language-specs
wget https://raw.github.com/lbdremy/gedit-jade/master/jade.lang -O ~/.local/share/gtksourceview-2.0/language-specs/jade.lang
```

 Global installation
 
```
sudo mkdir -p /usr/share/mime/packages
sudo mkdir -p /usr/share/gtksourceview-2.0/language-specs
sudo wget https://raw.github.com/lbdremy/gedit-jade/master/jade.lang -O /usr/share/gtksourceview-2.0/language-specs/jade.lang
```
### For Gedit3: Local or global installation
 
 Installation based on the user

```
mkdir -p ~/.local/share/mime/packages
mkdir -p ~/.local/share/gtksourceview-3.0/language-specs
wget https://raw.github.com/lbdremy/gedit-jade/master/jade.lang -O ~/.local/share/gtksourceview-3.0/language-specs/jade.lang
```

 Global installation
 
```
sudo mkdir -p /usr/share/mime/packages
sudo mkdir -p /usr/share/gtksourceview-3.0/language-specs
sudo wget https://raw.github.com/lbdremy/gedit-jade/master/jade.lang -O /usr/share/gtksourceview-3.0/language-specs/jade.lang
```

 Restart gedit. Enjoy Jade syntax highlighting in gedit! 

## Highlight support for:

 * Tag
 * Tag Text
 * Comments (inline-only)
 * Nesting
 * Attributes
 * Doctypes
 * Filter
 * Code

## Community TODO's:

 * Block comment
 * Block expansion

Your contributions are appreciated!
