AM_TESTS_ENVIRONMENT = top_srcdir="$(top_srcdir)" top_builddir="$(top_builddir)" ; . $(srcdir)/testenv.sh ;

dist_noinst_SCRIPTS = libbytesize_unittest.sh libbytesize_unittest.py lbs_py_override_unittest.py locale_utils.py testenv.sh canary_tests.sh

TESTS = libbytesize_unittest.sh lbs_py_override_unittest.py canary_tests.sh

# Add the translation-canary source files to the tarball
EXTRA_DIST = $(top_srcdir)/translation-canary/translation_canary/*.py \
             $(top_srcdir)/translation-canary/translation_canary/*/*.py

MAINTAINERCLEANFILES = Makefile.in
