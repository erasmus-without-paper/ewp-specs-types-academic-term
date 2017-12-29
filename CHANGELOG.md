Release notes
=============

This document describes all the changes made to the *EWP Academic Term Data
Types* document, starting from its first released version.


1.1.0
-----

* Introduced *EWP unique academic term identifiers* (`EwpAcademicTermId` type).
  Added optional `<ewp-id>` to the academic term type.

* Added a separate `complexType` for academic term contents. Now the users are
  not forced to reuse the `<academic-term>` element, and this can be useful in
  some situations.


1.0.0
-----

* Changed XML Namespace. Replaced the draft `master` branch:

  ```
  https://github.com/erasmus-without-paper/ewp-specs-types-academic-term/tree/master
  ```

  With the `stable-v1` one:

  ```
  https://github.com/erasmus-without-paper/ewp-specs-types-academic-term/tree/stable-v1
  ```

This is the first official stable version, accepted by all the partners
([details here](https://github.com/erasmus-without-paper/general-issues/issues/24)).


0.1.1
-----

* Added an example (in the `README.md` file).


0.1.0
-----

Initial release.
