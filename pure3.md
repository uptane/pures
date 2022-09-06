* PURE: 3
* Title: Creating a responsible disclosure policy for Uptane
* Version: 1
* Last-Modified: 05-September-2022 
* Author: Philip Lapczynski philip.lapczynski@renesas.com, Lois Anne DeLong  lad278@nyu.edu
* Status: 
* Content-Type: text/markdown
* Created: 09-September-2022

# Abstract

This PURE proposes a formal mechanism for reporting vulnerabilities in the Uptane Standard. It also attempts to set some boundaries as to what the Uptane maintainers can actually do with any given reported vulnerability. While a patch can be prepared, Uptane maintainers are not capable of overseeing the application of such a patch. Therefore, the reporting mechanism proposed here will also specify what those submitting a vulnerability can reasonably expect in the way of a response from Uptane maintainers. 

# Motivation

The Uptane community recognizes the possibility of a vulnerability coming to light in its specification and therefore recognizes the need for a mechanism for users to report vulnerabilities. With input from the Uptane community at large, maintainers rigorously endeavor to keep the specification and any reference implementations under its control up-to-date and, in case of a perceived vulnerability, to make patches accessible to other users. What Uptane maintainers are NOT in a position to do is ensure these patches are actually installed.  Most Uptane implementations are private and proprietary. If an issue has the potential to be exploited in the wild, Uptane maintainers or authors cannot actually act on such reported vulnerabilities. Indeed, as an open source framework, the Uptane community does not even have a comprehensive list of all existing implementations. 

Another factor to consider in crafting a responsible disclosure policy for Uptane is that, given the sheer number of individual vehicles that could be impacted if, for example, a recall was deemed necessary, regulatory issues and potential liability would make such a process complicated, and confusing. Automobiles are global products and it is highly likely such procedures would vary in different jurisdictions around the world.

Therefore, the reporting and adoption method suggested below must offer a) an easy way to report observed vulnerabilities in the specification; b) a policy for evaluating and responding to reported vulnerabilities; c) guidelines for releasing vulnerability notifications and patches.

# Specification

## *Reporting a vulnerability*
Suspected security vulnerabilities should be reported to `uptane-security [AT] googlegroups [DOT] com. We're committed to working with security researchers to resolve the vulnerabilities they discover. You can help us by following these guidelines:

Please give as much detail as possible for a suspected vulnerability in Uptane including:

* Version in which it was found
* Description of vulnerability
* Examples (if applicable)

Give us a reasonable time to correct the issue before you disclose the vulnerability. We care deeply about security, but we're an open-source project and our team consists mostly comprised of volunteers.

We will acknowledge the contributions of security researchers (if desired)

## *Followup on reported items* 

# Security Analysis

# Backwards Compatibility 

# Copyright 
This document has been placed in the public domain.
