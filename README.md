# NameStorage.sol
NameStorage.sol5
pragma solidity ^0.8.20;

contract NameStorage {
    string public name;

    function setName(string memory _name) public {
        name = _name;
    }
}
Refactor contract code
Remove debug code
Add comments for clarity
