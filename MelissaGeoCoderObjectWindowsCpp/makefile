# Melissa GeoCoder Object Windows C++

CXX=cl
CXXFLAGS=-Zi -EHsc
LDLIBS=mdGeo.lib
RM=del /q /f

all: MelissaGeoCoderObjectWindowsCpp.exe clean

MelissaGeoCoderObjectWindowsCpp.exe:	Main.cpp mdGeo.h mdEnums.h
	$(CXX) $(CXXFLAGS) Main.cpp GeoObject.cpp $(LDLIBS) /Fe:.\Build\MelissaGeoCoderObjectWindowsCpp.exe

clean:
	$(RM) *.obj *.ilk *.pdb *.h.hash *.lib.hash 

