# warpx/src/language/c.rs

- **Language:** Rust
- **Semantic model:** 0.1.0
- **Analyzer:** rust-analyzer
- **Source lines:** 394

## Symbols

- **Function** `analyze` — `fn( root: &Path, sources: &[SourceFile], clang: &Path, ) -> Result<Vec<SemanticFile>, String>` (Known) — line 11, column 8, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@11:8`
- **Variable** `mut output` — line 16, column 9, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@16:9`
- **Variable** `result` — line 18, column 13, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@18:13`
- **Variable** `ast` — `Value` (Known) — line 38, column 13, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@38:13`
- **Variable** `stderr` — line 39, column 17, scope `analyze::ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@39:17`
- **Variable** `mut file` — line 46, column 13, scope `analyze`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@46:13`
- **Function** `walk_ast` — `fn( node: &Value, source_text: &str, source: &SourceFile, output: &mut SemanticFile, in_source_file: bool, ) -> bool` (Known) — line 62, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@62:4`
- **Variable** `Some(kind)` — line 69, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@69:9`
- **Variable** `in_source_file` — line 72, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@72:9`
- **Variable** `offset` — line 78, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@78:9`
- **Variable** `has_source_location` — line 79, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@79:9`
- **Variable** `name` — line 81, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@81:9`
- **Variable** `ty` — line 82, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@82:9`
- **Variable** `node_location` — line 87, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@87:9`
- **Variable** `offset` — line 108, column 13, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@108:13`
- **Variable** `symbol_kind` — line 109, column 13, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@109:13`
- **Variable** `value` — line 138, column 21, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@138:21`
- **Variable** `semantic_operation` — line 151, column 9, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@151:9`
- **Variable** `inner` — line 166, column 13, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@166:13`
- **Variable** `operands` — `Vec<String>` (Known) — line 167, column 13, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@167:13`
- **Variable** `mut child_in_source_file` — line 217, column 13, scope `walk_ast`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@217:13`
- **Function** `same_file` — `fn(left: &Path, right: &Path) -> bool` (Known) — line 227, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@227:4`
- **Variable** `left` — line 228, column 9, scope `same_file`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@228:9`
- **Variable** `right` — line 229, column 9, scope `same_file`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@229:9`
- **Function** `operation_kind` — `fn(opcode: &str) -> Option<OperationKind>` (Known) — line 233, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@233:4`
- **Function** `control_flow_kind` — `fn(node_kind: &str) -> Option<&'static str>` (Known) — line 253, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@253:4`
- **Function** `source_text_for_node` — `fn(node: &Value, source: &str) -> String` (Known) — line 267, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@267:4`
- **Variable** `range` — line 268, column 9, scope `source_text_for_node`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@268:9`
- **Variable** `begin` — line 269, column 9, scope `source_text_for_node`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@269:9`
- **Variable** `end` — line 274, column 9, scope `source_text_for_node`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@274:9`
- **Function** `location_offset` — `fn(node: &Value) -> Option<usize>` (Known) — line 289, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@289:4`
- **Function** `location` — `fn(node: &Value, source: &str) -> SourceLocation` (Known) — line 302, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@302:4`
- **Variable** `offset` — line 303, column 9, scope `location`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@303:9`
- **Variable** `prefix` — line 305, column 13, scope `location`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@305:13`
- **Function** `parse_clang_diagnostics` — `fn(stderr: &[u8], source: &SourceFile) -> Vec<crate::model::Finding>` (Known) — line 331, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@331:4`
- **Variable** `text` — line 332, column 9, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@332:9`
- **Variable** `trimmed` — line 335, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@335:17`
- **Variable** `(location_text, message_part)` — line 336, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@336:17`
- **Variable** `(severity, message)` — line 337, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@337:17`
- **Variable** `mut parts` — line 344, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@344:17`
- **Variable** `column` — line 345, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@345:17`
- **Variable** `line_number` — line 346, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@346:17`
- **Variable** `severity` — line 347, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@347:17`
- **Variable** `rule_id` — line 352, column 17, scope `parse_clang_diagnostics`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@352:17`
- **Variable** `severity_name` — line 357, column 25, scope `parse_clang_diagnostics::rule_id`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@357:25`
- **Function** `first_line` — `fn(text: &str) -> &str` (Known) — line 390, column 4, scope `module`, 0 reference(s), semantic ID `warpx/src/language/c.rs#symbol@390:4`

## Findings

No findings were reported with the available semantic evidence.
