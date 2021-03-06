# Changelog

## 1.4.3
- Fixed issue #23 for Linux.

## 1.4.2
- Added more commands/fixes (kborowinski).

## 1.4.1
- Added support for more sjasmplus directives thanks to kborowinski.

## 1.4.0
- New icon.

## 1.3.2
- Fixed falsy recognition of opcodes as labels.

## 1.3.1
- Improved 'Goto Definition' and 'Rename' for concatenated (sjasmplus) labels.

## 1.3.0
- Settings fixed.
- Added settings for globbing include and exclude files.
- Fixed error reading files, sometimes wrong data was read, i.e. sometimes labels were not found.

## 1.2.2
- Added Z80 register names as proposals for completions.
- Fixed "Go to definition" for sjasmplus macros.

## 1.2.1
- Fix for hovering local labels.
- Completions for z80 instructions.

## 1.2.0
- Better support fo sjasmplus dot label notation.
- Support for sjasmplus macros.
- Recognizes sjasmplus MODULE keyword in assembly files.
- 'Go to definition' also for INCLUDE files.
- Completions implemented. Also supports sjasmplus dots notation and MODULEs.
- New settings: enableCompletions, completionsRequiredLength.
- Unit tests for regular expressions.
- Configurable through settings.json.
- Added syntax highlighting.

## 1.1.0
- HoverProvider can be enabled/disabled in the settings.
- DefinitionProvider added.
- New Command: asm-code-lens.find-labels-with-no-reference. Searches all labels and shows the ones that are not referenced.
- Bugfixes.

## 1.0.1
- Readme updated.

## 1.0.0
- Initial marketplace release.

## 0.2.0
Added.
- Code Lens
- Hover support
- Symbol renaming

## 0.1.0
- Initial version. Support for "Find all references".

