---
title: Delta Encoding
abbrev:
date: 2014
category: info

ipr: trust200902
area: General
workgroup:
keyword: Internet-Draft

stand_alone: yes
pi: [toc, tocindent, sortrefs, symrefs, strict, compact, comments, inline]

author:
 -
    ins: B. Smith
    name: Bob Smith
    organization: Google
    email: bob@google.com
    uri: https://www.google.com/

normative:
  RFC2119:
  RFC5234:
  RFC5226:
  RFC7230:
  RFC7231:


informative:

--- abstract

Delta encoding mechanism to reduce the payload size by only transferring the diff.

--- middle

# Introduction

Intro goes here.

## Notational Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in {{RFC2119}}.

This document uses the Augmented Backus-Naur Form (ABNF) notation of {{RFC5234}} with the list rule extension defined in {{RFC7230}}, Appendix B. It includes by reference the DIGIT rule from {{RFC5234}}; the OWS, field-name and quoted-string rules from {{RFC7230}}; and the parameter rule from {{RFC7231}}.


# IANA Considerations

This document defines the "A", "B", "C", and "D" HTTP request fields and registers them in the Permanent Message Header Fields registry.

- Header field name: A
- Applicable protocol: HTTP
- Status: standard
- Author/Change controller: Bob Smith, bob@google.com
- Specification document(s): [this document]
- Related information: for Delta Encoding


# Security Considerations

Text goes here.

--- back
