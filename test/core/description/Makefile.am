TESTS = test_description
noinst_PROGRAMS = test_description
SUBDIRS =
test_description_SOURCES = test_description.c

test_description_LDADD   =  \
			../../../util/src/libaxutil.la \
			../../../axiom/src/om/libaxis2_axiom.la \
			../../../axiom/src/parser/$(WRAPPER_DIR)/libaxis2_parser.la \
			$(top_builddir)/neethi/src/libneethi.la \
			$(top_builddir)/src/core/engine/libaxis2_engine.la

INCLUDES = -I$(top_builddir)/include \
            -I$(top_builddir)/src/core/description \
            -I$(top_builddir)/src/core/context \
            -I$(top_builddir)/src/core/phaseresolver \
            -I$(top_builddir)/src/core/deployment \
            -I$(top_builddir)/src/core/transport \
            -I$(top_builddir)/src/core/engine \
            -I$(top_builddir)/src/core/clientapi \
			-I ../../../util/include \
			-I ../../../axiom/include 

