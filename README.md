# aaprox
A proxy AA for transfer ownership of a predefined asset

It allows to divide asset until 15 decimal places max.
    
It allows to do almost free transfers until run out of bytes, on that case it changes fee to `$DEFAULT_FEE`, it fills with leftover bytes until `$FEE_THRESHOLD` and then changes again to `$LOW_FEE` to restart cycle.

Any byte donation will change cycle to `$LOW_FEE`.

## Usage
Accepted function params: `deposit`,`withdraw`,`transfer`,`transfer_from`,`approve`. Send function = 1 and follow instructions.

Accepted address params: `to`,`from`,`spender`

Accepted numeric param: `value`

https://testnetexplorer.obyte.org/#hWKoPMT2O8/0Um3u8hPYW3Wqh7IODcNCM7nOqgk4JRM=
GP2TKQHIHYTFSJHNVS5ARBWEUCRU3PLV
