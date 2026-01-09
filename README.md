## Hi, I'm Ziyad Rahman!

If you want the highlights, check out my [Resume](https://github.com/ZSR3004/ZSR3004/blob/main/Ziyad_Rahman_Resume.pdf)!

I'm a Junior at Wesleyan University, majoring in Computer Science and Mathematics with a Data Analysis Minor. I'm
interested in software engineering, and my interests lie in two broad categories: developer tools and 
optimizing data analysis pipelines for researchers.

I'm fascinated by the way tools I use daily work, weather that be Git, Compilers, or SQL databases. I love to 
recreate them from scratch in low-level languages like C or Rust with a few major differences to see if I can
improve on their design ([see my current endeavor below!](<README#What I'm Currently Working On>). I also 
really like creating tools that help me in my own workflow, usually as [Neovim](https://neovim.io) plugins
(Yes, I use Neovim btw). Feel free to check out my [Neovim Configuration](https://github.com/ZSR3004/nvim) for 
inspiration!

On the other side, I really like creating programs to boost productivity for others. Most recently, I worked
with the [Mitchel Lab](http://www.jennifermitchel.com), a biology lab at Wesleyan, to improve their video
analysis pipeline through an app called [Cell-Tracking](https://ZSR3004/cell-tracking). We even enabled them
to leverage machine learning in their pipeline which was previously too technical for them to implement.
I had a ton of fun collaborating with friends over Github on this project, and I hope I get the opportunity
to collaborate with them again.

Outside of programming, I'm part of the [Wesleyan University Mock Trial Team](https://wesmocktrial.com).
When I was financial manager, I managed a budget of about $20,000 and organized the team's competition fees,
lodging for away tournaments, and community building events. I've competed with their A-team since my 
freshman year, and I'm really thankful to be part of a community (and show-off my acting chops).


### Here are Some Project Highlights

If you're only visiting for a little, here are two projects you should definitely checkout before you go!


#### [Cell-Tracking](https://ZSR3004/cell-tracking)

This project was in conjunction with [Mitchel Lab](http://www.jennifermitchel.com). I lead a team of 
four undergraduate students to develop a command line interface and web-based app to streamline their 
data analysis pipelines. In short, we enabled them to upload a video and select analysis methods so 
that members of the lab who don't know how to program can access the powerful data analysis abilities 
of Python.

On the technical side, we built out a robust testing-framework using `pytest` and leveraged 
state-of-the-art computer vision algorithms from `open-cv` to create the actual data analysis
capabilities. I'm particularly proud of how we experimented with how machine learning learning
could fit into their analysis which provided a significant increase in the accuracy of the
program. I had a lot fun using `pytorch` and reading academic papers to create new machine
learning applications. 


#### [Arxiv Paper Search](https://ZSR3004/arxiv_paper_search)

[Arxiv](https://arxiv.org) is a database of academic papers. They have papers on any topic you can 
think of. The first step for a lot of researchers is reviewing literature to see what has already 
been covered in their research topic. I wanted to create a tool help my friends who do research with
this step. So, I create the `Arxiv Paper Search`. To use this program, you need to find a paper in
the subject of interest. Then, you can give the program the URL for the paper and it will find 
similar papers based on a tag and text analysis. Using natural language processing methods like
cosine similarity indices, it returns a graph of papers, where the edges tell you how similar 
two papers are to each other.


### What I'm Currently Working On

I'm currently working on two big projects that aren't ready for public viewing yet.

#### Retrieve

The first is `Retrieve` a drop-in Git replacement written in Rust. Git is perhaps one of the most influential programs
ever created, but it has its downsides. In particular, I have three problems with it.

1. [It was originally created as a scripting language](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain), 
and the command line tool was built on top of it. That contributes to sluggish execution on large code bases.

2. The code base is notoriously difficult to read and the inner workings, 
[difficult to understand](https://news.ycombinator.com/item?id=16807206). This is a pretty regular problem with code bases,
but Git's abstraction is so powerful, it's a shame it isn't really represented in the code well (as far as I can tell).

3. This one is a little more of a personal gripe. I'm not a fan of how switching branches work. I REALLY don't like having
to Git stash and pop to switch branches and the alternative, [Git Worktrees](https://git-scm.com/docs/git-worktree) remove 
a lot of the simplicity that makes Git abstraction work.

So, I decided to make `Retrieve` or `Rtv` to fix these issues and add some quality of life features. In short, I'll be
using a similar abstraction to Git, but making the implementation more idiomatic so it's to maintain. Building it 
from the ground up with this intent hopefully makes `Rtv` faster as a version control system when compare to Git. I'll
also be completely reworking the branch management system, so you can hop between branches with uncommitted changes. I
also want this to be usable, so I'll be adding ways to make a Git repository into the `Rtv` equivalent and vice-versa,
so you can also upstream your repository to Github.

#### CDCL SAT Solver (Senior Thesis)

The second project is (hopefully) related to my senior thesis. I'm not 100% sure what I want to do, but I know it will 
revolve around [SAT Solvers](https://en.wikipedia.org/wiki/SAT_solver) and in particular 
[CDLC SAT Solvers](https://en.wikipedia.org/wiki/Conflict-driven_clause_learning). A SAT Solver is basically a fancy 
computer program to solve logic problems. It has a ton of uses from pharmaceuticals to package manager to even AI, 
so there's a lot of interest in optimizing these solvers.

For a very closely related project, check out the [DPPL SAT Solver that I implemented in OCaml](https://github.com/ZSR3004/ocaml-dpll/tree/main).


### Connect With Me
<!-- TODO: Add icons -->

You can connect with me over the following platforms.

<zrahman3004@gmail.com>: This is definitely the best way to get in touch with me!

[LinkedIn](https://www.linkedin.com/in/ziyad-s-rahman/): I'm on here too!

[Mataroa Blog](https://zsr.mataroa.blog): I write essays about software engineering sometimes!
