#############################################################################
# Makefile for building: libhtmllogger.a
# Generated by qmake (2.01a) (Qt 4.8.2) on: Fri Aug 24 11:35:56 2018
# Project:  htmllogger.pro
# Template: lib
# Command: /qt/project/bin/qmake -o Makefile htmllogger.pro
#############################################################################

####### Compiler, tools and options

CC            = arm-none-linux-gnueabi-gcc
CXX           = arm-none-linux-gnueabi-g++
DEFINES       = -DHTMLLOGGER_LIBRARY -DQT_NO_DEBUG -DQT_NETWORK_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -fPIC -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -fPIC -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/qt/project/mkspecs/qws/linux-arm-g++ -I. -I/qt/project/include/QtCore -I/qt/project/include/QtNetwork -I/qt/project/include -I.
AR            = arm-none-linux-gnueabi-ar cqs
RANLIB        = 
QMAKE         = /qt/project/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = arm-none-linux-gnueabi-strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = htmllogger.cpp moc_htmllogger.cpp
OBJECTS       = htmllogger.o \
		moc_htmllogger.o
DIST          = /qt/project/mkspecs/common/unix.conf \
		/qt/project/mkspecs/common/linux.conf \
		/qt/project/mkspecs/common/gcc-base.conf \
		/qt/project/mkspecs/common/gcc-base-unix.conf \
		/qt/project/mkspecs/common/g++-base.conf \
		/qt/project/mkspecs/common/g++-unix.conf \
		/qt/project/mkspecs/common/qws.conf \
		/qt/project/mkspecs/qconfig.pri \
		/qt/project/mkspecs/modules/qt_webkit_version.pri \
		/qt/project/mkspecs/features/qt_functions.prf \
		/qt/project/mkspecs/features/qt_config.prf \
		/qt/project/mkspecs/features/exclusive_builds.prf \
		/qt/project/mkspecs/features/default_pre.prf \
		/qt/project/mkspecs/features/release.prf \
		/qt/project/mkspecs/features/default_post.prf \
		/qt/project/mkspecs/features/staticlib.prf \
		/qt/project/mkspecs/features/static.prf \
		/qt/project/mkspecs/features/warn_on.prf \
		/qt/project/mkspecs/features/qt.prf \
		/qt/project/mkspecs/features/unix/thread.prf \
		/qt/project/mkspecs/features/moc.prf \
		/qt/project/mkspecs/features/resources.prf \
		/qt/project/mkspecs/features/uic.prf \
		/qt/project/mkspecs/features/yacc.prf \
		/qt/project/mkspecs/features/lex.prf \
		/qt/project/mkspecs/features/include_source_dir.prf \
		htmllogger.pro
QMAKE_TARGET  = htmllogger
DESTDIR       = ../build/
TARGET        = libhtmllogger.a

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile ../build/$(TARGET) 

staticlib: ../build/$(TARGET)

../build/$(TARGET):  $(OBJECTS) $(OBJCOMP) 
	@$(CHK_DIR_EXISTS) ../build/ || $(MKDIR) ../build/ 
	-$(DEL_FILE) $(TARGET)
	$(AR) $(TARGET) $(OBJECTS)
	-$(DEL_FILE) ../build/$(TARGET)
	-$(MOVE) $(TARGET) ../build/


