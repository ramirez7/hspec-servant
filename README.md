## hspec-wai-servant
Write tests in the style of [Test.Hspec.Wai](https://hackage.haskell.org/package/hspec-wai-0.8.0) for your Servant APIs

Just `import Test.Hspec.Wai.Servant` and you're good to go! Don't import `Test.Hspec.Wai` as `hspec-wai-servant` shadows some of its bindings; however, `hspec-wai-servant` does re-export some useful things from `hspec-wai`.

See tests for usage examples.

Not every servant API combinator is implemented yet.
