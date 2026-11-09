# Phrack Articles for <https://phrack.org>

This repository contains PHRACK articles as TXT and as Markdown. Changes to these files will update the articles at <https://www.phrack.org>.

Anyone, but mostly authors, are encouraged to send PullRequests to fix or update an article.

Examples PHRACK articles using MarkDown:
* <https://phrack.org/issues/71/6_md>
* <https://phrack.org/issues/71/7_md>
* <https://phrack.org/issues/71/8_md>

How to add Markdown-beauty to an article:

1. Use [Phrack Markdown Editor](https://phrack.org/md_editor).
2. Edits show up in realtime and gives you a good idea of how the final article will look like.
3. Add Markdown tags, especially syntax highlights, to make the article look more pretty.
4. Create a PR at [phrackzine/articles](https://github.com/phrackzine/articles) for the Markdown article.

---

### Markdown Tips

* You may need to convert some `<` and `&` to `&lt;` and `&amp;`.
* All available Markdowns: [https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)
* All available Syntax Highlights [https://pygments.org/languages/](https://pygments.org/languages/).

### Misc Tips

1. Article artifacts like source go into `/dl/<ISSUE>/<N>/`.
1. PDF files of articles go into `/dl/<ISSUE>/<descriptive-name>.pdf`.

May need to reduce size of PDF:
```bash
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/screen -dNOPAUSE -dQUIET -dBATCH -sOutputFile=output.pdf input.pdf 
```


