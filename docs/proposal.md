# Our Proposal to IATI

---

## Project-level Attributes 
| MapMe Data Type                          | Name in the IATI Standard                              | Mandatory       | Location in the IATI Standard          |
|------------------------------------------|--------------------------------------------------------|-----------------|----------------------------------------|
| Project ID                               | IATI Identifier                                        | Y               | Element of an IATI Activity            |
| Data Publisher                           | IATI Organisation Identifier                           | Y               | Element of an IATI Activity            |
| Project Title                            | Title                                                  | Y               | Element of an IATI Activity            |
| Project Description                      | Description                                            | Y               | Element of an IATI Activity            |
| Project Status                           | Activity Status                                        | Y               | Element of an IATI Activity            |
| Project Start / End Date                 | Activity Date                                          | Y               | Element of an IATI Activity            |
| Project Sector                           | Sector (DAC Vocabulary No. 1: 5-digit CRS Code & Name) | Y               | Element of an IATI Activity            |
| Project Recipient Country / Region       | Recipient Country / Recipient Region                   | Y               | Element of an IATI Activity            |
| Project Donor / Client                   | Participating Organisation (upstream)                  | Y               | Element of an IATI Activity            |
| Type of Financing Instrument             | Finance Type                                           | recommended as Y| Element of an IATI Activity            |
| Name of Executing / Implementing Agency  | Activity participants                                  | recommended as Y| Element of an IATI Activity            |
| Date of Data Collection / Latest Update  |                                                        | optional        | Attribute of iati-activity             |
| Language Code                            |                                                        | optional        | Attribute of iati-activity             |

---

## Location-level Attributes
| MapMe Data Type                              | Name in the IATI Standard                         | Mandatory       | Location in the IATI Standard              |
|----------------------------------------------|---------------------------------------------------|-----------------|--------------------------------------------|
| Location Activity Description                | Activity Description                              | Y               | Sub-element of iati-activity/location      |
| Location Reach                               | Location Reach                                    | Y               | Sub-element of iati-activity/location      |
| Geographic Exactness                         |                                                   | Y               | Sub-element of iati-activity/location      |
| Location Description                         | Description                                       | Y               | Sub-element of iati-activity/location      |
| Location Type (Name)                         | Location Type                                     | Y               | Sub-element of iati-activity/location      |
| Geospatial Attributes – Admin Unit / Point   | Administrative / Point                            | Y               | Sub-element of iati-activity/location      |
| Field ID                                     |                                                   | recommended as Y| Attribute of iati-activity/location        |
| IATI Location ID                             | Location ID                                       | recommended as Y| Sub-element of iati-activity/location      |
| Location Name                                |                                                   | recommended as Y| Sub-element of iati-activity/location      |
| Location (Sub-)Activity Status               |                                                   | recommended as Y| n/a                                        |
| Geospatial Attributes – Line / Polygon       |                                                   | recommended as Y| n/a                                        |
| Location Start / End Date                    |                                                   | optional        | n/a                                        |
| Date of Data Collection / Latest Update      |                                                   | optional        | n/a                                        |
| Publishing Restrictions (Security)           |                                                   | optional        | n/a                                        |

