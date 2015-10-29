Commit
======

First, remove the commit on your local repository. You can do this using git rebase -i . For example, if it's your last commit, you can do git rebase -i HEAD~2 and delete the second line within the editor window that pops up. Then, force push to GitHub by using git push origin +master .

The standard reST inline markup is quite simple: use

one asterisk: *text* for emphasis (italics),
two asterisks: **text** for strong emphasis (boldface), and
backquotes: ``text`` for code samples.

Lists and Quote-like blocks
^^^^^^^^^^^^^^^^^^^^^^^^^^^

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.

Definition lists (ref) are created as follows:

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.
   
Quoted paragraphs (ref) are created by just indenting them more than the surrounding paragraphs.

Line blocks (ref) are a way of preserving line breaks:

| These lines are
| broken exactly like in
| the source file.


