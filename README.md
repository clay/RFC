RFC
===

## Clay Request for Comments Library

This repository is intended to hold RFCs for the Clay Project and any of it's associated projects. The main idea is to document the design, implementation, and purpose of various facets of the Clay Project. The contents of an RFC is not meant to be removed from the document, once it is published (committed), it is part of the permanent record for that RFC.

## How to Use it

RFCs can cover theory, specifications, protocals, inclusive implemenations, and specific implementations.  In a nutshell, an RFC can cover anything.  An RFC, included in this repository, should be a MarkDown file (.md), but can be published in any format.  Anyone is allowed to submit, modify, and comment an RFC, by submitting a pull request.  If you want a pull request to be accepted, it is recommended to submit comments to an established RFC.

### New RFCs

#### Contents

A new RFC should contain the author's name, current date, a short title, and a description.  It should be assigned an RFC id by YY-nnn ; this id is the current year, followed by a chronological RFC number.  So the first 3 RFCs will be: 14-001, 14-002, 14-003.  Once an RFC is considered established, it will be assigned an acceptance id and appear as nnn-YY-nnn: 001-14-001, for example.

#### File Name

An RFC should be named [short title]_[RFC id].md  For example: modules/RestServer_2014-054.md

### Modifications

Modifications to established RFCs should be modified in a way that provides evidence to what was changed.  This can be by striking out the changed portion of the text or by moving it to a referenced footnote.  Striking through the changed portion is recommended, if plausible.

### Comments

An RFC should be commented by placing blockquotes around the individual's name, current date, and a short subject.  Comments should be placed at the end of the file and should not be removed unless they become or are determined to be irrelevant.  Striking through a comment is the recommended means to handle a removed comment.

## Repository File Structure

RFCs should be contained in a heirarchy to easily distinguish it's purpose.  Theories, specifications, and protocols may be placed in the root of the repo, but may be moved later.  An RFC that covered a specific implementation, should be categorize under a folder for that type, such as: application, module, library, etc.  If you are unsure of a location, commit it to the root of the repo and it can be categorized later.

## Establishing an RFC

Committing an RFC or acceptance of an RFC into the repo does not make that RFC deemed as established.  An RFC is considered established once it has been reviewed and is recognized as the desired implementation of whatever subject it covers.  

An established RFC will be prefixed with a chronological acceptance id, such as RFC 001-14-001

## End of Life

An RFC is considered to have been deprecated, obsolete, etc once a new RFC is established and has been reviewed or a new implementation has occurred based on a newer RFC.  An RFC can live over multiple implementations, as long as a new RFC has not been established. An RFC for a proposed implementation or committed as a theory or design that is considered experimental does not override an established RFC until the new RFC has become established.

## Final Thoughts

The overall design and contents of an RFC is at the liberty of the author.  Stricter standards will likely be implemented in the future, but he intent is to give the author as much liberty as possible, within the guidelines set in this document.
