# name without .R 
nwr= syntaxfile1
# allgemeine R settings
Rsettings=  --no-save

# --------------------------------


all: mygraphic1.pdf


mygraphic1.pdf: $(nwr).R
	R CMD BATCH $(Rsettings) $(nwr).R
	
	
# clean nie als erstes, weil es sonst defaultm��ig bei make ausgef�hrt wird, wenn man all nicht definiert

clean:
	\rm *.Rout *.bak *.pdf