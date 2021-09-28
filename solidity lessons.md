pragma solidity ^0.5.1;

// it is publically accessible, value declared in contract is what will be stored on blockchain

contract Mycontract {
    // can declare whatever we want, it can be set or something constant by removing set
    string public value = "myValue";
    

    function set(string memory _value) public {
        value = _value;
    }
}

// this smart contract sets the value whenever it is deployed and it has functions to allow us to read and create value.
