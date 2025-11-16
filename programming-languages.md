# Details on Programming Languages

I have come into contact with many programming languages in the last twenty five years. In some
cases, I had to learn a language for:
<ul>
<li>a specific course at university,</li>
<li>for a specific project started by another researcher,</li>
<li>as part of a summer school,</li>
<li>to finish a task that was given to me by a senior colleague, or advisor.</li>
</ul>

I have had some contact with matlab throughout the years, but on
principle, I never use a licensed piece of software, if it can be
avoided in any way.

> [!IMPORTANT]
> I would always prefer Free Software to proprietary,
> secret, facy-pants Software. Free in the sense of the [GNU](https://www.gnu.org/) project,
> the [GPL](https://www.gnu.org/licenses/gpl-3.0.html), the Free
> Software Foundation [FSF](https://www.fsf.org/) and
> [fsfe](https://fsfe.org/)

## Ancient History

This is a list of languages that I have come into contact with,
but didn't use beyond that: [java](https://openjdk.org/),
[prolog](https://en.wikipedia.org/wiki/Prolog),
[haskell](https://www.haskell.org/), c++,
[julia](https://julialang.org/), [perl](https://www.perl.org/) 

Some of these I would take steps to avoid: java, c++.

> [!NOTE]
> Of these languages I enjoyed perl the most, with julia a
> close second. I worked with perl longer than the other entries, and
> since perl is ubiquitous, I find it quite useful at times.

## Core Utils Type Languages

> [!WARNING]
> These languages are used in domain specific UNIX tools
> and are commonly used for _one liners_. They are often interactively
> written pieces of code that do a spontaneously encountered task that
> will probably not repeat that often. These aren't always
> considered as full programming languages (even though they are).

I use these often, in scripts or interactively:
- [grep](https://www.gnu.org/software/grep/),
- [awk](https://www.gnu.org/software/gawk/),
- [sed](https://www.gnu.org/software/sed/), even though there are
  (annoyingly) different implementations of `sed`, with
  conflicting flavours of regular expressions,
- [bash](https://www.gnu.org/software/bash/),
   - [POSIX shell](http://gondor.apana.org.au/~herbert/dash/)

> [!IMPORTANT]
> There are often several implementations of these tools, and dialects of
> their respective languages. The provided links are examples of each tool.

> [!TIP]
> Perl fits into this category as well, it can be used like a core util (with the `-p` flag)

## 📊 Scientific Languages

There are several _scientific languages_, used by researchers
for simulation, visualization of data (plots in articles), statistical
analysis, etc. I am fairly proficient in: GNU Octave (similar to
matlab), and R. Julia also fits here, but I have not used it much.

## 📄 Pretty Text

There are also _programming-language-adjacent_ systems of writing: `html`
& `css`, $\LaTeX$, emacs `org-mode`, `markdown` in its various flavors.

Of these I enjoy LaTeX the most. I also like org-mode and markdown.

I am a fan of _regular expressions_, including the `(rx )` variant in
emacs. But, I don't like it that there are so many different
implementations of REs, with their differing optinions on what needs
to be escaped.

The worst example I know is: `[:<:]` (BSD sed) and `\<` (GNU sed) for
left boundary of a word.

## Language Goals

I would like to learn these languages:

- [elm](https://elm-lang.org/)
   + this is a language for one-page web applications
- [elisp](https://www.gnu.org/software/emacs/manual/elisp.html),
   + the lisp flavour in the emacs editor
   + I use it a bit, but I'm not fluent in it
- [zig](https://ziglang.org/)
   + it is a language that belongs into a very particular group of
     langauges that aim to improve on C: [go](https://go.dev/),
     [rust](https://rust-lang.org/), [odin](https://odin-lang.org/), and [D](https://dlang.org/).


In this group of C improvement languages I like zig the most. But the
mere existence of them has lead to lots of cool software being
written, like the nu-shell, redox OS, many command line tools. It's
great that there is so much activity in the area of very fast
(blazingly even) compiled languages.
