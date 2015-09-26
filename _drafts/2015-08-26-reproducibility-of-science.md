[Science](http://www.sciencemag.org/content/349/6251/aac4716) 1.

[2012 article](http://pps.sagepub.com/content/7/6/657.short) 2.

> Innovation points out paths that are possible; replication points out paths that are likely; progress relies on both. 

> Humans desire certainty, and science infrequently provides it. As much as we might wish it to be otherwise, a single study almost never provides definitive resolution for or against an effect and its explanation.

2. Open Science Collaboration. "An open, large-scale, collaborative effort to estimate the reproducibility of psychological science." Perspectives on Psychological Science 7.6 (2012): 657-660.

[Nature article](http://www.nature.com/news/scientific-method-statistical-errors-1.14700)

Nuzzo, Regina. "Statistical errors." Nature 506.7487 (2014): 150-152.


## P-hacking

There are [an awful lot of papers that have P-values close to 0.05](http://dx.doi.org/10.1037/a0033242)

Simonsohn, Uri, Leif D. Nelson, and Joseph P. Simmons. "P-curve: A key to the file-drawer." Journal of Experimental Psychology: General 143.2 (2014): 534.

[Media outplays the importance of irrelevant research](http://io9.com/i-fooled-millions-into-thinking-chocolate-helps-weight-1707251800?commerce_insets_disclosure=on&utm_expid=66866090-48.Ej9760cOTJCPS_Bq4mjoww.2)

[Good synopsis of Fisher's original intention](http://www.pnas.org/content/112/37/E5114.full)

## Intrinsic falsibility potential of a hypothesis

[My proposal is based upon an asymmetry between verifiability and falsifiability; an asymmetry which results from the logical form of universal statements. For these are never derivable from singular statements, but can be contradicted by singular statements.](https://en.wikipedia.org/wiki/Falsifiability) - Karl Popper

[Strengthening model refutation](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0138212)

# Workshop

6 / 56 landmark oncology papers confirmed

43 / 67 drug target validation studies failed to reproduce

"Science as a enterprise" - science is built on reproducibility

"Reproducible science acclerates scientific progress" - Bruno Oliviera

Communcication is key - how do you communicate with yourself 6 months ago?

Technology soup (innovation of technologies)

"Use laziness as a virture" and "Don't repeat yourself"


File structures

doc ---
code ---
data-raw ---
data-output ---
tests ---


[Duke Library "Data Management Guide"](http://library.duke.edu/data/guides/data-management)

"Data use" aggreements are like copyrights for data, more like a contract.


# Four facets

1. Executable documentation (literate programming)

	Show the code to display the "providence", how/why it was generated, what you're trying to answer. 
	For example, look at RMarkdown.

2. Naming

	Use ISO 8601 standard for dates (YYYY-mm-dd)
	Make things "self documenting"
	[William Noble 2009 (A quick guide to organizing computational biology projects)](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)

3. Automation

	Use a makefile

4. Disssemination

	Make an archive
	Its shown that papers that share data and archive get more citations

	["A Quick Guide to Software Licensing for the Scientist-Programmer" PLoS Computational Biology](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598) (If you don't say anything, you have ALL rights. If you put a license on it, you can grant rights!)

## My thoughts

Think about the parts of your research are subjective and make them automatic.

## Cool software


### Notebooking software

- Github automatically renders IPython notebooks
- Jupyter is a cool notebooking program for Python/R/Haskell
- Rmarkdown is a cool notebooking program

### Generic repository 

- Dryad
- Figshare
- Zenodo

## Questions

Is there a bunch of examples of Rmarkdown manuscripts and their folder structures?
