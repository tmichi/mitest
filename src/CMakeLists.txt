ADD_LIBRARY( mitest SHARED TestCase.cpp TestSuite.cpp)
SET_TARGET_PROPERTIES(mitest PROPERTIES VERSION ${serial} SOVERSION ${soserial})
INSTALL(TARGETS mitest LIBRARY DESTINATION lib)


