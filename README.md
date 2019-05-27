# How to generate a PDF

On linux I use `pandoc` and it works pretty well.

```
pandoc -f commonmark -o output.pdf cv_slamontagne_fr.md
```

## Manipulate margins

The default PDF output seems to be configured with very big margins. You can easily change this by adding the following options:
* ```-V geometry:margin=1in``` or 
* ```-V geometry:"top=2cm, bottom=1.5cm, left=1cm, right=1cm" ```

You can find more informations in the [official documentation](https://pandoc.org/faqs.html#collapse-how-do-i-change-the-margins-in-pdf-output) 
