// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract MarquezSmartContract{
    uint public totalValue;

    function sellerSetValue(uint _value) external {
        //require statement of seller
        require(_value != 4, "The value is sum");
        
       totalValue = _value;
    }

    function computerValue(uint _x) external pure returns (uint) {
        //assert statement in device
        assert(_x != 2);
        return _x + 600;
    }

    function printerValue(uint _y) external pure returns (uint) {
        //revert statement in device
        if (_y == 2) {
            revert("The value is sum");
        }
        return _y + 100;
    }
}
