# EE381V lecture slide scribes MAKEFILE
# Jimmy Lin <JimmyLin@utexas.edu> 

#######################################################################
# DO NOT EDIT THIS MAKEFILE UNLESS YOU KNOW WHAT YOU ARE DOING. 
#######################################################################	

all:
	pdflatex Slides_16.tex
	pdflatex Slides_16.tex

push:
	git add *.tex *.pdf
	git commit -m "upgrade"
	git push

clean:
	rm -rf *.aux *.bak *.log
