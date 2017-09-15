INCLUDE_PATH    := ./  ../common/ /usr/include/suitesparse
SOURCE_PATH     := ./ ../common/
DEPENDENCY_PATH := dep
OBJECT_PATH     := obj

LDLIBS := -lm -lpthread -lcholmod -lumfpack


CFLAGS += -O3 -D'UF_long=SuiteSparse_long'

include ../makefile.mk
