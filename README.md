# files_in_dir_2_txt
Writes the path of all files with a specific ending (*.tif) to a txt-file using only windows cmd.

Open cmd an navigate to the folder containing the files. Than type:
for /r %i in (*.tif) do echo %i >>list_luftbildkacheln.txt
