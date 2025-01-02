---
layout: page
title: Create User Type
parent: Types
permalink: /types/createUser
---

# Type Alias : Create User

CreateUserInputDTO: object

## Type declaration

| field                | type      | required  | specifications                              |
|:---------------------|:----------|:----------|:--------------------------------------------|
| title                | string    | yes       | maximum 5 characters eg: Mr, Ms, Dr         |
| first_name           | string    | yes       | only alphabets                              |
| last_name            | string    | yes       | only alphabets                              |
| gender               | string    | yes       | accepted values - Male, Female, Other, None |
| dob                  | string    | yes       | format - DD/MM/YYYY                         |
| place_of_birth       | string    | yes       | full country name, maximum 10 characters    |
| birth_country        | string    | yes       | 2-digit ISO format eg: Australia = *AU*     |
| village              | string    | yes       | -                                           |
| district             | string    | yes       | -                                           |
| province             | string    | yes       | -                                           |
| isd_code             | int       | yes       | eg Australia - *61*                         |
| telephone            | string    | yes       | -                                           |
| mail                 | string    | yes       | -                                           |
| occupation           | string    | yes       | -                                           |
| passportnumber       | string    | yes       | -                                           |
| passport_issue_date  | string    | yes       | format - DD/MM/YYYY                         |
| passport_expiry_date | string    | yes       | format - DD/MM/YYYY                         |
