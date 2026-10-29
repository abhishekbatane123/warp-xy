# warpx/src/report.rs

- **Language:** Rust
- **Semantic model:** 0.1.0
- **Analyzer:** rust-analyzer
- **Source lines:** 227

## Symbols

- **Function** `write_reports` — `fn(root: &Path, files: &[SemanticFile]) -> Result<usize, String>` (Known) — line 8, column 8, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@8:8`
- **Variable** `report_root` — line 9, column 9, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@9:9`
- **Variable** `mut output_sources` — line 10, column 9, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@10:9`
- **Variable** `report_path` — line 12, column 13, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@12:13`
- **Variable** `relative_report` — line 27, column 13, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@27:13`
- **Variable** `destination` — line 28, column 13, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@28:13`
- **Variable** `markdown` — line 33, column 13, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@33:13`
- **Variable** `temp_path` — line 34, column 13, scope `write_reports`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@34:13`
- **Function** `report_path` — `fn(source_path: &Path) -> PathBuf` (Known) — line 43, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@43:4`
- **Variable** `mut report` — line 44, column 9, scope `report_path`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@44:9`
- **Function** `render_file` — `fn(file: &SemanticFile) -> String` (Known) — line 49, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@49:4`
- **Variable** `source` — line 50, column 9, scope `render_file`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@50:9`
- **Variable** `mut markdown` — line 51, column 9, scope `render_file`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@51:9`
- **Variable** `properties` — line 107, column 21, scope `render_file`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@107:21`
- **Variable** `mut findings` — line 172, column 13, scope `render_file`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@172:13`
- **Function** `render_finding` — `fn(markdown: &mut String, finding: &Finding)` (Known) — line 186, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@186:4`
- **Function** `analyzer_name` — `fn(extension: &LanguageExtension) -> &str` (Known) — line 199, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@199:4`
- **Function** `confidence_text` — `fn(confidence: Confidence) -> &'static str` (Known) — line 207, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@207:4`
- **Function** `escape_inline` — `fn(text: &str) -> String` (Known) — line 211, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@211:4`
- **Module** `tests` — line 216, column 5, scope `module`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@216:5`
- **Function** `preserves_nested_source_path_in_report_mapping` — `fn()` (Known) — line 221, column 8, scope `tests`, 0 reference(s), semantic ID `warpx/src/report.rs#symbol@221:8`

## Findings

No findings were reported with the available semantic evidence.
