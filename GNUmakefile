OBJS = PET2LAnalysis.o 
EXE = PET2LAnalysis


ROOTCFLAGS    = $(shell root-config --cflags)
ROOTLIBS      = $(shell root-config --libs)
ROOTGLIBS     = $(shell root-config --glibs)

INCFLAGS = -I$(ROOTSYS)/include
LDFLAGS = -L$(ROOTSYS)/lib

#CXX = gcc -m32 -D_FILE_OFFSET_BITS=64 -D_LARGE_FILE
#####CXX = g++ -g -m32 -D_FILE_OFFSET_BITS=64  -D_LARGEFILE_SOURCE  -D_LARGEFILE64_SOURCE
#CXX = g++ -m32 -D_FILE_OFFSET_BITS=64 -D_LARGE_FILE
CXX = g++ 
FLAGS =  -Wall -std=c++11 -g $(INCFLAGS) $(LDFLAGS)


COMPILE = $(CXX) $(FLAGS) -c 

all: $(EXE) 

$(EXE): $(OBJS)
	$(CXX) -o $(EXE) $(OBJS) $(ROOTCFLAGS) $(ROOTLIBS) $(ROOTGLIBS)

%.o: %.cxx
	$(COMPILE)  $< 

clean:
	rm -f $(EXE)  
	rm -f $(OBJS) 
