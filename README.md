# ChainMessage.sol
ChainMessage.sol9
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract ChainMessage {
    string public message;

    constructor(string memory _message) {
        message = _message;
    }

    function setMessage(string memory _newMessage) public {
        message = _newMessage;
    }
}
Update contract logic
Improve contract structure
Add basic validation
Fix edge case handling
