---
layout: post
category: chsc
title: برگه رمز دستور top
date: '2016-04-06 21:35'
published: true
---
## مقدمه

h راهنما

q خروج از برنامه.

## پیمایش

کلید های Up و Down برای حرکت بین فرآیند ها و کلید های PageUp و PageDown برای حرکت بین صفحه ها.

کلید های Left و Right برای حرکت به صورت افقی بین فرآیند ها.

Shift+c در لیست فرآیند های index را نمایش می دهد.

## Sorting

Shift+p مرتب سازی بر اساس مصرف cpu

Shift+m مرتب سازی بر اساس memory

Shift+r مرتب سازی برعکس

برای مرتب سازی بر اساس هر فیلد ابتدا کلید f را فشار می دهیم.

سپس از منو باز شده field to sort on را انتخاب می کنیم

سپس کلید s را برای خروج فشار می دهیم.

## Searching

Shift+l جست و جو

o ایحاد فیلتر مانند {field name}{comparator}{value}. برای مثال, نمایش فرآیند های ایجاد شده تویط کاربر USER=eric.

Ctrl+o نمایش فیلتر فعلی.

= پاک نمودن تمام فیلتر ها.

## دیگر موارد

m switches memory views between the list of metrics and graph view.

k kill a process

d set the refresh rate (in seconds)

Shift+w saves the settings you've configured while running top to a file (.toprc) so they persist next time you use it.

Shift+e toggle the scale of memory metrics (between kilobytes and megabytes etc.) in the system memory summary, and e toggles the scale of memory metrics in the process list. The default is kilobytes, I find megabytes a useful level.

### منبع

<a href="https://gist.github.com/ericandrewlewis/4983670c508b2f6b181703df43438c37">gist</a>
