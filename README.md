# test

This is a test repo to play with release-please.

Java configuration: https://github.com/googleapis/release-please/blob/v17.2.1/src/strategies/java.ts#L35-L48

```ts
const CHANGELOG_SECTIONS = [
    {type: 'feat', section: 'Features'},
    {type: 'fix', section: 'Bug Fixes'},
    {type: 'perf', section: 'Performance Improvements'},
    {type: 'deps', section: 'Dependencies'},
    {type: 'revert', section: 'Reverts'},
    {type: 'docs', section: 'Documentation'},
    {type: 'style', section: 'Styles', hidden: true},
    {type: 'chore', section: 'Miscellaneous Chores', hidden: true},
    {type: 'refactor', section: 'Code Refactoring', hidden: true},
    {type: 'test', section: 'Tests', hidden: true},
    {type: 'build', section: 'Build System', hidden: true},
    {type: 'ci', section: 'Continuous Integration', hidden: true},
];
```