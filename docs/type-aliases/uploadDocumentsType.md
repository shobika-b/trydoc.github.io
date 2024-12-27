---
layout: page
title: Upload Document Type
parent: Types
permalink: /types/uploadDoc
---

# Type Alias : Upload Documents

UploadUserDocsInputDTO: object

## Type declaration

| field                | type          | required  |
|:---------------------|:--------------|:----------|
| userId               | string        | yes       |
| documents            | []DocumentDto | yes       |

DocumentDto: object

| field                | type          | required  |
|:---------------------|:--------------|:----------|
| docName              | string        | yes       |
| base64data           | string        | yes       |
