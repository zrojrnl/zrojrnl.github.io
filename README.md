# Dead Simple Blog

I've wanted for a long time to create a simple way of blogging that eschews basically all bells and whistles. Many "flat file" Content Management Systems exist already, as well as "static site generators", but none of these that I looked at were simple enough for my liking.

I don't want to have to install Ruby, or Python, or Composer, or whatever else on a server to run a blog. On the other hand, installing WordPress or one of the other popular PHP-based CMSes for this use case is like hammering in a nail with a sledgehammer.

Many people dislike PHP, and while it has its warts, I like it. I like using (vanilla) PHP simply because it is nearly ubiquitous. Having to install or configure it is often unnecessary because it is usually *already* installed, configured, and running.

I wanted to use plain text files, but some formatting is nice -- Markdown was the obvious solution for this, since it offers quite a lot of options in terms of text formatting, without sacrificing the readability of the plain text itself. I was not keen on adding dependencies but I found [Parsedown](http://parsedown.org) which offers Markdown parsing by including a single PHP file. I can deal with that.

That's really all there is to it -- dead simple PHP-based templating, and Markdown-formatted plain text content.

I know I'm probably forgetting about a million edge cases, but I want to keep it simple. So, we'll roll with this for now and add features as they become necessary.

## Installation

Download the files and upload them to a webserver somewhere. That's it!

## Usage

1. Edit "index.php" with your text editor of choice, and change the variables at the top to your liking.
2. Create text files with a NUMERIC file name, I use YYYY-MM-DD date-based names (e.g. 2018-10-30.txt).
3. Format text files with Markdown, or not. Whatever. ;)
4. If you need to link to image/video/audio/etc. files, you can upload them to the media folder.
4. Upload text files to the "content" directory.
5. You're done!!
