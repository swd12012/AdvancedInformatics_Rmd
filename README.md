### Week 2 Lab Exercise

1. To find the Python executable, you insert the command `use_python()`, potentially with the option `required=TRUE`.

2. To find the path to your Python from the shell, you type `which python` into the terminal.

3. `include = FALSE` in that chunk says that the code and ouput are both suppressed, but the code is still evaluated in the document.

4. If the semicolon is removed from the codeblock with `seaborn`, it gives an output `<seaborn.axisgrid.FacetGrid object at 0x7fbdf869c490>` that is no longer suppressed by the semicolon.
My guess is that it might be like a pipe into the `plt.show()` line.