# Revision History

Repository-local revision summary.

| Commit | Timestamp | Message |
| --- | --- | --- |
| `06d2808` | `2026-03-02T09:28:56Z` | chore(release): 1.13.0 [skip ci] |
| `c1c3bc2` | `2026-03-01T16:15:55+01:00` | Merge pull request #17 from andrea9293/dev/handle-database |
| `b675c47` | `2026-03-01T16:14:00+01:00` | feat: enhance document management with new tools for deleting documents, retrieving web UI URL, and processing uploads |
| `4cdbd5d` | `2026-03-01T01:44:17+01:00` | feat: enhance document management with parent chunk retrieval and context window navigation |
| `a6e1991` | `2026-03-01T01:01:59+01:00` | feat: implement parent-child deduplication and enhance document formatting in search results |
| `6a6b7ca` | `2026-03-01T00:44:22+01:00` | feat: implement parent-child chunking pattern with separate parents DB |
| `9e3a2c8` | `2026-03-01T00:19:04+01:00` | feat: enhance README with detailed web UI features and usage instructions |
| `34aee75` | `2026-03-01T00:18:16+01:00` | feat: add web server for document management and search API |
| `09a66ad` | `2026-02-28T23:47:34+01:00` | Refactor DocumentManager to integrate Orama for document storage and search |

## 2026-03-13
- Recorded and prepared local enhancements for publication.
- Updated repository documentation to reflect current operational and integration changes.

