---
layout: material
title: "About efficient Googling"
date: 1969-12-28 00:05:00 +0200
permalink: "/about-googling/"
tag: info-eng
---

This course contains several exercises, where you are asked to find on the Internet how to do a specific task of use a specific program. Independently searching for information on the Internet is an indispensible part of a programmer's job. No one really expects you to remember the syntax of all the commands and methods you need, but you are expected to be able to find the information efficiently, on your own. 

Here are some tips on how to Google answers for programming problems:

## Use English.

English is the primary language of programming, and so you should see more results, and thus it should be easier to find reliable sources.

## You can only use key words if you wish.

Nowadays Google is quite good at interpreting complete sentences. However, sometimes a full sentence may distort the results, as it contains many irrelevant words. You can also just use key words in your searches, like  "Ubuntu command line move to folder" instead of "How to move to a folder in Ubuntu command line". 

## Use context words.

If you're looking for an answer to a programming problem, it's a good idea to start with the language name. On this course, especially in the first part, you might want to start with the name of the operating system: Unix or Linux. 

## Check several sources if possible.

When it comes to programming, oftentimes it is easier to find answers from fellow programmers on the Internet instead of the official documentation. Obviously the official docs are always the best source for information, but if none are available, or you don't understand them, the best way to be sure of the reliability of an answer is to check as many sources as possible. However, it is good to know that sometimes information circles around the Internet, meaning that several places have gotten their information from the same, erronous source.

## Use <a href="https://stackoverflow.com/">StackOverflow</a>.

StackOverflow is a forum named after an error message, and created as a support channel amongs programmers. It is extremely popular, and often appears in Google results when searching for programming related issues. You don't need an account in order to browse the answers. However, there are a few things you should know about StackOverflow: Firstly, users can vote answers up and down, based on their correctness. The more an answers has up votes, the higher it will be displayed on the page. In addition, the person who asked the question can mark an answer as "accepted/best answer". This means that it solved their original problem. Accepted answers are displayed first, with a green check mark on their left side. Neither the amount of upvotes nor the "accepted" status guarantees that the answer is completely correct, but they definitely help filtering out the most useless ones.

<figure class="stackoverflow-example">
<img alt="Stackoverflow example answer" src="/assets/exit_vim.png">
<figcatpion>A highly upvoted and accepted answer in StackOverflow.</figcatpion>
</figure>


## Use the proper Google search syntax.

Google actually supports a variety of different search operators. Using a hyphen ("-") in front of a word will filter out irrelevatn words. For example, if you are searching for something related to the programming language Python, (and your search is history is not filled with programming related searches), it might be a good idea to search for "python -snake" for optimal results. If you want to search for a specific sentence, use quotation marks around it. You can find more info [here](https://support.google.com/websearch/answer/2466433).

## Make use of error messages.

If your problem relates to a specific program, you will usually be shown some error message. Error messages are extremely valuable when debugging, as they are in fact designed to give out useful information about a specific problem. First of all, **make sure to read the error message throughoutly yourself**, as they may be quite easily understandable, depending on the program. However, if you don't understand the message or the problem, you can simply Google the error message itself -- this will usually take you to GitHub, where someone has created an issue of the problem. Make sure to remove all identifying aspects of the message, such as file paths, as they will distort the search results. Try to find the essential part of the error message, that you think other people might have searched for as well.

## Find similar problems.

In some cases you will not find a direct answer to your problem on the Internet. Then you might be able to divide the problem into subproblems, and search for answers to each of them. In addition, note that the solution to your problem might be found from a seemingly unrelated answer. When browsing the search results, always start by reading the question, and ask yourself whether their situation corresponds to yours in any way.
