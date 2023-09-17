# Introduction

This repository contains scripts and jupyter notebooks to generate and analyze
$\beta$-lactamase variants as well as analyze their experimental characterization 
as was done in our recent bioRxiv submission (see citation below):

Download this repository and navigate to the root directory
```
git clone git@github.com:gauthierscience/beta-lac-design.git
cd beta-lac-design
```

Notes:
- Data are available in the `analysis_scripts/data` directory. 
- Analysis scripts are
all provided as jupyter notebooks in the `analysis_scripts` directory. 
- All scripts and data that were used to generate the designs are available in
[ingraham_code_generate_seqs.zip](https://drive.google.com/file/d/1HblnaqjFCSUKItoxahlQaezLE7bYSgZI/view?usp=drive_link)

## Run analysis Scripts

1. **Optional** create a virtual environment for analysis:
```
python3 -m venv ~/env/betalacdesign
source ~/env/betalacdesign/bin/activate
```

2. Install dependencies
```
pip3 install --upgrade pip
pip3 install pandas
pip3 install biopython
pip3 install seaborn
pip3 install openpyxl
pip3 install scikit-learn
pip3 install https://github.com/debbiemarkslab/EVcouplings/archive/develop.zip
pip3 install jupyter
pip3 install lmfit
pip3 install "numpy<1.24"
```

3. Navigate to script directory and launch jupyter notebook
```
cd analysis_scripts
jupyter notebook
```

## Citation

>**Simultaneous Enhancement of Multiple Functional Properties Using Evolution-informed Protein Design.**
>Benjamin Fram<sup>#</sup>,
>Ian Truebridge,
>Yang Su, 
>Adam J. Riesselman,
>John B. Ingraham,
>Alessandro Passera,
>Eve Napier,
>Nicole N. Thadani,
>Samuel Lim,
>Kristen Roberts,
>Gurleen Kaur,
>Michael Stiffler,
>Debora S. Marks,
>Christopher D. Bahl,
>Amir R. Khan,
>Chris Sander,
>Nicholas P. Gauthier<sup>#</sup>,
>bioRxiv 2023.05.09.539914; doi: https://doi.org/10.1101/2023.05.09.539914
>
> \# Correspondence should be addressed to [Benjamin Fram and Nicholas Gauthier](mailto:benjamin.fram.research@gmail.com,nicholas.gauthier.research@gmail.com)
