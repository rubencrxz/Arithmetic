# 🧮 Arithmetic

This repository entry is a compact deep-dive into how numeric computation actually works on Ethereum: the EVM’s 256-bit modular arithmetic model, Solidity ≥0.8 checked math, and the security implications of division/rounding choices. It then systematizes fixed-point conventions used across DeFi, shows why mulDiv (512-bit intermediates) and explicit rounding helpers are foundational, and highlights common footguns around signedness, casting, shifts and packed storage decoding, connecting these ideas to real protocol math patterns.
