# Quipper 

This is a copy of the [Quipper language v0.8](https://www.mathstat.dal.ca/~selinger/quipper/) with some minor modifications so that it is compatible with GHC 8.4.3 and containers 0.6.X.

## Modifications

`Libraries/ShowAll.hs`
: Added `OVERLAPPABLE` pragma on general `Show` instance

`quipper/Quipper/Printing.hs`
: Replaced `Map.insertWith'` with `Map.Strict.insertWith`
