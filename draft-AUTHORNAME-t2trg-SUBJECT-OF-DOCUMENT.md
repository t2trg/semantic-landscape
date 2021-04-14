---
# This is a skeleton Internet-Draft to get you going.
# (1) Replace all the uppercase words.
# (2) Rename the file as shown below.
# (3) Commit
# (4) make -f lib/setup.mk
# For local use, best compile this to TXT and HTML with
#   kdrfc -3chi filename.md
#   e.g.,
#   kdrfc -3chi draft-AUTHORNAME-t2trg-SUBJECT-OF-DOCUMENT.md
# This gives you: a .txt and a .html for looking at,
#   a .v2v3.xml to submit to dt.ietf.org/submit (submit this XML file
#   only!) after replacing -latest with -00 twice,
#   and (if you have installed idnits), an idnits report (which will
#   always have four complaints on the file name) on the command line.

docname: draft-AUTHORNAME-t2trg-SUBJECT-OF-DOCUMENT-latest
# use as filename, too, but without -latest and with .md appended
title: >
  TITLE OF DOCUMENT
abbrev: SHORT TITLE
# Various attributes:
stand_alone: true
ipr: trust200902
cat: info
pi:
  compact: true
  symrefs: true
  sortrefs: true

# List of authors; give name, email, and possibly org,
#   and any further RFC 7749 Section 2.2 and 2.6 attributes you want
author:
- name: Fritz the Cat
  email: fritz@example.com
- name: Mickey Mouse
  org: Disney
  email: mickey@example.com
# Like authors, but not on title page.
#   Remove if not needed.
contributor:
  - name: Pikachu
    email: pikachu@example.com

# References: remove next two lines if you don't have normative references.
normative:
  RFC0815:
informative:
  RFC4711:
  I-D.ietf-anima-bootstrapping-keyinfra:
  DOI.10.1109/MIC.2012.29:

--- abstract

ABSTRACT -- DO NOT INCLUDE FORMAL REFERENCES HERE

--- middle

# Introduction

FILLME

# Terminology {#terminology}

DELETE THIS IF MUST/MAY ETC. ARE NOT USED:
{::boilerplate bcp14}

# One Section: Background {#background}

FILLME

# Another Section

FILLME

# Security Considerations

# IANA Considerations

This document does not make any requests on IANA.

--- back

# Acknowledgements
{: numbered="false"}

We would like to thank the academy and all our supporters.
