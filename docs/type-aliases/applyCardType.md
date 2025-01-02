---
layout: page
title: Apply Card Type
parent: Types
permalink: /types/applyCard
---

# Type Alias : Apply Card

ApplyCardInputDTO: object

## Type declaration

| field                | type      | required  | source                                                                           | specifications               |
|:---------------------|:----------|:----------|:---------------------------------------------------------------------------------|:-----------------------------|
| userId               | string    | yes       | id from user/create api response or specific user ID from user/list api response | unique identifier for a user |
| cardId               | string    | yes       | specific card ID from card/list api response                                     | unique identifier for a card |
| embossname           | string    | yes       | -                                                                                | maximum 25 characters        |
| carddeliveryaddress  | string    | yes       | -                                                                                | -                            |
| accountNumber        | string    | optional  | -                                                                                | -                            |
| cardNumber           | string    | optional  | -                                                                                | maximum 16 characters        |
