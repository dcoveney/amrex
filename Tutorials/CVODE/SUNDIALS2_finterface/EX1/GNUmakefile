# AMREX_HOME defines the directory in which we will find all the BoxLib code
# If you set AMREX_HOME as an environment variable, this line will be ignored
AMREX_HOME ?= ../..

DEBUG     = FALSE
USE_MPI   = TRUE
COMP      = gnu
DIM       = 3
PRECISION = DOUBLE
EBASE     = main

USE_CVODE = TRUE
CVODE_LIB_DIR ?= ${CVODE_LIB}

include $(AMREX_HOME)/Tools/GNUMake/Make.defs

include ./Make.package
include $(AMREX_HOME)/Src/Base/Make.package

include $(AMREX_HOME)/Tools/GNUMake/Make.rules
