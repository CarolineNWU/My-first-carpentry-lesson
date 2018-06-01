---
title: "Introduction to markdown"
teaching: 30
exercises: 10
questions:
- "What is markdown?"
- "How do I create a list?"
- "How do I create aa figure"
objectives:
- "Know what markdown is"
- "Know how to insert list"
- "Know how t insert figures"
keypoints:
- "Markdown is a mark up language that can be concerted to HTML."
- "You use `-` to start a list."
- "You use `![legend](/fig/file.jpg)" to insert a figure."
---
Markdown is a markup language that got very popular in the web.
You can have lists in Markdown

Lists starts after an empty line
with lines where the first character is `-`, `+` or `*`,
For example
a list of fruits is

- apple
- banana
- oranges

you can use `+` for list and it doesn't matter for Jekyli
+ apple
+ banana
+ oranges

You can have numbered list as well. For numbered list you start the line with a number followed by a dot. For example,

1. Caroline's workshop
1. Library Carpentry workshop
1. Bring your lesson workshop

You can add emphasis on some words or expressions by using `*` or `**` around the word or expression.
`*` makes the text to be in italic,
for example, *this is a italic text*,
and `**` make the text to be in boldface,
for example, **this is a boldface text**,

For preformatted text, you use backtick.
{% include links.md %}
