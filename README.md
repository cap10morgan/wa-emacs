**DEPRECATED:** Wahoo has been merged into [Oh My Fish](https://git.io/oh-my-fish), which already has a great Emacs plugin. This repo will be deleted soon.

# emacs

A port of the oh-my-fish emacs plugin to the [Wahoo Framework](https://github.com/bucaran/wahoo).

From that plugin's README:

This plugin replicates the functionality of the [emacs](https://www.gnu.org/software/emacs/) plugin for [oh-my-zsh](http://ohmyz.sh/).
It is essentially a wrapper around the very useful [emacs daemon](http://www.emacswiki.org/emacs/EmacsAsDaemon) capability.

Below is an extract from the original plugin source file:

"Emacs 23 daemon capability is a killing feature.
One emacs process handles all your frames whether
you use a frame opened in a terminal via a ssh connection or X frames
opened on the same host.
Benefits are multiple

  * You don't have the cost of starting Emacs all the time anymore
  * Opening a file is as fast as Emacs does not have anything else to do.
  * You can share opened buffered across opened frames.
  * Configuration changes made at runtime are applied to all frames."


## Requirements

Emacs 23 or later is required for this plugin.

## Usage

`e [file]` - opens file in emacs buffer in existing frame using emacsclient
`ec [file]` - opens file in emacs buffer in new frame using emacsclient

TODO: Document the rest.
