
#
# twilio-utils - Command line utilities for Twilio users
# 
# $Id$
#

bin_PROGRAMS=		smslen

dist_bin_SCRIPTS=	sendsms twilog

man_MANS=		smslen.1 sendsms.1 twilog.1

pkgdata_DATA=		result.xsl

docdir=			$(datadir)/doc/packages/$(PACKAGE)

doc_DATA=		CHANGES COPYING README twilio.conf.sample

EXTRA_DIST=		CHANGES INSTALL sendsms.in twilog.in result.xsl twilio.conf.sample

smslen_SOURCES=		smslen.c
