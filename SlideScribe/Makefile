# EE381V Scribble MAKEFILE
# Jimmy Lin <JimmyLin@utexas.edu> 
# David Inouye <davidinouye@gmail.com>
# Vutha Va <vutha.va@utexas.edu>

#######################################################################
# DO NOT EDIT THIS MAKEFILE UNLESS YOU KNOW WHAT YOU ARE DOING. 
#######################################################################	


all:
	pdflatex LSO_Sanghavi_Lec07.tex
	pdflatex LSO_Sanghavi_Lec07.tex

push:
	git add LSO_Sanghavi_Lec07.tex LSO_Sanghavi_Lec07.pdf Makefile
	git commit -m "upgrade"
	git push

clean: 
	rm *.log *.toc *.nav *.aux *.out *.snm
