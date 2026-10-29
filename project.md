# warpx/src/project.rs

- **Language:** Rust
- **Semantic model:** 0.1.0
- **Analyzer:** rust-analyzer
- **Source lines:** 123

## Symbols

- **Constant** `IGNORED_DIRECTORIES` — `&[&str]` (Known) — line 7, column 7, scope `module`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@7:7`
- **Function** `discover` — `fn(root: &Path) -> Result<Vec<SourceFile>, String>` (Known) — line 28, column 8, scope `module`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@28:8`
- **Variable** `root` — line 29, column 9, scope `discover`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@29:9`
- **Variable** `mut paths` — line 35, column 9, scope `discover`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@35:9`
- **Variable** `relative_path` — line 42, column 17, scope `discover`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@42:17`
- **Variable** `source` — line 46, column 17, scope `discover`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@46:17`
- **Variable** `language` — line 48, column 17, scope `discover`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@48:17`
- **Function** `visit` — `fn(root: &Path, directory: &Path, output: &mut Vec<PathBuf>) -> Result<(), String>` (Known) — line 64, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@64:4`
- **Variable** `entries` — line 65, column 9, scope `visit`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@65:9`
- **Variable** `entry` — line 68, column 13, scope `visit`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@68:13`
- **Variable** `file_type` — line 69, column 13, scope `visit`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@69:13`
- **Variable** `path` — line 75, column 13, scope `visit`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@75:13`
- **Function** `language_for_path` — `fn(path: &Path) -> Option<Language>` (Known) — line 93, column 8, scope `module`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@93:8`
- **Module** `tests` — line 103, column 5, scope `module`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@103:5`
- **Function** `detects_only_the_three_supported_languages` — `fn()` (Known) — line 109, column 8, scope `tests`, 0 reference(s), semantic ID `warpx/src/project.rs#symbol@109:8`

## Findings

No findings were reported with the available semantic evidence.
