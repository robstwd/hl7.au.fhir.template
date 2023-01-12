# HL7 Australia FHIR template

package hl7.au.fhir.template

Template used for most HL7-defined FHIR implementation guides (based on ig-template-base - package = hl7.base.template).  Adds HL7 logos.

## Inheritance
This template inherits from the base HL7AU template: `hl7.au.base.template#current` 

https://github.com/hl7au/hl7.au.base.template

## Template inclusions

### 1. ./includes
#### a) `/_append.fragment-css.html`
css styling - css/fhir.css

* footer background colour
* navbar inverse colour
* logo to right side

#### b) `/_append.fragment-footer.html`
To the footer, adds:
* `Version History` link
* license image and link
* `Propose a change` link

#### c) `/_append.fragment-header.html`
To the header, adds:
* AU FHIR logo, appearing at the right side, with link 

### 2. ./layout
No additions

### 3. ./scripts
No additions