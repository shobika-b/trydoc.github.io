---
layout: page
title: Upload Document Type
parent: Types
permalink: /types/uploadDoc
---

# Type Alias : Upload Documents

UploadUserDocsInputDTO: object

## Type declaration

| field                | type          | required  | source                                                                           | specifications               |
|:---------------------|:--------------|:----------|:---------------------------------------------------------------------------------|:-----------------------------|
| userId               | string        | yes       | id from user/create api response or specific user ID from user/list api response | unique identifier for a user |
| documents            | []DocumentDto | yes       | -                                                                                | array of DocumentDto object  |

DocumentDto: object

| field                | type          | required  | specifications                                                       |
|:---------------------|:--------------|:----------|:---------------------------------------------------------------------|
| docName              | string        | yes       | accepted values - "PASSPORT", "SIGNATURE", "SELFIE_WITH_PASSPORT"    |
| base64data           | string        | yes       | document in base64 format                                            |
