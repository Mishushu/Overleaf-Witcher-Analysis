# Security Policy

## All my projects and attachments are licensed under the Mozilla Public License (MPL). This license allows others to freely use, modify, and distribute the software, provided any derivative works are also made available under the same license terms.

### Mozilla Public License (MPL)

Mozilla Source Code License Policy
Version 4.1

Introduction
Overview: this flowchart provides a summary of the policy that can help you decide which license to use.

This policy determines which license to use for source files stored in Mozilla-controlled code repositories, whether hosted at Mozilla or elsewhere - "Mozilla Repositories". Committers to Mozilla Repositories must comply with this policy, as they agreed to do in the Committer's Agreement. The following is a brief summary:

New files in, or modifications to, an existing, consistently-licensed area of code should be under the same license as the existing code.
New projects should be under the MPL 2.0 or Apache 2.0 - see below for guidance on choosing which.
You must consult the licensing team before importing third-party code which is not under the MPL or Apache 2.0.
Mozilla employees can consult the Licensing & Contributor Agreements Runbook for more details.
Types of Code
Mozilla Code is code in Mozilla Repositories which originated with the Mozilla Project. Code which is not Mozilla Code is Third Party Code.

Product Code means all files any part of which is included in nightly binaries of client-side Mozilla products. Note that this definition excludes the code of tools used merely to build these products, such as system libraries.

Test Code means test cases for automated test frameworks (but not the frameworks themselves).

Licensing of Mozilla Code
New files in, modifications to, or code designed to integrate with or build on an existing, consistently-licensed area of Mozilla Code should be under the same license as the existing code. This means that modifications to Product Code will be MPL 2.

New projects which are Mozilla Code may choose either the MPL 2.0 or the Apache License 2.0. No other license is acceptable, because Mozilla is committed to using modern open source licenses with patent grant clauses. The licensing team recommends MPL 2.0 for client-side code; please consult the team before going against this recommendation.

Trivial bits of Mozilla Code, such as test cases or snippets of code used in documentation, should be put in the public domain in order to facilitate re-use. To do that, apply the Creative Commons Public Domain Dedication by using the following boilerplate:

Any copyright is dedicated to the Public Domain.
http://creativecommons.org/publicdomain/zero/1.0/

Note that, for historical reasons, some trivial support code, such as old code samples in developer.mozilla.org, may be under the MIT license.

PD Test Code is test cases for automated test frameworks that (1) is Mozilla Code, (2) does not carry an explicit license header, and (3) was either committed to a Mozilla Repository on or after 23rd September 2014, or was committed before that date but for which all contributors up to that date were Mozilla employees, contractors or interns. PD Test Code is placed in the public domain pursuant to the Creative Commons Public Domain Dedication. Test Code which has not been demonstrated to be PD Test Code should be considered to be under the MPL 2.

Licensing of Third Party Code
When modifying or adding to Third Party Code that has already been checked into a Mozilla Repository, you should use the license pertaining to that code. The only exception is if you are adding Mozilla-specific files that have no reason to go upstream, such as build system files. In that case, you should use the MPL.

If you are planning to import new Third Party Code into a Mozilla Repository, always consult the licensing team first. They can check whether the license is compatible - even simple-looking licenses can have twists in them - and make sure our requirements are met. After such consultation, a developer checking in Third Party Code should make sure that:

The checkin comment contains information (or references to information) sufficient to identify the author of the Code, including at minimum an email address, and ideally the URL of a public source repository where the code was obtained from.
about:license is updated to refer to the new code (and new license, if any). Please file a Licensing bug.
All code in Mozilla Repositories must be under an Open Source Definition-compliant license. There may be further restrictions on what licenses are permissible, depending on what the Third Party Code is to be used for. For example, Product Code that is Third Party Code must be under the MPL, or a compatible license (see list below). The purpose of this rule is to make sure that all users of our code can use the complete codebase under the MPL, and that no group is disadvantaged.

Other Information
Filing Licensing Bugs
If you need to make a request of, or seek information from, the licensing team, please file a bug in Bugzilla.

Using the MPL
To apply the MPL to new source files, please don't copy boilerplate from existing files - instead, use the appropriate boilerplate license notice.

Licenses Compatible with the MPL
The following waivers and licenses are compatible with the Mozilla Public License, version 2.0, in the sense that code under them can be included in the same binary:

Creative Commons Zero
Other Public Domain dedications
MIT, New BSD, and similar permissive licenses
Apache 2.0
GPL and MPL dual license
In addition, it may be permissible to import Third Party Code under the LGPL (version 2.0 upwards) to be Product Code if it's a clearly-demarcated library and will be dynamically linked into the product.

The following licenses are not compatible with the Mozilla Public License, version 2.0:

CC-BY, CC-BY-*
GPL
Remember, always consult the licensing team before importing Third Party Code.

Copying Code
You may copy code between files with identical licensing terms, or between files where the target file has a subset of the licenses of the source file (e.g. MPL/LGPL/GPL -> MPL). For any other transfer, consult the licensing team first.

Reporting Incompatible Code
If you happen to find a file in the Mozilla source tree which does not conform to our licensing policy, please report it to the licensing team.
