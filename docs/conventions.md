# Reference code convention
The basic format of any reference code is 
`<type>_<date>/<count_number>`\
There can be a shorter format which will only return the latest version of document
`<type>/<count_number>` 
- `type`: the type of legislation, can be:
    - BIL: Bill
    - ACT: Act (bill that was approved and signed)
    - CON: Documents relate to constitution
- `date`: signed date in UTC time with dd-mm-yyy format (24/12/2018). In case the date is not the same as the original sign date, then the code is referring to an amendment that was sign at the date.
- `count_number`: an universal integer count foward for every document with the same type. This field have 6 digits and start with 000000. Exception: documents with `BIL` type will be assign with a random number instead.