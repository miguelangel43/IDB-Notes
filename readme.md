Run these commands on the terminal to convert the notes to the following formats.

To HTML
```
pandoc -s --metadata title="Implementation of Databases Notes"  --toc -o new.html script.md
```

To PDF
```
pandoc -s --pdf-engine=xelatex  --metadata title="Implementation of Databases Notes"  --toc -o new.pdf script.md
```

To DOCX 
```
pandoc -s --metadata title="Implementation of Databases Notes"  --toc -o new.docx script.md
```