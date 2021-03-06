## Tools in the ecosystem

#### Linters / Refactoring

* `hlint`: suggests changes to simplify code and make it easier to read -
  ([github](https://github.com/ndmitchell/hlint),
  [hackage](https://hackage.haskell.org/package/hlint),
  [website](http://community.haskell.org/~ndm/hlint/))
* `HaRe`: Haskell Refactoring Tool -
  ([github](https://github.com/alanz/HaRe),
  [website](http://www.cs.kent.ac.uk/projects/refactor-fp/))
* :skull: `dead-code-detection`: Detects dead code in haskell projects -
  ([github](https://github.com/soenkehahn/dead-code-detection),
  [hackage](http://hackage.haskell.org/package/dead-code-detection))
* `weeder`: Detect dead exports or package imports -
  ([github](https://github.com/ndmitchell/weeder),
  [hackage](http://hackage.haskell.org/package/weeder))
* :skull: `argon`: Monitor cyclomatic complexity in Haskell programs -
  ([github](https://github.com/rubik/argon),
  [hackage](http://hackage.haskell.org/package/argon))
* :skull: `style-scanner`: Lexical style suggestions for source code -
  ([darcs](http://code.haskell.org/style-scanner/),
  [hackage](http://hackage.haskell.org/package/scan),
  [website](http://projects.haskell.org/style-scanner/))
* `stylish-haskell`: Haskell code prettifier -
  ([github](https://github.com/jaspervdj/stylish-haskell),
  [hackage](http://hackage.haskell.org/package/stylish-haskell))
* `hindent`: Extensible Haskell pretty printer -
  ([github](https://github.com/chrisdone/hindent),
  [hackage](https://hackage.haskell.org/package/hindent))
* `apply-refact`: Refactoring tool.  Can apply the suggestions from `hlint`.
  ([github](https://github.com/mpickering/apply-refact),
  [hackage](http://hackage.haskell.org/package/apply-refact),
  [blog post](http://mpickering.github.io/posts/2015-11-22-hlint-refactor.html))
* :skull: `pointfree`: Tool for refactoring expressions into pointfree form -
  ([hackage](http://hackage.haskell.org/package/pointfree)
  [haskell wiki](https://wiki.haskell.org/Pointfree)
  [github](https://github.com/bmillwood/pointfree))
* `pointful`: Tool for refactoring expressions into pointfull form -
  ([github](https://github.com/23Skidoo/pointful),
  [hackage](http://hackage.haskell.org/package/pointful))
* `hfmt`: Code reformatter, using hlint, hindent, and stylish-haskell -
  ([hackage](http://hackage.haskell.org/package/hfmt),
  [github](https://github.com/danstiner/hfmt))
* `hsimport`: extend imports list, only if the given symbol is not already imported
  ([github](https://github.com/dan-t/hsimport),
  [hackage](http://hackage.haskell.org/package/hsimport))
* `refact-global-hse`: - Global haskell source code refactorings (e.g. move declarations between modules) -
  ([github](https://github.com/ddssff/refact-global-hse)
* :skull: `module-management` : Clean up module imports, split and merge modules
  ([hackage](https://hackage.haskell.org/package/module-management),
  [github](https://github.com/seereason/module-management))

#### Documentation generation / lookup

* `haddock`: A Haskell Documentation generation Tool -
  ([github](https://github.com/haskell/haddock),
  [website](https://www.haskell.org/haddock/))
* `hayoo`: Search Hackage by function, signature or package -
  ([app](http://hayoo.fh-wedel.de/),
  [github](https://github.com/hunt-framework/hayoo),
  [hackage](http://hackage.haskell.org/package/Hayoo))
* `hoogle`: Haskell API search engine -
  ([haskell wiki](https://wiki.haskell.org/Hoogle),
  [haskell.org app](https://www.haskell.org/hoogle/),
  [stackage.org app](http://www.stackage.org/),
  [hackage](http://hackage.haskell.org/package/hoogle),
  [github](https://github.com/ndmitchell/hoogle))
* `doctest` - checks examples in source code comments and include them in generated documentation-
  ([github](https://github.com/sol/doctest),
  [hackage](https://hackage.haskell.org/package/doctest))
* `haskell-indexer` - Emits code crossreference data for Haskell sources -
   ([github](https://github.com/google/haskell-indexer))

#### console / REPL

* `ghci`: ...
* `ghci-ng`: ...
* `ghc-vis` - Visualize live data structures in GHCi -
  ([github](https://github.com/def-/ghc-vis),
  [hackage](http://hackage.haskell.org/package/ghc-vis))
* `intero` - Complete interactive development program for Haskell in Emacs built around an ghci fork -
  ([github](https://github.com/commercialhaskell/intero),
  [hackage](https://hackage.haskell.org/package/intero),
  [site](http://commercialhaskell.github.io/intero/))

#### Ide backends

* `ghc-mod`: Haskell ide-backend -
  ([github](https://github.com/kazu-yamamoto/ghc-mod),
  [hackage](https://hackage.haskell.org/package/ghc-mod),
  [website](http://www.mew.org/~kazu/proj/ghc-mod/))
* `hsdev`: ide backend: autocompletion, symbol info, go-to declaration, find references etc. -
  ([hackage](http://hackage.haskell.org/package/hsdev),
  [github](https://github.com/mvoidex/hsdev))
* `hint`: a huge subset of the GHC API wrapped in a simpler API -
  ([github](https://github.com/mvdan/hint),
  [hackage](http://hackage.haskell.org/package/hint))
* :skull: `ide-backend`: drives the GHC API to build, query, and run your code -
  ([github](https://github.com/fpco/ide-backend),
  [hackage](http://hackage.haskell.org/package/ide-backend))
* :skull: `buildwrapper`: A library and an executable that provide an easy API for a Haskell IDE
  ([github](https://github.com/JPMoresmau/BuildWrapper),
  [hackage](https://hackage.haskell.org/package/buildwrapper))
* :skull: `scion`: Haskell IDE library -
  ([hackage](https://hackage.haskell.org/package/scion))

#### Ctags generation

  * `haskdogs`: generate tags file for a project and its  dependencies
    ([github](https://github.com/grwlf/haskdogs),
    [hackage](https://hackage.haskell.org/package/haskdogs))
  * `codex`: A ctags file generator for cabal/stack project dependencies -
    ([github](https://github.com/aloiscochard/codex),
    [hackage](https://hackage.haskell.org/package/codex))
  * `hasktags`: Produces ctags tags and etags TAGS files for Haskell programs -
    ([github](https://github.com/MarcWeber/hasktags),
    [hackage](https://hackage.haskell.org/package/hasktags))
  * `fast-tags`: Produces ctags and etags for Haskell with quick addenda for changes when using vim -
    ([github](https://github.com/elaforge/fast-tags),
    [hackage](https://hackage.haskell.org/package/fast-tags))
  * :skull: `lushtags`: ... -
    ([github](https://github.com/bitc/lushtags))
  * :skull: `gasbag`: ... -
    ([github](http://kingfisher.nfshost.com/sw/gasbag))
  * :skull: `hothasktags`: ... -
    ([github](http://hackage.haskell.org/package/hothasktags))

#### Code Generation

  * :skull: `djinn`: Generate Haskell code from a type -
    ([github](https://github.com/augustss/djinn),
    [hackage](https://hackage.haskell.org/package/djinn),
    [lambda-the-ultimate](http://lambda-the-ultimate.org/node/1178))
  * :skull: `exference`: Haskell tool to generate expressions from types.
    [github](https://github.com/lspitzner/exference/)
    [pdf](https://github.com/lspitzner/exference-paper/raw/master/exference.pdf)

#### Others...

* `liquid haskell`: Refinement Types: static verifier for Haskell, based on Liquid Types -
  ([github](https://github.com/ucsd-progsys/liquidhaskell),
  [website](http://goto.ucsd.edu/~rjhala/liquid/haskell/blog/about/))
* `sbv`: Express properties about Haskell programs and automatically prove them using SMT solvers - 
  ([github](https://github.com/LeventErkok/sbv),
  [hackage](https://hackage.haskell.org/package/sbv),
  [website](http://leventerkok.github.io/sbv/))
* `ghc-proofs`: GHC plugin to prove program equations by simplification -
  ([github](https://github.com/nomeata/ghc-proofs),
  [hackage](http://hackage.haskell.org/package/ghc-proofs))
* `mote`: (Agda Style programmer's assistant for Vim) -
  ([github](https://github.com/imeckler/mote))
* `flycheck-haskell`: Improved Haskell support for Emacs Flycheck -
  ([github](https://github.com/flycheck/flycheck-haskell))
* :skull: `illuminate` : source-code syntax highlighting library and a command-line highlighting tool -
  ([github](http://github.com/jgm/illuminate),
  [hackage](https://hackage.haskell.org/package/illuminate))
* :skull: `hscope`: partial cscope line oriented mode reimplementation for Haskell code -
  ([github](https://github.com/bosu/hscope),
  [hackage](https://hackage.haskell.org/package/hscope))
