# $Date$
# $Revision$

check_PROGRAMS  = entity_test entityrep_test geometry_test orientedentitytable_test
#noinst_PROGRAMS = buildcpgrid_test

AM_CXXFLAGS = $(DUNE_CPPFLAGS) $(DUNEMPICPPFLAGS) $(OPM_BOOST_CPPFLAGS)
AM_LDFLAGS  = $(DUNE_LDFLAGS) $(DUNEMPILDFLAGS) $(OPM_BOOST_LDFLAGS)

entity_test_SOURCES  = entity_test.cpp
entity_test_LDADD    = $(DUNE_LIBS) $(DUNEMPILIBS) $(BOOST_UNIT_TEST_FRAMEWORK_LIB)

entityrep_test_SOURCES  = entityrep_test.cpp
entityrep_test_LDADD    = $(DUNE_LIBS) $(DUNEMPILIBS) $(BOOST_UNIT_TEST_FRAMEWORK_LIB)

geometry_test_SOURCES  = geometry_test.cpp
geometry_test_LDADD    = $(DUNE_LIBS) $(DUNEMPILIBS) $(BOOST_UNIT_TEST_FRAMEWORK_LIB)

orientedentitytable_test_SOURCES = orientedentitytable_test.cpp
orientedentitytable_test_LDADD   = $(DUNE_LIBS) $(DUNEMPILIBS) $(BOOST_UNIT_TEST_FRAMEWORK_LIB)

#buildcpgrid_test_SOURCES  = BuildCpGrid.hpp buildcpgrid_test.cpp
#buildcpgrid_test_LDADD    = $(DUNE_LIBS) $(BOOST_SYSTEM_LIB) \
#                            ../../lib/libdunecornerpoint.la

TESTS = $(check_PROGRAMS)

include $(top_srcdir)/am/global-rules
