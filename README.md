# Fractionalized Asset Protocol — FAP

_Fractionalized Asset Protocol_, abbreviated as _FAP_, is a simple protocol/convention for fractionalizing Ordinals asset ownership via a token issued using the [Runes protocol](https://docs.ordinals.com/runes.html).

# Protocol

Any premined or minted Rune represent a fraction (proportionate to the total supply) of the inscription(s) spent to `op_return` in the etching reveal transaction.

# Examples

## New Inscription

[FAP•WIZARDS•FAP](https://ordinals.com/rune/FAP•WIZARDS•FAP) is the first ever Rune created following the _FAP_ convention, fractionalizing [The Wizards of Ord](https://twitter.com/TheWizardsOfOrd) logo into 3,333 tokens.

Few things to note re: _FAP•WIZARDS•FAP_'s [etching reveal transaction](https://ordinals.com/tx/739bd9c74cb7924cb10b1d1d723067a74b52c41482a7f3b9a87ccca847bdbcf9).

- It creates the [inscription](https://ordinals.com/inscription/739bd9c74cb7924cb10b1d1d723067a74b52c41482a7f3b9a87ccca847bdbcf9i0) being fractionalized.
- Spends the newly created inscription to [first output](https://ordinals.com/output/739bd9c74cb7924cb10b1d1d723067a74b52c41482a7f3b9a87ccca847bdbcf9:0), which is an _op_return_. Verifiably burned forever.
- Premines 3,333 tokens to [2nd output](https://ordinals.com/output/739bd9c74cb7924cb10b1d1d723067a74b52c41482a7f3b9a87ccca847bdbcf9:1).

## Existing Inscription(s)

_Not today._ But it's the same deal. Spend the existing inscription(s) to `op_return` in etching reveal transaction. Additionally, the optional etching inscription could be a delegate to the inscription being burned. That way, marketplaces and wallets can display the correct image.

## Author

[lifofifo](https://twitter.com/lifofifo)
