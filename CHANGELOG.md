# Changelog

## [1.1.0](https://github.com/Issafalcon/neotest-dotnet/compare/v1.0.0...v1.1.0) (2023-02-05)


### Features

* **sln-root:** Creating multiple specs for direcotory tree ([e6d91ed](https://github.com/Issafalcon/neotest-dotnet/commit/e6d91eda40c56e7fd7e7257da9c3204eab5d11f2))
* **sln-root:** Fix for file type position and more unit tests ([0c76827](https://github.com/Issafalcon/neotest-dotnet/commit/0c76827f948c25d45b58339d3e38e1d90502ab50))


### Bug Fixes

* **sln-root-dir:** Provides option to determine the root dir ([0905484](https://github.com/Issafalcon/neotest-dotnet/commit/0905484bda666c33bfbf7ae592cefd45e9543742))
* **sln-test-runs:** Fixing the error when running entire test suite ([e1697f5](https://github.com/Issafalcon/neotest-dotnet/commit/e1697f548b1b31c2a339a96bf29c6d10b31485db))

## 1.0.0 (2023-01-28)


### Features

* **build_spec:** Adding in initial dotnet test command to run tests ([101860b](https://github.com/Issafalcon/neotest-dotnet/commit/101860b8fd700e06762a2a408d07665996621696))
* **console-output:** Fixing console output to pick up results ([9dcd154](https://github.com/Issafalcon/neotest-dotnet/commit/9dcd1547ca36d583b916cc43af621e2f50de49f8))
* **custom_attributes:** Adding initial support for custom xunit attrs ([83b0a36](https://github.com/Issafalcon/neotest-dotnet/commit/83b0a36992b7e58bf7f5f482425d544c98b43e98))
* **custom_attributes:** Adding some attribute utils ([a6ce6c4](https://github.com/Issafalcon/neotest-dotnet/commit/a6ce6c47556bd7c7ac95d4c66728111cd80ab184))
* **custom_attributes:** Finalizing the custom attribute support ([2dd016d](https://github.com/Issafalcon/neotest-dotnet/commit/2dd016de88bb6ec6590c06a1712aa3993739b9ae))
* **debugging:** Debug support now working for Xunit (with some bugs) ([95dd030](https://github.com/Issafalcon/neotest-dotnet/commit/95dd030e2d1c2244f2708e1d5809f2f4e40dd851))
* **debugging:** Initial stab at debugging ([075f7ed](https://github.com/Issafalcon/neotest-dotnet/commit/075f7ed2369a81ca4133997b86a443122bb8cb6e))
* **debugging:** Updating README with debug info ([c0ceac4](https://github.com/Issafalcon/neotest-dotnet/commit/c0ceac4fb57e7dcb1e7c6b8230010c54d3abccba))
* **discover-positions:** Messing around with async scheduler ([4d6e5de](https://github.com/Issafalcon/neotest-dotnet/commit/4d6e5dea007b4ccf7836630763bb7e4b97b49542))
* **discover-positions:** moving over to using treesitter queries ([33a391f](https://github.com/Issafalcon/neotest-dotnet/commit/33a391f99107e31c64ad5ba51e79b8908be59751))
* **mpv:** Adding code for making requests on omnisharp-lsp ([f04370a](https://github.com/Issafalcon/neotest-dotnet/commit/f04370a6d440800bd896788bf4c17e8d0d862486))
* **mstest-support:** Adds support for mstest ([f6c3d20](https://github.com/Issafalcon/neotest-dotnet/commit/f6c3d20a97fcc9a9029537f8e7313b11a0eb14a8))
* **mstest-support:** Tidying up some duplicate code ([acea1fa](https://github.com/Issafalcon/neotest-dotnet/commit/acea1fa62163f900da6101f2e1758acb9ea6d798))
* **mvp:** Adding stylua and creating first skeleton outline of adapter ([572a085](https://github.com/Issafalcon/neotest-dotnet/commit/572a0859b50548aa01fb09c1e1a4e1969da90157))
* **mvp:** Additional omnisharp code for making requests on lsp ([9830d7f](https://github.com/Issafalcon/neotest-dotnet/commit/9830d7fafab7b7d93b6fade2aa56e31afe4ec017))
* **nunit-support:** First attempt to get strategy pattern working ([41dd81a](https://github.com/Issafalcon/neotest-dotnet/commit/41dd81a48f01ec3f422939782ed6d89383542eb6))
* **nunit-support:** Fixing the parameterized tests for nunit ([d4ad3c8](https://github.com/Issafalcon/neotest-dotnet/commit/d4ad3c8b96009f6a2afc0b34821586e09d174600))
* **nunit-support:** Marking nunit as supported in README ([f49e2ce](https://github.com/Issafalcon/neotest-dotnet/commit/f49e2ce094c41bf80ebddd9daccd3aa49e9315d6))
* **nunit-support:** Refactoring some of the ts-queries ([fdce4f0](https://github.com/Issafalcon/neotest-dotnet/commit/fdce4f0954b2c4f4c61cdcc244344b21a1b09f8e))
* **nunit-support:** Refactoring test utils to support multiframework ([2faffa7](https://github.com/Issafalcon/neotest-dotnet/commit/2faffa7586e61670f9f1689c569c643274b52a62))
* **nunit-support:** Still trying to get framework strategies to work ([d96c01c](https://github.com/Issafalcon/neotest-dotnet/commit/d96c01c6c1cbee73108ab4cc8d9f8d0f95ead7f2))
* **nunit-support:** Strategy pattern discovery for framework working ([762f33f](https://github.com/Issafalcon/neotest-dotnet/commit/762f33fa9894331d29d5100aae94a3256ab438f3))
* **omnisharp-removal:** Removing dependency on omnisharp in build_pos ([88c4215](https://github.com/Issafalcon/neotest-dotnet/commit/88c4215c98487d8bb3df324b1f7865f9ca630177))
* **omnisharp-removal:** Removing last dependency on LSP ([bcac8b5](https://github.com/Issafalcon/neotest-dotnet/commit/bcac8b51ec1f6d030bee0de3b213493b909b3676))
* **omnisharp-removal:** Tidying up specflow queries, add filter_dir ([2efa9fc](https://github.com/Issafalcon/neotest-dotnet/commit/2efa9fc7e86184537d37978c0c50c5dce6600f18))
* **parser:** Adding parser to get the tree of node elements ([d885034](https://github.com/Issafalcon/neotest-dotnet/commit/d88503440fc0efc6a20c798d52d275753677f900))
* **positions:** Updated parse function so it correctly parses tests ([57c2373](https://github.com/Issafalcon/neotest-dotnet/commit/57c237362b8248c7215f15fbdef5cfac64b75fba))
* **results:** Adding xml parsing for trx files ([1f25ebc](https://github.com/Issafalcon/neotest-dotnet/commit/1f25ebc92738e21eb1166222fc2195fdde9eddba))
* **results:** First iteration of test result output ([92a34a4](https://github.com/Issafalcon/neotest-dotnet/commit/92a34a49494338b19c715ccd64296fdb4635f8b5))
* **results:** Marshalling results into intermediate objects ([5dcd232](https://github.com/Issafalcon/neotest-dotnet/commit/5dcd23280be97999e3c04c3fe829c4fd03166918))
* stateless parsing ([493eb22](https://github.com/Issafalcon/neotest-dotnet/commit/493eb22bd1bb7e7651d09a89462b74c6b1c2f33a))
* **stateless-parsing:** Fixing naming of xunit tests ([2efabdc](https://github.com/Issafalcon/neotest-dotnet/commit/2efabdc433e856a61310fe63d7ee7255ae684594))
* **stateless-parsing:** Fixing the position ID for parameterized tests ([dfec475](https://github.com/Issafalcon/neotest-dotnet/commit/dfec475e241f54f65693188cdb0f126b849f9af5))
* **stateless-parsing:** Tidying up redundant code ([102b04a](https://github.com/Issafalcon/neotest-dotnet/commit/102b04a743e132397d75a60f34cbe18cbff503ab))
* **test-check:** Moving code structure according to convention ([6323e23](https://github.com/Issafalcon/neotest-dotnet/commit/6323e23fad9e5476d6304fc8fdd76250ef79a72a))
* **xunit-parameterized:** Initial attempt to split test queries ([269e50f](https://github.com/Issafalcon/neotest-dotnet/commit/269e50fd5170e0a21c03494976e877d810b7f19c))
* **xunit:** Getting parameterized tests to show up in summary ([fba1844](https://github.com/Issafalcon/neotest-dotnet/commit/fba1844501ff5cc49ecdb1642cc36e09c159fed8))
* **xunit:** Polishing support for parameterized tests xunit ([fb2013a](https://github.com/Issafalcon/neotest-dotnet/commit/fb2013aa32ba7abcc0405176c73775984b56a819))


### Bug Fixes

* **22:** Fixing issue when using directives for test framework missing ([f8d62dd](https://github.com/Issafalcon/neotest-dotnet/commit/f8d62dd61505fdfd3a3f413830f50cdbcad2ca9e))
* **28:** Use --results-directory instead of -r ([d313033](https://github.com/Issafalcon/neotest-dotnet/commit/d313033285f8ec0316d69874ba8921c7fef92131))
* **build-positions:** Adds support for file scoped namespace syntax ([e40cdf5](https://github.com/Issafalcon/neotest-dotnet/commit/e40cdf5547c523c0acc67f4192c8183b0126d71c))
* **custom_attributes:** Fixes dicovery error when custom attributes not provided ([30d2c02](https://github.com/Issafalcon/neotest-dotnet/commit/30d2c02df17ecc965879c7e0ad338ef4f4f0a087))
* Dynamically parameterized tests name matching ([109aec0](https://github.com/Issafalcon/neotest-dotnet/commit/109aec0e729999d12a3a1c70e4537b298cfc2aa6)), closes [#40](https://github.com/Issafalcon/neotest-dotnet/issues/40)
* **error-handling:** Handling LSP nil responses ([c53dedc](https://github.com/Issafalcon/neotest-dotnet/commit/c53dedc61c536a8144bfcdd71195322922b00ad7))
* **nunit-support:** Change test attribute variable name to match name used in queries ([c324f2f](https://github.com/Issafalcon/neotest-dotnet/commit/c324f2f0741821e31207e71efa0d5b634fccd890))
* **results:** Fixed bug in nunit skipped tests causing error ([acff63a](https://github.com/Issafalcon/neotest-dotnet/commit/acff63abb905959d6687b4f415752c18e13ba40e))
* **results:** Fixing unknown status output for skipped tests ([9b2e1e0](https://github.com/Issafalcon/neotest-dotnet/commit/9b2e1e087309405a7390a6820f0973093bc64d63))
* **results:** Handling runtime errors when no test results ([2fae64b](https://github.com/Issafalcon/neotest-dotnet/commit/2fae64b134a403ae75d3868d6e999b803eac9b48))
* **run-tests:** Fixing fully qualified path on windows ([8b4b5e4](https://github.com/Issafalcon/neotest-dotnet/commit/8b4b5e452b1702ab94d5abca7023d13231694781))
* **ts-queries:** Fixing name of unit test query file ([74649fc](https://github.com/Issafalcon/neotest-dotnet/commit/74649fca140ce79da23ee32112cac62a1ebc0e69))