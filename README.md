# aaprox
A proxy AA for transfer ownership of a predefined asset

It allows to divide asset until 15 decimal places max.

Each operation to AA needs `$BYTE_INP` byte deposit which would be withdrawn later.

Each withdraw or withdraw_bytes costs "exact" amount of response unit fee which is deducted from byte deposited amount.

It allows to do free operations (except withdrawals) until run out of donated bytes (default case).

AA adds trigger unit fees to user balance if there are more bytes than `$FREE_LIMIT`.

User address can give permission to any other address using `approve`.

Optionally, a constant `$ATTESTOR_ADDR` could be defined to limit access to AA. On that case, withdrawals will be also paid by AA with donated bytes.

## Usage
Accepted function params: `withdraw`,`transfer`,`transfer_from`,`approve`,`withdraw_bytes`. Send function = 1 and follow instructions.

Accepted address param: `to`

Accepted numeric param: `value`

https://testnetexplorer.obyte.org/#SCKFaMA7pY8aPBWhFOySbAAjXDH03zaT3up5MC/14bQ=
6BXZTFIFY7DX7LDY536JBFSJHFLLRJIU
