ADD_SUBDIRECTORY(globalSfM)
ADD_SUBDIRECTORY(SfM)
#ADD_SUBDIRECTORY(opencv)
IF (NOT APPLE)
  ADD_SUBDIRECTORY(SfMViewer)
ENDIF ()
ADD_SUBDIRECTORY(colorHarmonize)

