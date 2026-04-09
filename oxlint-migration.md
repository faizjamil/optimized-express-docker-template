✨ .oxlintrc.json created with 164 rules.

   Skipped 35 rules:
     - 14 Not Implemented
       - no-implied-eval
       - no-restricted-properties
       - prefer-regex-literals
       - no-unreachable-loop
       - no-restricted-syntax
       - one-var
       - import/no-extraneous-dependencies
       - import/newline-after-import
       - import/no-useless-path-segments
       - import/no-import-module-exports
       - import/no-relative-packages
       - strict
       - n/no-deprecated-api
       - n/process-exit-as-throw
     - 21 Unsupported
       - no-dupe-args: Superseded by strict mode.
       - no-octal: Superseded by strict mode.
       - consistent-return: Use `typescript/consistent-return` instead, which we support as a type-aware rule.
       - dot-notation: Use `typescript/dot-notation` instead, which we support as a type-aware rule.
       - no-octal-escape: Superseded by strict mode.
       - no-return-await: Deprecated, not recommended anymore by ESLint.
       - global-require: Deprecated, replaced by `node/global-require`.
       - no-buffer-constructor: Replaced by `node/no-deprecated-api`.
       - no-new-require: Deprecated, replaced by `node/no-new-require`, which we already support.
       - no-path-concat: Deprecated, replaced by `node/no-path-concat`.
       - lines-between-class-members: Deprecated stylistic rule, can be used via the stylistic eslint plugin as a JS Plugin if necessary.
       - lines-around-directive: Deprecated stylistic rule, can be used via the stylistic eslint plugin as a JS Plugin if necessary.
       - no-new-object: Replaced by `eslint/no-object-constructor`, which we support.
       - spaced-comment: Deprecated stylistic rule, can be used via the stylistic eslint plugin as a JS Plugin if necessary.
       - no-undef-init: #6456, `unicorn/no-useless-undefined` covers this case.
       - no-new-symbol: Deprecated as of ESLint v9, but for a while disable manually.
       - import/no-unresolved: Will always contain false positives due to module resolution complexity.
       - import/order: Not implementing this in Oxlint as its behavior is covered very well by [Oxfmt's import sorting](https://oxc.rs/docs/guide/usage/formatter/sorting.html).
       - handle-callback-err: Deprecated, replaced by `node/handle-callback-err`.
       - no-negated-in-lhs: Replaced by `eslint/no-unsafe-negation`, which we support.
       - no-tabs: Deprecated stylistic rule, can be used via the stylistic eslint plugin as a JS Plugin if necessary.

🚀 Next:
     npx oxlint .

⚠️  Warnings (2):
   * Settings not migrated (not supported by oxlint):
     * `import/resolver`
     * `import/extensions`
     * `import/core-modules`
     * `import/ignore`
   * special parser detected: @babel/eslint-parser