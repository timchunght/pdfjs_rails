# PdfjsRails

This gem allows you to easily integrate mozilla's popular project, pdf.js, into Rails 3/4/4+ app.
https://github.com/mozilla/pdf.js/

PDF.js online demo
http://mozilla.github.io/pdf.js/web/viewer.html

## Installation

Add this line to your application's Gemfile:

  gem 'pdfjs_rails',:git => 'https://github.com/shyammohankanojia/pdfjs_rails.git'

And then execute:

    $ bundle

Or install it yourself locally as:

    $ gem install pdfjs_rails

## Configure the gem

	$ rails g pdfjs_rails:install

	This will copy pdfjs files to your public directory. All the assets have been since updated to version 1.1.1, the newest version of PDF.js as of 2015, May 18th.

	To Display pdf files in your view, embed this iframe in your html page

	<iframe src="/pdfjs/web/viewer.html?file=http://cdn.mozilla.net/pdfjs/helloworld.pdf" style="border: 0" width="50%" height="600" frameborder="0" scrolling="no"></iframe>

	Note: "file=" in the src url is the reference to the pdf.

## Contribution/Credits

This Gem was started by shyammohankanojia

Due to the Gem was deprecated, last commit was 2 years ago, I have decided to update and maintain it.

###TODOS

Update assets in Vendors
