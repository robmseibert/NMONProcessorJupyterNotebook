# NMONProcessorJupyterNotebook
IPython Notebook for replacing Nmon Processor VB Script
The Ipython Notebook, now know as Jupyter notebooks are a great way to share scripts and programs with others.

To run the notebook edits must be made to enable the path to your nmon_output dir as well as placing a local copy of 
"nmon analyser v34a-batch.xlsm" (hint first save a copy of "nmon analyser v34a-batch.xls" as "nmon analyser v34a-batch.xlsm")

Modify a local copy of collect_nmon.sh to dump the nmon files to your nmon output dir and then leave them there after processing.

Of course the analyser will operate on the nmon files that the collect_nmon.sh script has already placed in your nmon_output dir.

sample running of modified collect script:
/home/<eid>/collect_nmon.sh cvdsvc 01/25/2018 11:55:27 - 01/25/2018 13:25:17 'Z:\nmon_output' 
