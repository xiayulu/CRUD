
# Api

An api is some kind of resource.

## Overview

For each api, we can do some Operations:

Http:
- Create 
- Update
- List
- Detail
- Delete

WebSocket:
- Send
- SendMany
- Recieve


For each operation, there are some associated types:

- Input: Header+Query+Body
- Output: Ok(T)+Err(E)+Doc

And some assotiated Operations:

- Log
- Permission
- Statistic
- Throttle
- ...

## Api Operation

Input -> [Prelude Operations] -> Operation -> [Post Operations] -> Output

## Struct Design

- Main Struct: includes all fields
- Input Struct: subset of main
- Output Struct: subset of main

