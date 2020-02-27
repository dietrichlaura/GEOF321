If you have not yet used jupyter notebook (lab), do the following steps to open a jupiter lab script:

open terminal

type "ssh -L 7777:localhost:20054 ldi022@cyclone.hpc.uib.no" (or cycloneL if alias is added in .bash_profile)

go to your working directory,e.g.  "cd /Data/gfi/work/ldi022/GEOF321/Desmond_T255L91/plots"

type either "wget https://github.com/dietrichlaura/GEOF321/blob/master/plot_results.ipynb" to get the file only

or git clone 

type "jupyter-notebook --no-browser --port=200524" to start a jupiter notebook

open a browser (e.g. firefox or safari)

type "localhost:7777/lab" in the command line

open the "plot_results.ipynb" script
