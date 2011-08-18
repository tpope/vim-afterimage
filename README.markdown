afterimage.vim
==============

Edit ICO, PNG, and GIF icons.  No really.  They're converted with
[ImageMagick](http://www.imagemagick.org) to XPM, a plain text image
format with beautiful syntax highlighting in GUI versions of Vim.  Here,
it's easier just to show you:

![Beautiful syntax highlighting](https://raw.github.com/tpope/vim-afterimage/gh-pages/actionshot.png)

And yes, I did say edit.  Obviously you're not going to be uninstalling
Photoshop anytime soon, but for stupid simple tweaks, it gets the job
done.

Oh, and it can also handle PDFs (with
[pdftk](http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/)),
Word Documents (read-only, with [Antiword](http://www.winfield.demon.nl/)),
and Mac OS X plist files.

Installation
------------

If you don't have a preferred installation method, I recommend
installing [pathogen.vim](https://github.com/tpope/vim-pathogen), and
then simply copy and paste:

    cd ~/.vim/bundle
    git clone git://github.com/tpope/vim-afterimage.git

Once help tags have been generated, you can view the manual with
`:help afterimage`.

Contributing
------------

See the contribution guidelines for
[pathogen.vim](https://github.com/tpope/vim-pathogen#readme).

Self-Promotion
--------------

Like afterimage.vim? Follow the repository on
[GitHub](https://github.com/tpope/vim-afterimage) and vote for it on
[vim.org](http://www.vim.org/scripts/script.php?script_id=1617).  And if
you're feeling especially charitable, follow [tpope](http://tpo.pe/) on
[Twitter](http://twitter.com/tpope) and
[GitHub](https://github.com/tpope).

License
-------

Distributable under the same terms as Vim itself.  See `:help license`.