## 2026-03-17
- Fixed local MCP startup compatibility by moving Web UI banner output from stdout to stderr so stdio clients can initialize without disabling `START_WEB_UI`.
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `9a1810b12ffd` | first commit |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4bc80ec913b4` | Refactor search engine and server for improved embedding management and document processing |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d8b1c0f7ec77` | Initial commit |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `edf04bd73cde` | feat: Update package configuration and embedding model |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `24357e35dbca` | Merge branch 'main' of https://github.com/andrea9293/mcp-documentation-server |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `3c21a05c96a7` | fix: update workflow to handle test script and fix GitHub Actions configuration |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `1a3261527d38` | fix: update Node.js version in GitHub Actions workflow to 20 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `e96944f625a7` | chore(release): 1.0.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4602c1e6fa09` | feat: add publishConfig to package.json for public access |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `63b01119dd53` | Merge branch 'main' of https://github.com/andrea9293/mcp-documentation-server |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `3e0c929c8c02` | chore(release): 1.1.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d7674f413bc0` | fix: correct bin path in package.json for proper executable resolution |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4b291fe38c7b` | chore(release): 1.1.1 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `a527bc565d87` | Refactor server structure: move main logic from index.ts to server.ts, update package.json for entry point, and implement document deletion functionality |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `00329c4b147c` | feat: add comprehensive document deletion functionality and improve documentation |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `126a6696dab7` | chore(release): 1.2.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `40f8e1488af3` | fix: improve code readability by adding spacing in TransformersEmbeddingProvider |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `1fa17d9f8f8e` | feat: add PDF text extraction support |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `65f5db0c82d4` | chore(release): 1.3.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `2d1a9c9cad28` | feat: enhance file upload support and improve directory management in DocumentManager |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `ef86cdf225f0` | chore(release): 1.4.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `7920c595c82e` | feat: increase content preview length in get_document tool |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4d752039500e` | chore(release): 1.5.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d63f291e647b` | Create SECURITY.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `e1e5e70e8ecf` | Create CODE_OF_CONDUCT.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4900d4d2b2f4` | Create CONTRIBUTING.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `adb5086d3ab4` | Update issue templates |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `73d1b6465619` | docs: update README with new command arguments and environment variable for embedding model add Code of Conduct, Contributing guidelines, and Security Policy documents |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `0e2d3487cb52` | remove example MCP configuration file |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `8cbc51ac1b3a` | Update LICENSE |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `7397bcfe30c9` | fix: update document search logic and improve error handling |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `ddf4e1cc3e6a` | fix: update search_documents tool to include query parameter for improved search functionality |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `61fc29727928` | chore(release): 1.5.1 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `5ed75494a64e` | Update README.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `77e28a8f9223` | Initial plan |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d5d57c19d016` | Initial analysis: dotenv not imported causing env vars to be ignored |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `b91f5781bd3f` | fix: add dotenv import to load environment variables from .env files |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `dacef36664ec` | chore: remove accidental .env.backup file |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `90f99f084fcd` | Add MseeP.ai badge to README.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d7dc3c94d246` | feat: implement intelligent chunking for document processing |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d8b3321cac4a` | feat: enhance embedding providers with model dimensions and lazy initialization |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `f94746bd1b2b` | feat: add getOnlyContentDocument method and get_context_window tool; enhance EmbeddingProvider with getDimensions |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `c92f530cf6da` | feat: add get_context_window tool to retrieve surrounding chunks of a document |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `8750830b9f62` | feat: enhance search_documents tool with truncation notice and context retrieval hint |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `77514d8b312d` | feat: update README to enhance feature descriptions and add context window retrieval example |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `211828cc2fed` | Merge pull request #3 from lwsinclair/add-mseep-badge |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `7a9414677e77` | Merge pull request #2 from andrea9293/copilot/fix-1 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `086aee962d66` | chore(release): 1.6.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `0678442781b4` | docs: add NPM package badge to README for better visibility |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `e00ae10e73c9` | docs: add star history |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `1b29f708bafd` | docs: add funding configuration for GitHub and Buy Me a Coffee |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `3cbfba1f664f` | Update README.md |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `66e3f293b0e8` | Update README.md - add deepwiki doc |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `c202ee512456` | feat: update all docs e and bugfixing |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `b91d8de88c2b` | chore(release): 1.7.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `45b0d17ac25b` | Initial plan |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d522a77872f5` | Initial analysis - identify critical pdf-ts vulnerability (CVE-2024-4139) |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4a160607e840` | Replace vulnerable pdf-ts with safe unpdf library |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d2458bc61d48` | Update security documentation for PDF vulnerability fix |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `f568f03504b3` | Merge pull request #6 from andrea9293/copilot/fix-5 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `f28f93b4c26d` | feat: Fix critical PDF vulnerability (CVE-2024-4139) by replacing pdf-ts with unpdf |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d9e9aa461e7d` | chore(release): 1.8.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4b6c42e4f77f` | docs: Add scalability analysis document outlining critical bottlenecks and proposed improvements for MCP Documentation Server |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `315c01484226` | Initial plan |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `87002dcb8888` | Initial analysis complete - implement Phase 1 scalability improvements |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `fb15510ff420` | Implement Phase 1 scalability improvements: indexing, caching, parallel processing, streaming |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `561c1cdc3f37` | feat: Phase 1 (scalability) - O(1) DocumentIndex, LRU embedding cache, parallel chunking & streaming |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `1752020ba778` | Merge pull request #7 from andrea9293/copilot/fix-ab749cd5-6bc6-419b-ab43-2a1d2edacba6 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `f17051a59536` | chore(release): 1.9.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `a437bb34f362` | docs: Update CHANGELOG for Phase 1 scalability improvements |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `2f01eba01554` | feat: add readme to reflect the status of the server |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `90d723b8fb37` | chore(release): 1.10.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `c1f551188d13` | update .gitignore to include ROADMAP.md and ensure proper formatting |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `9425fc17410e` | Merge branch 'main' of https://github.com/andrea9293/mcp-documentation-server |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `ccd92e164b63` | fix(indexing): avoid fs-extra ESM/CJS interop causing fs.readdir error |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `19bc688c0688` | Merge pull request #9 from andrea9293/andrea9293/issue8 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `b94270eb1b58` | chore(release): 1.10.1 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `30621bcf8f0f` | update lockfile for consistency |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `3f4163952c51` | chore: update .gitignore to include temporary folders and remove Scalability Analysis document |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `a8d52d2823cf` | Refactor Document Management System |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `ea9c33b2f849` | chore: clean up unused code and improve code organization |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `136a3395ec41` | refactor: update ID generation to use SHA-256 hash of document content |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `692d251ad33b` | Merge pull request #10 from andrea9293/andrea9293/vectra-branch-dev |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `db31495312f8` | feat: add file backup functionality during document upload |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `b2fd3086f3b1` | feat: enhance document deletion to remove associated files and improve error handling |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `34e09600e46e` | feat: integrate Gemini AI for advanced document search |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `3f223e612266` | docs: update README to include instructions for obtaining Google AI API key |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `ff663db8f1fd` | Merge pull request #11 from andrea9293:andrea9293/gemini-mode-dev |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `c7e5f4b1eda8` | chore(release): 1.11.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `dc9af088db20` | docs: update CHANGELOG for Gemini AI integration and file management enhancements; bump version to 1.11.0 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `52e19e493062` | fix(server): add_document metadata parameters description adjusted |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `e704267536f1` | fix(document-manager): improve PDF extraction method documentation |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `5be29366f50e` | Merge pull request #12 from serge-medvedev/fix-add-document-metadata |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `bcc1a8781674` | chore(release): 1.11.1 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d919872a03a0` | docs: update changelog |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d5c8f8e54160` | Initial plan |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `eaa5cf84b893` | feat: add configurable base directory via MCP_BASE_DIR env var |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `fd263d72158b` | refactor: trim whitespace from MCP_BASE_DIR env var |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `f4e14babdad2` | fix: upgrade fastmcp to v3.24.0 |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `00a0a676b622` | Merge pull request #16 from Masashi-Lateolabrax/fix-completions-error |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `405dc8307017` | chore(release): 1.11.2 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d27443432ca5` | Merge pull request #14 from andrea9293/copilot/add-configurable-base-directory |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `d11dd7e0a12a` | chore(release): 1.12.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `09a66ad0ed8a` | Refactor DocumentManager to integrate Orama for document storage and search |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `34aee75a71b4` | feat: add web server for document management and search API |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `9e3a2c860274` | feat: enhance README with detailed web UI features and usage instructions |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `6a6b7ca43ba2` | feat: implement parent-child chunking pattern with separate parents DB |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `a6e1991eed34` | feat: implement parent-child deduplication and enhance document formatting in search results |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `4cdbd5dbb79c` | feat: enhance document management with parent chunk retrieval and context window navigation |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `b675c47a4db1` | feat: enhance document management with new tools for deleting documents, retrieving web UI URL, and processing uploads |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `c1c3bc29655e` | Merge pull request #17 from andrea9293/dev/handle-database |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `06d28086dd3f` | chore(release): 1.13.0 [skip ci] |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `0174768c8ece` | docs: add repository revision history summary |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `0809de944355` | docs: capture local enhancements and sync local updates (2026-03-13) |
| 2026-03-17T06:27:40.438601+00:00 | main | origin | `dfe43dddbe2d` | fix: log web ui banner to stderr |
