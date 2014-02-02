---
comments: true
date: 2014-02-01 9:30:00
layout: post
slug: welcome-to-my-blog
title: "Welcome to my blog"
summary: "Here is where I'll be talking about my course work, what I discover and what has me stumped. "
image: 'welcome-to-my-blog/tealeaf.jpg'
tags:
- development
- ruby
- tealeaf
---
This is the first post to my [Tealeaf Training] [1] blog.  I'm trying to use GitHub User Pages 
and a Jekyll template for my blog.  So far it's been way too much work. I think I should have 
just used WordPress orTumblr.

#  Playing around with Markdown #

This I'll try a footnote [^1]

now a table...
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| Chapter 1      |  Intro  | 1 |
| Chapter 2      |  Array  | 9 |
| Chapter 3      |  Hash  | 21 |

and some code...
```ruby
  def print_cards cards
    puts "#{cards.count}-card deck"
    cards.each do | rank, suit |
      puts "  #{rank} of #{suit}"
    end
  end
```

[1]: http://www.gotealeaf.com "Introduction to Ruby and Web Development"
[^1]:  Here is the footnote
