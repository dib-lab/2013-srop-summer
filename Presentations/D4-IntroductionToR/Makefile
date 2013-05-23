all: D4-IntroductionToR.pdf D4-IntroductionToR.R

D4-IntroductionToR.pdf: D4-IntroductionToR.tex
	pdflatex D4-IntroductionToR.tex

D4-IntroductionToR.tex: D4-IntroductionToR.Rnw
	R CMD Sweave D4-IntroductionToR.Rnw

D4-IntroductionToR.R: D4-IntroductionToR.Rnw
	R CMD Stangle D4-IntroductionToR.Rnw