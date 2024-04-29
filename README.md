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

[THE•GREAT•FAPPENING](https://ordinals.com/rune/THE%E2%80%A2GREAT%E2%80%A2FAPPENING) Rune demonstrate how to fractionalize an existing inscription with the _FAP_ convention.

The [etching reveal transaction](https://ordinals.com/tx/55eb1bd8afad48878e75c28bf3df925c869fa2cc55f92ece92408886cd92af81) does the following:

- Spends [Wizard #1](https://ordinals.com/inscription/30a522e76569be8ec88bcfc60a6e81cdba2d0ce7dbc3afce06f39cae7ae5e10ci0) inscription to the _op_return_ [output](https://ordinals.com/output/55eb1bd8afad48878e75c28bf3df925c869fa2cc55f92ece92408886cd92af81:0).
- Creates a [new inscription](https://ordinals.com/inscription/55eb1bd8afad48878e75c28bf3df925c869fa2cc55f92ece92408886cd92af81i0) on the [same sat](https://ordinals.com/sat/394947743645) as Wizard #1, and spends it to the _op_return_ [output](https://ordinals.com/output/55eb1bd8afad48878e75c28bf3df925c869fa2cc55f92ece92408886cd92af81:0) as well. By default, this inscription will be used by the marketplaces and wallets as the Rune image. It does not need to be a re-inscription on the asset being burned.
- Premines 1,111 💦 _THE•GREAT•FAPPENING_ Runes to [2nd output](https://ordinals.com/output/55eb1bd8afad48878e75c28bf3df925c869fa2cc55f92ece92408886cd92af81:1), representing the burned [Wizard #1](https://ordinals.com/inscription/30a522e76569be8ec88bcfc60a6e81cdba2d0ce7dbc3afce06f39cae7ae5e10ci0).

## Author

[lifofifo](https://twitter.com/lifofifo)
