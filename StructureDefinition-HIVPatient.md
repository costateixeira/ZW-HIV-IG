# HIVPatient - HIV v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **HIVPatient**

## Resource Profile: HIVPatient 

| | |
| :--- | :--- |
| *Official URL*:http://mohcc.gov.zw/fhir/hiv/StructureDefinition/HIVPatient | *Version*:0.1.0 |
| Draft as of 2025-11-13 | *Computable Name*:HIVPatient |

**Usages:**

* This Profile is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/zw.fhir.ig.hiv|current/StructureDefinition/HIVPatient)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-HIVPatient.csv), [Excel](StructureDefinition-HIVPatient.xlsx), [Schematron](StructureDefinition-HIVPatient.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "HIVPatient",
  "url" : "http://mohcc.gov.zw/fhir/hiv/StructureDefinition/HIVPatient",
  "version" : "0.1.0",
  "name" : "HIVPatient",
  "status" : "draft",
  "date" : "2025-11-13T08:50:47+00:00",
  "publisher" : "WHO",
  "contact" : [
    {
      "name" : "WHO",
      "telecom" : [
        {
          "system" : "url",
          "value" : "http://who.int"
        }
      ]
    }
  ],
  "jurisdiction" : [
    {
      "coding" : [
        {
          "system" : "http://unstats.un.org/unsd/methods/m49/m49.htm",
          "code" : "001",
          "display" : "World"
        }
      ]
    }
  ],
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "loinc",
      "uri" : "http://loinc.org",
      "name" : "LOINC code for the element"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Patient",
  "baseDefinition" : "http://mohcc.gov.zw/fhir/core/StructureDefinition/ZimPatient",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Patient",
        "path" : "Patient"
      },
      {
        "id" : "Patient.name",
        "path" : "Patient.name",
        "max" : "0"
      }
    ]
  }
}

```
