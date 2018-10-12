all: slides.pdf
	
slides.pdf: slides.tex
	texi2pdf slides.tex

run: slides.pdf
	okular slides.pdf

clean:
	rm slides.aux  slides.log  slides.nav  slides.out slides.snm slides.toc  slides.vrb

ultraclean:
	rm slides.aux slides.pdf slides.log  slides.nav  slides.out slides.snm slides.toc  slides.vrb
