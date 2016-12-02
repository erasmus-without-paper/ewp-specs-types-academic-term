EWP Academic Term Data Types
============================

* [What is the status of this document?][statuses]
* [See the index of all other EWP Specifications][develhub]


Summary
-------

This repository contains XML Schemas used in EWP APIs for addressing academic
years and academic terms. It follows the same [versioning rules][compat-rules]
as all EWP APIs do. Other projects are welcome to reuse this schema, along with
its namespace. We are also open to suggestions of extending it.


The Schema
----------

See attached [`schema.xsd`](schema.xsd) file.


Examples
--------

```xml
<academic-term>
    <academic-year-id>2008/2009</academic-year-id>
    <display-name xml:lang="pl">Semestr letni 2008/2009</display-name>
    <display-name xml:lang="en">Spring semester 2008/2009</display-name>
    <start-date>2009-02-18</start-date>
    <end-date>2009-06-07</end-date>
</academic-term>
```


[develhub]: http://developers.erasmuswithoutpaper.eu/
[statuses]: https://github.com/erasmus-without-paper/ewp-specs-management#statuses
[compat-rules]: https://github.com/erasmus-without-paper/ewp-specs-architecture/#backward-compatibility-rules
[addressing-the-world-paper]: http://www.upu.int/fileadmin/documentsFiles/activities/addressingAssistance/paperAddressingAddressingTheWorldAnAddressForEveryoneEn.pdf
[discussion]: https://github.com/erasmus-without-paper/ewp-specs-architecture/issues/13
[stack-thread]: http://stackoverflow.com/questions/929684/
