# TU Berlin Thesis Template

This thesis template is intended to get students writing their theses at the Mobile Cloud Computing chair of Technische Universität Berlin up to speed.
Using LaTeX to typeset your thesis is a crucial step you can take to reduce headaches at the last minute and will make your life very comfortable (or at least as comfortable as someone writing their thesis can be...).
You can use this template as-is for your thesis as we distribute it with a permissible MIT license.
The original template was provided by Felix Moebius, and we have extended it for use by all students.
The content of our template is only for illustrative purposes and does not necessarily reflect the necessary content, detail, structure, or length of a Master's or Bachelor's thesis!

We recommend writing in [Visual Studio Code](https://code.visualstudio.com/) using the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) and [LTex](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) extensions.
For help writing the content of your thesis, please refer to our [thesis tips](https://github.com/3s-rg/thesis-tips).

For your presentation, we provide a PowerPoint template in `presentation.potx`.
If this template does not meet your requirements (different chair, different university, LaTeX user, etc.), please refer to the official university templates before making adjustments.

Please keep these recommendations in mind when writing your thesis and working with this template:

1. There are few official rules for formatting your thesis at Technische Universität Berlin. Our template can serve as a guideline and help you get started, but you are free to make any changes you deem necessary.
1. We recommend using a version control system (such as git) for your thesis. As LaTeX is text-based, you will be able to track and revert changes easily and keep a backup of your work.
1. To make working with your VCS easier, we recommend writing each sentence in your source files on a new line. LaTeX will ignore single newlines, but you can use a double newline to force a paragraph break (don't use `//` to force paragraph breaks).
1. All graphics you include in your thesis should be vector graphics -- this can be achieved by exporting them in PDF format. This is easily possible in both PowerPoint and `matplotlib`/`seaborn`. The benefit is that your file size will be reduced (compared to PNG) while having the highest possible quality for your final document.
1. Use the `booktabs` package for tables and the `subcaption` package for combining multiple figures. See their respective documentation for instructions on their usage.
