## Why I build Bitnote
This comic comes from xkcd.

![rtfm](http://imgs.xkcd.com/comics/rtfm.png)

If you are a full-stack engineer, you know why it pains. If you see
programming as a job for raising lives (i guess most of us), you also
know why it pains. If you are a specialist on one  technology and know
all details... Tide will blow old things away, new technology conquers!
You will know why it pains by then.

Although it is information age now, something still doesn't change. If
someone is not famous, it is very hard to find relevant useful
information on internet. However if he is, internet will be full of his
rumors, and gossips. Noises, these are. And you still cannot find
relevant useful information.

Same thing happens to software, to programming. Let's explain it with
the following story.

I am a vim user, but not good at it, just use it sometimes. And more
rarely, i need to copy something between vim clipboard and system
clipboard. The command should be "+yy and "+p, but because i use it
rarely, every time i need it, i google 'vim system clipboard'  to make
sure it is not `+p or +"p. There is no obvious answer in the result
overview page. So i clicked the first link, it's a wiki, jump over the
long narration paragraphs, then find "+p in the bottom of it. 

Normally this should work, and our story ends. I just want to use this
to prove how inefficient i am, or some of us, maybe most of us. But
today is different, What actually happened is, might because I installed
a new OS recently, "+p doesn't work.

I tried a few times, also tried "*p, it doesn't work. Then I google "vim
system clipbord kde"(I am trying Kubuntu), i found a thread in KDE forum
for the same problem. At the bottom of this thread, one enthusiast said
"use vim --version to check your vim, it should has "+xterm_clipboard
support, if not, install vim-gui-common package".

(Use right keywords for searching is a trick, and i am getting used to
it more and more recently. Weird, I am not quite proud of it.)

Then i felt a little annoyed, why the wiki author in the first link
didn't say this. So i read that wiki again, and i was shocked. it says
vim version might have problem in the FIRST paragraph, and provide
solution, which hidden deeply in the MIDDLE of the page. OK i might
exaggerate, but it did come after some complicate paragraphs i will
never read.

"Shame on you" I said to myself, "You should RTFM first".

This happens almost every working hour and every day, even when I am
writing this article. I solved the problem finally, but because i am
LAZY at first, i spend more time to solve it.

If you asked for someone's help, they might help you, then say, you
should RTFM first, or STFW (search web) first. But what actually
happened is, the document is not good, the web is full of outdated
articles, we need to guess what key words might other people use to
describe the problem. If the problem is not important, some of us
might just throw it away then forget it. If we have to solve the
problem, then we might need to fight with document and google, and
finally we solved it. But what's the feeling by then? Thrilled?
Frustrated? Or both.

"Customer's Experience Matters". Managers are saying, designers are
saying. But What about programmers' experience?

What if i have a browser extension, when i search "vim system
clipboard", it shows
```
"+yy for yank and "+p for paste
vim --version should have +xterm_clipboard
More info referrer to Vim wiki(link)
```
besides the normal google results. What if i can just create this memo
by doing some drag and click with mouse? I might be lazy, but i know
if do it one time, there will be no more burden next time, and the
community might benefit from this. Smart lazy people will do the
right choice. 

Then bitnote comes. I wish it can solve the problem above, also i
wish it can solve many other daily problems which programmers will
meet, as a simple way to collect, share, discover knowledge and
experience. I wish it can stand with github and stackoverflow.

It is still under development, and i know except reliability,
performance and experience, i should also consider that:

"I wanna my data back!"
"What is the license? Who owns the data?"
"Privacy! You never care about privacy!"

Laziness is the first step towards efficiency. Now it's time to step
forward.
