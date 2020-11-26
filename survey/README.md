# Inclusion Surveys

To edit `ipynb` files, you will need to do the following:

```shell
pip3 install jupyter-lab pandas seaborn matplotlib # might turn this into a requirements.txt file if it gets longer
jupyter-lab
```

You will then be able to open the Jupyter notebooks in your browser. This has been tested on Python 3.9 but should work with earlier 3.x versions.

The way notebooks work is when you run, the charts are embedded as PNGs in the file, so if you make any changes, run then commit. GitHub serves them using nbviewer (albeit with a few restrictions.)

## November 2020

The survey was performed by CultureAmp. CultureAmp don't have an easy export feature, so data was manually entered into CSV files.

- [Demographics](nov2020/demographics.ipynb) - A breakdown of the demographics from the participation of the survey.
- [Questions](nov2020/questions.ipynb) - For each question asked, how many answered 'Favourably', 'Neutral' or 'Unfavourably'.

Questions were broken down further by demographics on CultureAmp's site, but without an extract it would take far too long to input this.