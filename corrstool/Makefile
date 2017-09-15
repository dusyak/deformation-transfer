INCLUDE_PATH    := ./  ../common/ ../gl_util/ /usr/include/suitesparse
SOURCE_PATH     := ./ ../common/ ../gl_util/
DEPENDENCY_PATH := dep
OBJECT_PATH     := obj

LDLIBS := -lm -lpthread -lglut -lGL -lGLU -lcholmod -lumfpack


CFLAGS += -O3 -D'UF_long=SuiteSparse_long'

include ../makefile.mk
