# Reverie

## What is it ?

**Reverie is my personal blog; it is just that my thoughts wanted a place to live.**
This is where I would be ranting, appreciating, criticisng, fantasizing about stuff that matters to me - Technology, Life and Love.

## What is Jekyll, exactly ?

**Jekyll is a simple, blog-aware, static site generator.**

You create your content as text files (**Markdown**), and organize them into folders. Then, you build the shell of your site using Liquid-enhanced HTML templates. Jekyll automatically stitches the content and templates together, generating a website made entirely of static assets, suitable for uploading to any server.

Jekyll happens to be the engine behind **GitHub Pages**, so you can host your project’s Jekyll page/blog/website on GitHub’s servers for free.

## Installation

Here's a quick guide about how you would be setting up Jekyll locally.

### Requirements

* Ruby version 2.2.5 or above, including all development headers (ruby installation can be checked by running `ruby -v`)
* RubyGems (which you can check by running `gem -v`)
* GCC and Make (in case your system doesn’t have them installed, which you can check by running `gcc -v`,`g++ -v` and `make -v` in your system’s command line interface)

### Install on MacOS

Since I use a Mac, I will be writing the installation process for UNIX systems. But don't worry, almost all the commands will work for Linux systems too. I will mention the commands where they don't work, and will also give the Linux alternative for the same.

* **Ruby**
	Ruby comes pre-installed with all OSX systems. But you can't really work with the system-installed Ruby (access will be denied in many cases). **So we are going to install a personal version of Ruby using Homebrew.**
 
	* But before that, you need to install command-line tools for native extensions : `xcode-select --install`
	* Now run `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ruby`
 	This should install the latest version of Ruby in your OSX.

* **Bundler**
	Bundler is a **package manager** used to install all the dependencies of Jekyll.
	Run : `sudo gem install bundler`
	
