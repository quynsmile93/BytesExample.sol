# BytesExample.sol
BytesExample.sol
pragma solidity ^0.8.20;
contract BytesExample {
    function getBytes() public pure returns(bytes memory) {
        return "hello";
    }
}
