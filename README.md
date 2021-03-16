# my_latex_macros

stuff I add to my document preamble to make my life easier.

## usage

heres how to use the commands

### adding figures (path, caption, label)

```tex
\pic{path/to/image.png}{some nice caption text}{fig:image_example}
```

### smaller oscilloscope images

```tex
\oscpic{path/to/image.png}{some nice caption text}{fig:image_example}
```

### images next to each other

```tex
\vspace{2.5mm}
\begin{figure}
    \subpic{path/to/image.png}{some nice caption text}{fig:image_example}
    \subpic{path/to/image2.png}{some nice caption text}{fig:image2_example}
\end{figure}
\vspace{2.5mm}
```

### inserting code

```tex
\inputpython{path/to/code.py}{caption about the script}{code:label}
```

