# SUBTUBE

![](https://tokei.rs/b1/github/nagy135/tabber?category=code)

Simple script that allows you to collect screenshots of part of screen.

# Explanation
I made this script to steal tabs from youtube videos where actual pdfs are behind pay-wall.
After a while i began organizing my tabs in folder created by this script and use it to store tabs from free sources as well.

# Modes
## single
1. lets you select part of screen
1. asks for **tab name**
1. saves in folder
1. notifies using notify-send

## multiple
1. lets you select part of screen
1. asks for **folder name**
1. using different cli option lets you screenshot the same part of screen multiple times (forward video => screen => repeat)
1. notifies using notify-send
1. optionally you can combine those parts into "pages" (combining multiple pieces on top of the other, so for example 10 screenshots become 3 pages)


# Install
Simply clone repo, make *tabber* executable and run it

# Usage
Script generates files in `~/Documents/Tabs` and example of how it looks is located in **examples**.

```
tabber
```
without any option, asks for **single/multiple** mode and follows dialog as described in "Modes"

```
tabber grab
```
when **multiple** was selected, this allows you to perform screenshots

```
tabber process
```
when **multiple** was selected, this processes screenshotted parts into "pages".
