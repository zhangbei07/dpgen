#Parameters
SYSTEM  =  dpgen
PREC    =  A
ISART   =  0
ICHARG  =  2
#Electronic Relaxation 
ENCUT   =  650
NELM    =  100
NELMIN  =  6
NELMDL  =  -5
EDIFF   =  1e-06
LREAL   =  False
ALGO    =  Fast  # or normal
#Ionic relaxation
IBRION  =  0
ISIF    =  2
#EDIFFG  =  -0.01  # useless for MD
ISYM    =  0
NSW     =  10
ISMEAR  =  0
SIGMA   =  0.1
# MD related
SMASS   = 0
POTIM   = 2
TEBEG   = 100
TEEND   = 100
NBLOCK  = 1
KBLOCK  = 100
# Write flags
LWAVE    =  False
LCHARG   =  False
#parallel related
#KPAR   = 4
#NPAR    =  1
KSPACING = 0.1
KGAMMA  = False

PSTRESS = 0.0
