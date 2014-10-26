# Large scale optimization lecture 07 scribe MAKEFILE
# Jimmy Lin <JimmyLin@utexas.edu> 

#######################################################################
# DO NOT EDIT THIS MAKEFILE UNLESS YOU KNOW WHAT YOU ARE DOING. 
#######################################################################	

all:
	pdflatex Lecture_7_Scribe_Notes.tex 
	pdflatex Lecture_7_Scribe_Notes.tex 

push: 
	git add *.tex *.pdf
	git commit -m "upgrade"
	git push

clean:
	rm *.aux *.log *.bak
