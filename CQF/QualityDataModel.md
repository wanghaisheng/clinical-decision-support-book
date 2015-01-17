   

# Quality Data Model



The Quality Data Model (QDM) describes clinical concepts in a standardized format to enable electronic clinical quality measurement. The model is the backbone for representing quality measures criteria that are currently used by stakeholders involved in electronic quality measurement development and reporting. Stakeholders include measure developers, federal agencies, health IT vendors, standards organizations, informatics experts, providers, and researchers. The QDM is currently being harmonized with other relevant clinical decision support (CDS) standards.

## Minor Release

The latest version of the Quality Data Model specification, Version 4.1.1, published in September 2014 contains the following changes from the Quality Data Model, Version 4.1:

*   Replacement of _DateDiff_ and _TimeDiff_ functions with _DateTimeDiff_
*   Specification of _DateTimeDiff_ function to be used in measure observations only
*   Addition of a new section describing the use of attribute filters
*   Additional support for filtering date/time attributes by date
*   Re-specification of _Overlaps_ to interpret missing end dates/times as ongoing

This minor release builds on the Quality Data Model specification, QDM 4.1, published in July 2014, which added several new operators and attributes, listed below.

*   _Union_ and _Intersection_ operators
*   _Fulfills_ general relationship operator
*   _Ends Concurrent With Start_ and _Starts Concurrent With End_ timing operators
*   _Medication, Order_ attributes: _signed datetime_ and _active datetime_
*   _Care Goal_ attribute: _target outcome_

In addition to new operators and attributes, QDM 4.1 also included several modifications to the previous version of the specification.

*   _Starts Before Or During_ renamed to _Starts Before End_
*   _Ends Before Or During_ renamed to _Ends Before End_
*   _Patient Characteristic Expired_ attribute _reason_ renamed to _cause_
*   _Measurement Start Date_ and _Measurement End Date_ removed in favor of _Measurement Period_
*   Ambiguous and/or undefined datatypes/attributes clarified or removed ([see QDM-46](http://jira.oncprojectracking.org/browse/QDM-46))
*   QDM data elements restricted to only one attribute at a time
*   Guidance provided regarding the topic of _cumulative medication duration_

Support for these features and modifications were made in the Measure Authoring Tool (MAT) 4.0.0.

The QDM will continue to evolve based on stakeholder input and feedback from the QDM User Group.

*   [QDM 4.1.1 [PDF - 663 KB]](/sites/default/files/qdm_4_1_1.pdf)
*   [HL7 Version 3 Implementation Guide: Quality Data Model (QDM)-based Health Quality Measure Format (HQMF), Release 1](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=346)
*   [Part 1: QDM Training Covering v4.0 and v4.1 [PDF - 675K]](/sites/default/files/qdm_4_1_training_v3_508.pdf)
*   [Part 1: QDM Training Covering v4.0 and v4.1 [YouTube Video]](https://www.youtube.com/watch?v=2xE9giXCQDU)
*   [Part 2: MAT v4.0.0 The MAT Evolution: Implementing the Updated QDM [YouTube Video]](https://www.youtube.com/watch?v=BhjTViDGIhY&amp;feature=youtu.be)

## Previous Versions

The QDM provides detail and explanations for the QDM standard categories, data types, previous definitions and current definitions and includes the rationale and other relevant comments for each revision to the model. All QDM versions are listed below in PDF format including the QDM Style Guide, which is a companion document to the QDM Update June 2012.

The QDM Style Guide addresses feasibility of QDM components with respect to EHRs certified for the 2014 EHR Certification Program proposed by the Office of the National Coordinator for Health IT (ONC). The QDM Style Guide provides guidance as to which information can be expected in structured form in referenced EHRs and which information may be important to measures but would likely require additional effort if certified EHRs are used as the only source of data.

**QDM July 2014**

*   [QDM 4.1 [PDF – 1.23 MB]](/sites/default/files/qdm_4_1.pdf)
*   [HL7 Version 3 Implementation Guide: Quality Data Model (QDM)-based Health Quality Measure Format (HQMF), Release 1](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=346)

**QDM April 2014**

*   [QDM 4.0 [PDF - 1.6 MB]](/sites/default/files/qdm_4_0_final.pdf)
*   [HL7 Version 3 Implementation Guide: Quality Data Model (QDM)-based Health Quality Measure Format (HQMF), Release 1](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=346)

**QDM December 2013**

*   [QDM December 2013 [PDF - 1.5 MB]](/sites/default/files/qdm_dec2013.pdf)
*   [QDM December 2013 HQMF Supplement [PDF - 332 KB]](/sites/default/files/qdm_hqmf_templates_dec2013.pdf)

**QDM December 2012**

*   [QDM, December 2012&nbsp;[PDF - 577 KB]](/sites/default/files/qdm_122012.pdf)
*   [QDM HQMF Supplement, December 2012&nbsp;[PDF - 224 KB]](/sites/default/files/hqmf_supplement.pdf)
*   [QDM June 2012 Update comment responses&nbsp;[PDF - 878 KB]](/sites/default/files/update_comment_responses.pdf)

**QDM October 2012**

*   [QDM, October 2012&nbsp;[PDF - 458 KB]](/sites/default/files/qdmversion2111october2012.pdf)

**QDM June 2012**

*   [June 2012 QDM Update&nbsp;[PDF - 977 KB]](/sites/default/files/hit_qdm_update_06-2012.pdf)
*   [QDM Styleguide&nbsp;[PDF - 260 KB]](/sites/default/files/hit_qdm-style-guide_06-2012.pdf)

**QDM October 2011**

*   [October 2011 Draft Report&nbsp;[PDF - 957 KB]](/sites/default/files/qdm-draft-october-2011.pdf)
*   [Comments received and actions taken, October 2011 Draft Report&nbsp;[PDF - 349 KB]](/sites/default/files/qdmcommentsreceivedfall2011.pdf)

**QDM, Version 3.0**

*   [QDM Overview, Version 3.0&nbsp;[PDF - 1 MB]](/sites/default/files/national_quality_forum_quality_data_model_overview_april_20_2011_final.pdf)
*   [QDM Technical Specification, Version 3.0&nbsp;[PDF - 1 MB]](/sites/default/files/national_quality_forum_qdm_technical_specification_april_2011_final.pdf)
*   [Comments received and actions taken, Version 3.0&nbsp;[PDF - 280 KB]](http://www.healthit.gov/sites/default/files/qdm-version-3-0_comments-actions.pdf)

**QDM, Version 2.1**

*   [QDM, Version 2.1&nbsp;[PDF - 263 KB]](http://www.healthit.gov/sites/default/files/qds_model_version_2_1_september_2010.pdf)
*   [Comments received and actions taken, Version 2.1&nbsp;[PDF - 224 KB]](http://www.healthit.gov/sites/default/files/national_quality_forum_qdm_public_comment_resolution_april_2011.pdf)

**QDM, Version 2.0**

*   [QDM, Version 2.0&nbsp;[PDF - 247 KB]](http://www.healthit.gov/sites/default/files/nqfqds_model_version2_june2010.pdf)
*   [Comments received and actions taken, Version 2.0&nbsp;[PDF - 275 KB]](http://www.healthit.gov/sites/default/files/nqf_qds_model_version_2_comment_resolution_september_2010.pdf)      


## 参考资料     
1. [原始网站](http://www.healthit.gov/quality-data-model)