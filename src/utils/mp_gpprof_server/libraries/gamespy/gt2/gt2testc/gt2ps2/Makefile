#GameSpy.net PS2 Makefile

#SDK-specific compiler flags
#If the SDK uses Unique IDs, add "-DUNIQUEID"
SDK_CLFAGS  = 

#SDK-specific libraries
#If the SDK needs Logitech audio libraries, add "$(LIBDIR)/liblgaud.a"
SDK_LIBS    = 

#Name of the SDK sample
TARGET      = gt2testc

#All the object files needed for this SDK
OBJS        = ../../../ps2common/ps2common.o \
              ../../../nonport.o \
              ../../../darray.o\
              ../../../hashtable.o\
              ../../../stringutil.o \
              ../../gt2Auth.o\
              ../../gt2Buffer.o\
              ../../gt2Callback.o\
              ../../gt2Connection.o\
              ../../gt2Encode.o\
              ../../gt2Filter.o\
              ../../gt2Main.o\
              ../../gt2Message.o\
              ../../gt2Socket.o\
              ../../gt2Utility.o\
              crt0.o \
              ../$(TARGET).o

#Include the stuff common to the GameSpy.net SDKs
include ../../../ps2common/Makefile.common
