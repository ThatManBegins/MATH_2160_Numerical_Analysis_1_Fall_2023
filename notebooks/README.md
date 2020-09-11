# Pluto notebooks to accompany course notes

To install Julia, please visit the [JuliaLang/Downloads](https://julialang.org/downloads/) page.

**Pro tip:** platform-specific [instructions](https://julialang.org/downloads/platform/) can help you with post-installation conveniences such as being able to launch Julia by typing `julia` in the terminal.

Julia consists of a `Base` library and is also shipped with a *standard set of libraries*. One example of these is `LinearAlgebra`.

To use one of the standard libraries, just type `using LinearAlgebra`, for example, at the `julia>` prompt. To see what a package contains, type `LinearAlgebra.<TAB>`. This will show you all the types and functions that are declared within.

To add packages from the `GitHub` ecosystem, switch from execution mode (`julia>`) to package mode (`(@v1.5) pkg> `) by typing `]`. Add [Pluto.jl](https://github.com/fonsp/Pluto.jl) by typing `add Pluto` followed by `enter`. This may take a while as it initializes your package environment for the first time. To exit package mode, press `backspace`.

To use `Pluto`, type `import Pluto; Pluto.run()`. This will open the `Pluto` landing page in your default browser (at the local web address `http://localhost:1234`). Here, you can take a look at a few sample notebooks, start a new notebook, and even open a notebook that's hosted on the Internet by pasting the link in the `Open` box.

For a short YouTube video that shows these steps, please see [here](https://m.youtube.com/watch?v=OOjKEgbt8AI).

Our Pluto notebooks can also be viewed *statically* by downloading the PDF file or by using `GitHub`'s [HTML preview
](https://htmlpreview.github.io):

- [Introduction.jl](https://htmlpreview.github.io/?https://github.com/MikaelSlevinsky/MATH2160/blob/master/Notebooks/Introduction.jl.html)