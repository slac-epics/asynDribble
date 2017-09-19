TOP=..
include $(TOP)/configure/CONFIG
#=======================================

# Build asynDribble as a library for an IOC:
LIBRARY_IOC += asynInterposeDribble

# Library Source files
asynInterposeDribble_SRCS += asynInterposeDribble.c

# Link with the asyn and base libraries
asynInterposeDribble_LIBS += asyn
asynInterposeDribble_LIBS += $(EPICS_BASE_IOC_LIBS)

# Install .dbd and .db files
DBD += asynInterposeDribble.dbd

#=======================================
include $(TOP)/configure/RULES
