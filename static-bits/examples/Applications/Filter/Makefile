# BANNERSTART
# - Copyright 2006-2008, Galois, Inc.
# - This software is distributed under a standard, three-clause BSD license.
# - Please see the file LICENSE, distributed with this software, for specific
# - terms and conditions.
# Author: Magnus Carlsson <magnus@galois.com>
# BANNEREND
#

HALVM_SRCS=Filter.hs Dirty.hs
TEST_SUBJECTS=Filter
TEST_VMS=PlayerA PlayerB PlayerC

VERBOSE_TEST=--verbose

all: test

include ../../mk/tests.mk


runA: Filter
	$(XM) create Filter.config name="PlayerA" extra="player=A" -c

runB: Filter
	$(XM) create Filter.config name="PlayerB" extra="player=B" -c

runC: Filter
	$(XM) create Filter.config name="PlayerC" extra="player=C" -c

