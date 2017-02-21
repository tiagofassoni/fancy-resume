A fancy Resume

Fancy resume made with the help of D3

Boring resume made with Markdown and the lovely package markdown-resume (https://github.com/there4/markdown-resume)

For the next time I make such a thing, I really have to switch to LaTeX or some vector drawing program. Turns out the markdown-resume program uses an undocumented superset of Markdown. 

So I had to add the 'pdf' class to the html body tag, after md2resume made its output. Then, since wkhtmltopdf does not behave consistently cross-platform, I had to use the following command on MacOS (because font rendering in Linux is different): wkhtmltopdf  --page-size A4 --disable-smart-shrinking --zoom 2.1 resume.html resume.pdf

Next time, I will just use LaTeX. Or will move directly to a graphic program. Or will do the entire thing in D3. Or, luckily, the AI singularity will have happened, we will switch to a much better allocation scheme than captilism and the entire resumé thing will be as obsolete as the divine right of the kings
