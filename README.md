# gedit-jade

## Installation

 Download the language-spec:

      mkdir -p ~/.local/share/mime/packages
      mkdir -p ~/.local/share/gtksourceview-3.0/language-specs
      wget https://raw.github.com/lbdremy/gedit-jade/master/jade.lang -O ~/.local/share/gtksourceview-3.0/language-specs/jade.lang

 Update the mime database:

      cd ~/.local/share
      update-mime-database mime

 Enjoy Jade syntax highlighting in gedit3!

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
