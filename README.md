# aaprox
A proxy AA for transfer ownership of a predefined asset

It allows to divide asset until 15 decimal places max.
    
It allows to do free transfers until run out of donated bytes (default case).

Each operation to AA needs 10000 byte deposit which could be withdrawn later.

AA will add trigger unit fees to user if there are more bytes than `$FEE_LIMIT`

User address can give permission to any other address using `approve`.

## Usage
Accepted function params: `deposit`,`withdraw`,`transfer`,`transfer_from`,`approve`,`withdraw_bytes`. Send function = 1 and follow instructions.

Accepted address params: `to`

Accepted numeric param: `value`

https://testnetexplorer.obyte.org/#QVxrEoPFhkPI868x8CqZtQ1J5nLeNEYc+UG4YkHPEjA=
DZKCKGLCLH76VC2HL7ACGHGXTS2667OO
