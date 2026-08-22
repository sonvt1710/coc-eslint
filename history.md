## 3.1.2

- Release 3.1.2 (bf4173a)
- fix release.yml (994c937)
- not use npm whoami (b86f40d)
- improve npmignore (65d1a70)
- Release 3.1.1 (07238dd)
- use history.md (e764ed3)
- update vscode-languageserver (3705c93)
- address actionable GitHub issues (ff869c1)
- fix audit findings and expand tests (b1f8951)
- sync upstream changes for 3.1.0 (d86c4fa)
- add deprecationMessage (7fca5fb)
- Release 3.0.15 (1e45bdf)
- use context.asAbsolutePath (4185aac)
- extend default filtypes of eslint.probe (99ba86b)
- show information when no problem found with task (49cae36)
- doc (5864fc7)
- add important notice (e5a7cec)
- doc format (0d3bcc5)
- deprecationMessage of eslint.enable (ffd79f1)
- Release 3.0.14 (ae34b7d)
- Add a not for eslint.probe (5fc0601)
- doc (7342c35)
- fix url (df01b25)
- update tsconfig.json (3d15ac5)
- fix task output not parsed on eslint > 9 (4baeaa1)
- synchronize to vscode-eslint 3.0.13 (93642b1)
- Readme.md: add that eslint must be installed (#148) (5e10e82)
- fix: Wait for autofix to finish. (#149) (634a290)
- Release 1.7.0 (70eb10d)
- Add LICENSE file (#145) (336faa3)
- Release 1.6.0 (007ad15)
- support flat config (997b557)
- Release 1.5.8 (0344fd0)
- Undeprecated eslint.enable (aa80445)
- Release 1.5.7 (097b893)
- add eslint.fixOnSaveTimeout configuration (515cdeb)
- Release 1.5.6 (4673954)
- avoid exitCalled notification (e5852b2)
- Release 1.5.5 (0e2b7c3)
- Not show error message when normal exit (e36bc77)
- doc (9c161dd)
- Release 1.5.4 (c45eb00)
- register language client to services (f756bde)
- Release 1.5.3 (5d57a6f)
- fix reading property from null (107f72c)
- update dependencies (c1ffbc7)

## 3.1.2

- fix release.yml (994c937)
- not use npm whoami (b86f40d)
- improve npmignore (65d1a70)

## 3.1

- Added ESLint 10 flat-config support and related compatibility warnings.
- Added bulk suppressions diagnostics for ESLint ≥10.1.
- Added probing support for more languages and ESLint plugins.
- Added `eslint.useRealpaths` for improved symlink/path resolution.
- Added `eslint.codeActionsOnSave.options`.
- Added `eslint.lintTask.command` for custom project lint commands.
- Fixed code actions being applied to the wrong rule, document, or version.
- Fixed duplicate listeners and status bars after ESLint restarts.
- Improved global ESLint lookup, including pnpm failure handling.
- Fixed `eslint.lintProject` quickfix population using JSON output.
- Improved nested workspace, monorepo, and flat-config resolution.
- Added an automated release workflow; nothing has been pushed or published yet.

## 3.0.13

- Remove configuration `eslint.fixOnSaveTimeout`
- Add commands `eslint.migrateSettings`, `eslint.revalidate`
- Add configurations:
  - `eslint.problems.shortenToSingleLine`
  - `eslint.migration.2_x`
  - `eslint.ignoreUntitled`
  - `eslint.useFlatConfig`
  - `eslint.timeBudget.onValidation`
  - `eslint.timeBudget.onFixes`
- Flat config is used by default, you may need to configure `eslint.config.js`
  in your home folder to make it works for all of your files.
