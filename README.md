# stack-lh-min
stack exec ghc -- -v0 -package-env=- -ignore-dot-ghci -e "Control.Monad.join (Control.Monad fmap System.IO.putStr System.Environment.getExecutablePath)"

/Users/ashkan/.ghcup/tmp/ghcup-ghc-8.10.7_cabal-3.6.2.0_hls-1.7.0.0_stack-2.7.5/haskell-language-server-8.10.7
