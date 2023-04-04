# ChapAnalysis

# install on Betzy 
## https://documentation.sigma2.no/software/userinstallsw/python.html
## https://documentation.sigma2.no/software/userinstallsw/conda.html#installing-with-conda
module avail conda
module load Miniconda3/4.9.2
conda create -n py3 python=3.8
conda init bash
conda activate py3 
conda config --add channels defaults
conda config --add channels bioconda
conda config --add channels conda-forge
conda config --set channel_priority strict
conda install -c bioconda chap
chap -h 
