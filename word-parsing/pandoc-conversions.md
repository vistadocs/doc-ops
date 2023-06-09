## Pandoc Docops
MS Word documents converson to web-friendly forms using pandoc.  
Images stored in external images/media folder; html styles in styles.css file.  
https://blog.atwork.at/post/Convert-documents-with-Pandoc


__Word to github markdown__  
```
pandoc --extract-media=images -s INPUT.docx -t gfm -o OUTPUT.md
```

__Word to html__  
```
pandoc --extract-media=images -s INPUT.docx -t html -c styles.css -o OUTPUT.html
```

__HTML to markdown__
```
pandoc --from html --to gfm  -s -o markdownFile.md  HTMLFile.html
```


__Styles.css__   
```
html {
    line-height: 1.0;
    font-family: sans-serif;
    font-size: 12px;
    color: #1a1a1a;
    background-color: #fdfdfd;
 }
```
