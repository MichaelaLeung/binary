#Makefile for p-type hierarchical triple simualtion in 2d 


#compiler
cf=gfortran
#compilder flags
cfalgs=-O -Wall -fbounds-check


obj= twostars_m.o twostars2_tst.o

twostars:$(obj)
	$(cf) -o twostars2 $(obj)

%.o:%.f90
	$(cf) ${cflags} -c $<	
	
# Utility targets
.PHONY: clean veryclean

clean:
	rm -f *.o *.mod *.MOD

