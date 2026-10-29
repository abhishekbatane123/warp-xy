# warpx/src/language/mod.rs

- **Language:** Rust
- **Semantic model:** 0.1.0
- **Analyzer:** rust-analyzer
- **Source lines:** 208

## Symbols

- **Module** `c` — line 1, column 16, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@1:16`
- **Module** `lsp` — line 2, column 5, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@2:5`
- **Function** `analyze` — `fn(root: &Path, sources: &[SourceFile]) -> Result<Vec<SemanticFile>, String>` (Known) — line 14, column 8, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@14:8`
- **Variable** `mut by_language` — `BTreeMap<Language, Vec<SourceFile>>` (Known) — line 15, column 9, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@15:9`
- **Variable** `mut output` — line 23, column 9, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@23:9`
- **Variable** `mut analyzed` — line 25, column 13, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@25:13`
- **Variable** `command` — line 27, column 21, scope `analyze::mut analyzed`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@27:21`
- **Variable** `command` — line 40, column 21, scope `analyze::mut analyzed`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@40:21`
- **Variable** `command` — line 54, column 21, scope `analyze::mut analyzed`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@54:21`
- **Function** `find_analyzer` — `fn(name: &str, root: &Path) -> Result<PathBuf, String>` (Known) — line 64, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@64:4`
- **Variable** `local` — line 65, column 9, scope `find_analyzer`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@65:9`
- **Variable** `candidate` — line 71, column 17, scope `find_analyzer`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@71:17`
- **Variable** `guidance` — line 77, column 9, scope `find_analyzer`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@77:9`
- **Function** `analyzer_finding` — `fn( file: &SourceFile, diagnostic: &serde_json::Value, ) -> Option<Finding>` (Known) — line 88, column 15, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@88:15`
- **Variable** `message` — line 92, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@92:9`
- **Variable** `range` — line 96, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@96:9`
- **Variable** `start` — line 97, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@97:9`
- **Variable** `line` — line 98, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@98:9`
- **Variable** `column` — line 103, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@103:9`
- **Variable** `severity` — line 108, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@108:9`
- **Variable** `rule_id` — line 118, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@118:9`
- **Variable** `evidence` — line 132, column 9, scope `analyzer_finding`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@132:9`
- **Function** `symbol_kind` — `fn(kind: u64) -> &'static str` (Known) — line 165, column 15, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@165:15`
- **Function** `type_certainty` — `fn(language: Language, detail: Option<&str>) -> TypeCertainty` (Known) — line 197, column 15, scope `module`, 0 reference(s), semantic ID `warpx/src/language/mod.rs#symbol@197:15`

## Findings

No findings were reported with the available semantic evidence.
