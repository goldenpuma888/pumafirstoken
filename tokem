// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract CosmicToken is ERC20, Ownable {
    constructor() ERC20("Cosmic", "COSMIC") Ownable(msg.sender) {
        // Mint 69 million tokens to the deployer
        _mint(msg.sender, 69000000 * 10 ** decimals());
    }
}
