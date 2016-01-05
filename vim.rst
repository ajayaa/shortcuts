tags
====
* It's better to list out the files to index first and then use
  -L option with ctags.

.. \* to keep rst happy. It could become a common
.. pattern going forward.
* e.g: find . -name "\*.py" > list;ctags -L list
* :ts gives you list of tags.
* :tn to next tag.
* :tp to previous tag
* :tf to first tag
* :tl to last tag
* :tag function_name will take you to tag's definition.
  opposite of <C-]> is <C-t>

tabs
====
* gt goes to next tab
* 5gt goes to 5th tab
* gT goes to previous tab
* :tabnew or <C-T> opens a new tab

buffers
=======
* :1b takes you to first buffer
* :2b takes you to second buffer
* :buffers shows you list of buffers
* :bn takes you to next buffer
* :bp takes you to previous buffer

NERDTree
========

* Press ? inside nerdtree split to get a list of shortcuts.
* :help NERD_tree.txt gives the help text of nerdtree.
* bookmarks are a nice feature in nerdtree.
* To toggle whether to show bookmarks or not type B in nerdtree split.
* To bookmark something type :Bookmark <name> in nerdtree split.
* To open current focused node in a new tab type t there.
* To open current focused node in a split type  i there.
* To keep the focus in Nerdtree type g followed by the command.

append few lines to a file
==========================
* select the lines with v
* then type :'<,'>w! >>file

paste formatted text from clipboard
===================================
* :set paste 
* paste the text you want to.
* :set nopaste

Misc
====
* % inside vim refers to the current file name.
* :set all shows you all the current settings.
* :so $MYVIMRC reloads vimrc file. 
* :scriptnames gives you list of loaded plugins.
* ci" will let you modify content inside "".
