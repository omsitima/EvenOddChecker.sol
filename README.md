# EvenOddChecker.sol
How to deploy a contract on Base Chain EvenOddChecker.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract EvenOddChecker {
    function isEven(uint _num) public pure returns (bool) {
        return _num % 2 == 0;
    }
}
