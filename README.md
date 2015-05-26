# code-canon

You've probably seen calls for recommendations for good code to read
and study. When this comes up on aggregators and stackoveflow, the
result is pretty scattershot. Here is my own list, with only code I've
read enough of to judge as interesting in some way.

Canonizing my personal recommendations is a little fraught, since I
know some of the authors and potential authors. Don't take an omission
as much of a signal; we all have finite time, biases, and different
goals and tastes. I'd love to get suggestions, by pull request or
otherwise.

Hopefully I'll add critical remarks, though I'm lazy.

## Counterpoint: other lists, commentary, and tips

(An exception to the my-own-judgement rule.)

* http://www.gigamonkeys.com/code-reading/
* Code Reading: The Open Source Perspective http://www.amazon.com/Code-Reading-Open-Source-Perspective/dp/0201799405
* Ask HN: What source code is worth studying? https://news.ycombinator.com/item?id=7602237
* Ask HN: Good python code for code reading https://news.ycombinator.com/item?id=327710
* https://python-guide.readthedocs.org/en/latest/writing/reading/
* http://programmers.stackexchange.com/questions/38874/where-do-you-go-to-read-good-examples-of-source-code
* http://c2.com/cgi/wiki?TipsForReadingCode
* http://www.quora.com/Where-can-a-programming-beginner-go-to-read-good-code
* http://www.readingcodegood.com/
* http://www.sitepoint.com/reading-ruby-professional-development/

## Peter Norvig

(I've contributed in small ways to several of these.)

* http://norvig.com/paip.html
* Java, Lisp and Python Essays at http://norvig.com/
* iPython notebooks http://norvig.com/ipython/
* "Design of computer programs" on Udacity https://www.udacity.com/course/design-of-computer-programs--cs212
* on CodingBat http://codingbat.com/home/peter@norvig.com

## Barbara Liskov and John Guttag, Abstraction and Specification in Program Development

It's hard to find good models of contracts and invariants driving and
documenting code. This book with its examples taught me this.

## Kernighan and Pike, The Unix Programming Environment.

So old-school it’s practically prehistoric, but the best book I know
on the philosophy of Unix (with the possible exception of ESR’s The
Art of Unix Programming, but that book has hardly any code, and thus
is not so relevant to this question). The longest example is a small
programming language with a compiler and VM interpreter developed in
stages. http://cm.bell-labs.com/cm/cs/upe/

## Kernighan and Plauger, Software Tools in Pascal.

Develops variants of a bunch of classic Unix tools, back before Unix
became
popular. http://www.amazon.com/Software-Tools-Pascal-Brian-Kernighan/dp/0201103427

## Aho, Weinberger, Kernighan, The AWK Programming Language.

Many surprisingly interesting and compact examples. (E.g. a ‘make’ in
half a page of code, an assembler and interpreter, a command-line
database system, etc., etc., etc.) Code is available for download, but
it’s best with the book, which is unfortunately ridiculously expensive
these days. http://cm.bell-labs.com/cm/cs/awkbook/

## Chris Okasaki, Purely Functional Data Structures.

Just what it says, with code in Haskell and ML. Not your parent’s
data-structures book. http://www.cs.cmu.edu/~rwh/theses/okasaki.pdf

## Donald Knuth, Literate Programming.

Has a few extended examples doing neat
things. http://www-cs-faculty.stanford.edu/~knuth/lp.html

## Mark Jason Dominus, Higher-Order Perl.

Ideas from the functional-programming world brought to Perl. The
longest example is a constraint-based domain-specific language for
diagram drawing. http://hop.perl.plover.com/

## James F. Gimpel, Algorithms in Snobol4.

An overlooked classic with lots of fun code in a terribly obsolete
programming language. Emphasis on string processing. Hard to find. The
code is available online but probably hard to get much benefit from
without the book. http://www.amazon.com/dp/0471302139/

## Paul Graham, On Lisp.

Fine examples of the power of Lisp. The best chapters on macros I’ve
seen anywhere. His programming style is not so much to my taste
(favoring too-abbreviated global names, anaphoric macros, etc.) but
still interesting and educational.

http://www.paulgraham.com/onlisp.html

## Peter Seibel, Practical Common Lisp

http://en.wikipedia.org/wiki/Practical_Common_Lisp

## Richard O'Keefe, The Craft of Prolog.

A bit of a grab-bag but a tasteful exposition of ideas and examples
relevant to functional programming as well as Prolog. O'Keefe is
entertainingly opinionated, not unlike Snape at Hogwarts when a
student screws up. http://www.amazon.com/dp/0262150395/

## Leon Sterling (editor), The Practice of Prolog.

A collection of articles, each an extended example, with code, of
making Prolog do something interesting, usually something
AI-ish. Chapters by O'Keefe, Chris Mellish, Sterling,
others. http://www.amazon.com/dp/0262193019/

## P.J. Plauger, The Standard C Library.

A full, portable, clean, reasonably efficient implementation of the
(C89) standard library, with discussion of the design tradeoffs. Includes
the relevant pages from the standard.
http://www.amazon.com/dp/0131315099/

## Edsger Dijkstra, A Discipline of Programming.

Lots of small but nontrivial examples of developing a program and its
proof of correctness
hand-in-hand. http://www.amazon.com/dp/013215871X/

## https://github.com/rswier

I've read https://github.com/rswier/c4 but not
https://github.com/rswier/swieros

# Pending

* kragen-hacks seems to be gone from the web now
* <your favorites here>