Makefile: htmllogger.pro  /qt/project/mkspecs/qws/linux-arm-g++/qmake.conf /qt/project/mkspecs/common/unix.conf \
		/qt/project/mkspecs/common/linux.conf \
		/qt/project/mkspecs/common/gcc-base.conf \
		/qt/project/mkspecs/common/gcc-base-unix.conf \
		/qt/project/mkspecs/common/g++-base.conf \
		/qt/project/mkspecs/common/g++-unix.conf \
		/qt/project/mkspecs/common/qws.conf \
		/qt/project/mkspecs/qconfig.pri \
		/qt/project/mkspecs/modules/qt_webkit_version.pri \
		/qt/project/mkspecs/features/qt_functions.prf \
		/qt/project/mkspecs/features/qt_config.prf \
		/qt/project/mkspecs/features/exclusive_builds.prf \
		/qt/project/mkspecs/features/default_pre.prf \
		/qt/project/mkspecs/features/release.prf \
		/qt/project/mkspecs/features/default_post.prf \
		/qt/project/mkspecs/features/staticlib.prf \
		/qt/project/mkspecs/features/static.prf \
		/qt/project/mkspecs/features/warn_on.prf \
		/qt/project/mkspecs/features/qt.prf \
		/qt/project/mkspecs/features/unix/thread.prf \
		/qt/project/mkspecs/features/moc.prf \
		/qt/project/mkspecs/features/resources.prf \
		/qt/project/mkspecs/features/uic.prf \
		/qt/project/mkspecs/features/yacc.prf \
		/qt/project/mkspecs/features/lex.prf \
		/qt/project/mkspecs/features/include_source_dir.prf \
		/qt/project/lib/libQtNetwork.prl \
		/qt/project/lib/libQtCore.prl
	$(QMAKE) -o Makefile htmllogger.pro
/qt/project/mkspecs/common/unix.conf:
/qt/project/mkspecs/common/linux.conf:
/qt/project/mkspecs/common/gcc-base.conf:
/qt/project/mkspecs/common/gcc-base-unix.conf:
/qt/project/mkspecs/common/g++-base.conf:
/qt/project/mkspecs/common/g++-unix.conf:
/qt/project/mkspecs/common/qws.conf:
/qt/project/mkspecs/qconfig.pri:
/qt/project/mkspecs/modules/qt_webkit_version.pri:
/qt/project/mkspecs/features/qt_functions.prf:
/qt/project/mkspecs/features/qt_config.prf:
/qt/project/mkspecs/features/exclusive_builds.prf:
/qt/project/mkspecs/features/default_pre.prf:
/qt/project/mkspecs/features/release.prf:
/qt/project/mkspecs/features/default_post.prf:
/qt/project/mkspecs/features/staticlib.prf:
/qt/project/mkspecs/features/static.prf:
/qt/project/mkspecs/features/warn_on.prf:
/qt/project/mkspecs/features/qt.prf:
/qt/project/mkspecs/features/unix/thread.prf:
/qt/project/mkspecs/features/moc.prf:
/qt/project/mkspecs/features/resources.prf:
/qt/project/mkspecs/features/uic.prf:
/qt/project/mkspecs/features/yacc.prf:
/qt/project/mkspecs/features/lex.prf:
/qt/project/mkspecs/features/include_source_dir.prf:
/qt/project/lib/libQtNetwork.prl:
/qt/project/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -o Makefile htmllogger.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/htmllogger1.0.0 || $(MKDIR) .tmp/htmllogger1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/htmllogger1.0.0/ && $(COPY_FILE) --parents htmllogger.h .tmp/htmllogger1.0.0/ && $(COPY_FILE) --parents htmllogger.cpp .tmp/htmllogger1.0.0/ && (cd `dirname .tmp/htmllogger1.0.0` && $(TAR) htmllogger1.0.0.tar htmllogger1.0.0 && $(COMPRESS) htmllogger1.0.0.tar) && $(MOVE) `dirname .tmp/htmllogger1.0.0`/htmllogger1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/htmllogger1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_htmllogger.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_htmllogger.cpp
moc_htmllogger.cpp: htmllogger.h
	/qt/project/bin/moc $(DEFINES) $(INCPATH) htmllogger.h -o moc_htmllogger.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean 

####### Compile

htmllogger.o: htmllogger.cpp htmllogger.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o htmllogger.o htmllogger.cpp

moc_htmllogger.o: moc_htmllogger.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_htmllogger.o moc_htmllogger.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

