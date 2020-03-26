#  Versification in JSON

This directory contains work by the Versification Working Group of the Copenhagen Alliance.  The Working Group members are:

- Mark Howe, United Bible Societies
- Andi Wu, Global Bible Initiative
- Tim Steenwyk, SIL International
- Chris Vaughn, YouVersion
- David Instone-Brewer, Tyndale House
- Jonathan Robie, SIL International

Software that needs to align resources or resolve references in links faces a challenge:  there are many versification schemes, so the same verse reference may not refer to the same text across manuscripts, critical editions, and translations.  The Versification Working Group is working to help software systems bridge across these versification schemes.

Here are the deliverables this Working Group is working on.

## A Versification Format

The Versification Working Group will provide the following:

1. A JSON schema for specifying the versification scheme of a scripture text.
2. A base versification file (`org.json`) and sample versification files that describe the versification of some well-known Scriptures.
3. Documentation describing the schema and how to interpret these files.
4. Sample code for converting among schemes

This versification format is derived from versification files used in Paratext, which used a different format.

## Rules for Versification

The Versification Working Group will provide the following:

1. Rules for Versification - a set of rules, expressed in JSON, to identify the versification scheme used in a given Scripture text.
2. Documention describing the format for these rules and how to use them.
3. Sample code for identifying the versification scheme for a text.
