# Theo's Resume

##	Files

*	[view](index.html)
*	[source](theodore.md)
*	[download](theodorebaschak_resume.pdf)

##	How to use

```
<location-to-markdown-resume>/bin/md2resume html --template swissen theodore.md .
<location-to-markdown-resume>/bin/md2resume pdf --template swissen theodore.md .
mv theodore.html index.html
mv theodore.pdf theodorebaschak_resume.pdf
git add index.html theodorebaschak_resume.pdf
git commit -m 'message'
git push -u origin master
```

## Requires

*	https://github.com/there4/markdown-resume
