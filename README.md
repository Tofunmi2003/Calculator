# Calculator
This Project features a basic calculator built using the REMIX IDE, with Solidity as the programming language. The calculator demonstrates fundamental arithmetic operations executed on the Ethereum blockchain


// SPDX-License-Identifier: MIT

pragma solidity ^0.8.18;

// 1️⃣ Make a contract called Calculator
// 2️⃣ Create Result variable to store result
// 3️⃣ Create functions to add, subtract, and multiply to result
// 4️⃣ Create a function to get result




contract calculator{
    uint256 result = 0;

    function add( uint256 num ) public {
         result += num;

    }
    function subtract(uint256 num) public {
        result -=num;
    }

    function multiply(uint256 num) public {
        result *=num;
    }
    function get() public view returns (uint256){
        return result;
    }
}
