```
     _                 _                 _       ~
  __| |_   _ _ __ ___ | |__  _ __   ___ | |_ ___ ~
 / _` | | | | '_ ` _ \| '_ \| '_ \ / _ \| __/ _ \~
| (_| | |_| | | | | | | |_) | | | | (_) | ||  __/~
 \__,_|\__,_|_| |_| |_|_.__/|_| |_|\___/ \__\___|~
                                                 ~
```
It was supposed to be a wiki-style, such as
[Vimwiki](https://github.com/vimwiki/vimwiki) or [Zim - A Desktop
Wiki](http://zim-wiki.org/). But nope.

Dumbnote is just a *personal* Vim plugin for managing notes.

Zim is really great as an organizer, but it is not cross-platform and... well,
it is not Vim.

Vimwiki is a really nice (and huge) project, it offers waaaay more than what
what I need, but since there hasn't been any activities on the project and I was
missing markdown support... decided to take the plunge out.

## Warning

I'm not a programmer/developer/software-engineer/astronaut. 
Feel free to use dumbnote, create issues and whatsoever. I'll be glad to accept
the challenge and look for solutions. If you just give feedback, it will be
really appreciated.

However, if you are really looking for a note taking machine, scroll down for a
list of alternatives.

## File format

It was the main idea of the plugin: a note taker that would support markdown and
let the user decide how to deal with markdown. By default, all notes will have
the `.md` file extension. However, you can use whatever file format you prefer
just by seeting the `g:dumbnoteFileFormat` variable.

I have my own [dumb configs](https://github.com/lsrdg/markdumb.vim) for dealing 
with markdown, and that's why it was important to consider a way to keep the 
filetype as markdown.

Another important point was to make it as seamless as possible to publish the
notes with e.g. [Jekyll](http://jekyllrb.com/).

By not imposing a specific file format, I hope the user will be able to
partially
keep the best of its workflow.

## Collections

Dumbnote.vim borrows the sophisticated term "Collection" from Jekyll. But in
Dumbnote.vim it means a directory with a bunch of `*.md` files.

At the moment, there's a really limited support to multiple collections.

## Basic workflow

To list/view/open your notes, you can use the `:DumbnoteOpenNote ` command 
with `<tab>` completion or with `<c-d>` wild menu. Just open a note and work 
on it. The note doesn't exists? Just give it a name, a file extension and
hit enter. It is the same as using the `:e ` command.

Dumbnote will "autosave" every time you leave insert mode, don't do any anything
for a while etc.

## Another warning

Without time to really learn how to use a new tool and [unable to effectively
use](https://github.com/vimwiki/vimwiki/issues/345)
Vimwiki, Dumbnote is already being tested every day, but it will take quite a
few months until it gets stable and with an useful documentation.

By the way, it won't work on Windows, or at least it was tested only on Linux.

## Alternatives

If you have never used anything to organize your text stuff, you should probably
take a look at:

- Emacs' [Org morde](http://orgmode.org/)
- [Zim - A Desktop Wiki](http://zim-wiki.org/)

If you are here, you are probably looking for something to be used inside Vim.
Here is a list of some plugins, most of them offer more that what I need, that
said my only experience was with Vimwiki. Despite of that, it is nice to have a
list of alternatives to jump to, just in case...

- [Vimwiki](https://github.com/vimwiki/vimwiki)
- [Vim-pad](https://github.com/fmoralesc/vim-pad)
- [Vim-orgmode](https://github.com/jceb/vim-orgmode)
- [VimOrganizer](http://www.vim.org/scripts/script.php?script_id=3342)
- [Vimoutliner](https://github.com/vimoutliner/vimoutliner)

