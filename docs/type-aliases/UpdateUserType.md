---
layout: page
title: Update User Type
parent: Types
permalink: /types/updateUser
---

# Type Alias : Update User

UpdateUserInputDTO: object

## Type declaration

| field                | type      | required  | specifications                              |
|:---------------------|:----------|:----------|:--------------------------------------------|
| title                | string    | optional  | maximum 5 characters eg: Mr, Ms, Dr         |
| first_name           | string    | optional  | only alphabets                              |
| last_name            | string    | optional  | only alphabets                              |
| gender               | string    | optional  | accepted values - Male, Female, Other, None |
| dob                  | string    | optional  | format - DD/MM/YYYY                         |
| place_of_birth       | string    | optional  | full country name, maximum 10 characters    |
| birth_country        | string    | optional  | 2-digit ISO format eg: Australia = AU       |
| village              | string    | optional  | -                                           |
| district             | string    | optional  | -                                           |
| province             | string    | optional  | -                                           |
| isd_code             | int       | optional  | eg Australia - *61*                         |
| telephone            | string    | optional  | -                                           |
| mail                 | string    | optional  | -                                           |
| occupation           | string    | optional  | -                                           |
| passportnumber       | string    | optional  | -                                           |
| passport_issue_date  | string    | optional  | format - DD/MM/YYYY                         |
| passport_expiry_date | string    | optional  | format - DD/MM/YYYY                         |
