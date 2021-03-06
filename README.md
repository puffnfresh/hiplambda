# HipLambda [![TravisCI](https://travis-ci.org/purefn/hiplambda.svg)](https://travis-ci.org/purefn/hiplambda) [![Hackage](https://img.shields.io/hackage/v/hiplambda.svg?style=flat)](https://hackage.haskell.org/package/hiplambda) [![Dependencies](https://img.shields.io/hackage-deps/v/hiplambda.svg?style=flat)](http://packdeps.haskellers.com/feed?needle=hiplambda)

A HipChat bot in the spirit of Lambdabot providing useful commands use as

* Haskell evaluation: `> take 5 [1..] ==> [1,2,3,4,5]`
* Pointfree refactoring: `/pf \xs n -> take n xs ==> flip take`
* Asking for a functions type, like GHCi's `:t`, using either that or `:type`
* Using Hoogle: `/hoogle [a] -> [a]`
* More to come

[Add it to your room](https://hipchat.com/addons/install?url=https%3A%2F%2Fhiplambda.atlassian.com%2F)
