# A letter form in latex for German bureaucracy

### Backgrounds

When I first moved to Berlin in 2013, what impressed me most was how romantic German bureaucracy is.
He (German bureaucracy) consistently asks you to write a love letter to him with your handwritten signature!
My health tracker statistics says that I have written for example around 11 letters this year for him - writing a letter to him always make my heart rate soar, hopefully not due to stress but out of my love.

As many lovers do, German bureaucracy can be often demanding.
For example scanned signatures are not allowed and therefore sending your love letters via email should be out of the question.
You should print out all your love letters in a perfect format so that his address can be nicely displayed in the window of envelopes.

As usual my nerdy nature of de-romanticizing everything allowed me to write a <img src="https://render.githubusercontent.com/render/math?math=\LaTeX"> form of these letters.
I automatized formatting so that I write a single love letter faster.
Therefore I can write him more often, yet each letter still looks good.
Yes, good looking always helps, when it comes to a love letter.

### How to write your own letter

- Install `texlive` or other package for `pdflatex`. Writing love letters cannot be ever easier with the help of <img src="https://render.githubusercontent.com/render/math?math=\LaTeX">.

- Clone my repo: The best ingredient of earning his heart.
```
    $ git clone https://github.com/hahey/german-bureaucratic-letter-in-latex.git
    $ cd german-bureaucratic-letter-in-latex`
```

- Modify the source code in `loveletter_in_german.tex` with your best sincerity. For our lazy Expat lovers, if you are unsure what to write, you can always get some inspiration if you type a keyword `Musterformular` together with the topic that you are concerned in Google.

  For example, if you want to get a therapy due to your traumatized relationship with your home Internet,
  you can type `<your_internet_provider> Kündigung Musterformular`.

- Run `pdflatex loveletter_in_german.tex`. Check out your perfect-looking love letter `loveletter_in_german.pdf` with your favorite pdf viewer.

- If you are satisfied with the pdf view, you can print it out, put your handwritten signature on it, fold it carefully (direct under `sehr geehrte Damen und Herren` is a good place to fold), go to your favorite `Deutsche Post` office and send it with your love. Don't forget `Einschreibung`.

### A better solution

This repository was first created for my own use and for fun. Nevertheless this is quite a serious problem and many people have been already agonizing with it for long time. Therefore it is important to notice that a more serious and also more proper way to solve this problem is to use <img src="https://render.githubusercontent.com/render/math?math=\LaTeX"> package `dinbrief`: in [CTAN](https://ctan.org/pkg/dinbrief?lang=en) and in [Overleaf](https://www.overleaf.com/latex/templates/dinbrief-package-example/jbyvfkykhqvd).
