# Analysis results for test-filename.sol

## Ether send

- Type: Warning
- Contract: Unknown
- Function name: `withdrawfunds()`
- PC address: 816

### Description

In the function `withdrawfunds()` a non-zero amount of Ether is sent to msg.sender.

There is a check on storage index 1. This storage slot can be written to by calling the function `crowdfunding()`.

## Integer Overflow 

- Type: Warning
- Contract: Unknown
- Function name: `invest()`
- PC address: 483

### Description

A possible integer overflow exists in the function `invest()`.
The addition or multiplication may result in a value higher than the maximum representable integer.