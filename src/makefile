FILE = document

pdf:
	dvips -Ppdf -G0 -tletter $(FILE).dvi
	ps2pdf -dCompatibilityLevel=1.4 -dPDFSETTINGS=/prepress $(FILE).ps $(FILE).pdf
