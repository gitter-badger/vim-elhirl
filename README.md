# vim-elhirl
Library written in [riml](https://github.com/luke-gru/riml) for use in Vim plugins

elhirl stands for extreme language hacking in riml. Extreme language hacking is my programming style, but this is actually just a VimL library soon to be used by my Vim plugins.

For now, this is just me rewriting my vim-elhiv library into riml. riml is a language that compiles to VimL. I have nothing to do with the riml project, this library is just written in that language. If you think it sounds redundant for me to have both vim-elhiv and vim-elhirl, then you might actually understand both what VimL is and what riml is. Initially, I started out rewriting vim-elhiv to be written in riml without creating a new project. I was going to have both the riml code and the VimL code in the elhiv project. But then I realized it would be more usful to have both. If I find myself writing code in VimL again, and I want to use my library, I don't want to have to communicate with the library using an interface designed by a compiler. That would not be in the spirit of extreme language hacking. The main point of vim-elhiv is to provide an easy, memorable, lookupable way of doing things in VimL.

Installation

I don't recommend it. I'm not even using this yet. I still need to figure out how to integrate this into other plugins, so I don't have a recommended way to install it yet. If you still want to use it, you will have to either compile it and use the .vim files, source these riml files from your riml code, or include these riml files from your riml code.
