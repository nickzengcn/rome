# `undeclaredVariable.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/transforms/lint/__rtests__/undeclaredVariable.ts --update-snapshots` to update.

## `undeclared variable`

```javascript
Object {
  src: 'foobar;'
  suppressions: Array []
  diagnostics: Array [
    Object {
      category: 'lint/undeclaredVariables'
      filename: 'unknown'
      language: 'js'
      message: 'Undeclared variable <emphasis>foobar</emphasis>'
      mtime: undefined
      sourceType: 'module'
      origins: Array [Object {category: 'lint'}]
      end: Object {
        column: 6
        index: 6
        line: 1
      }
      start: Object {
        column: 0
        index: 0
        line: 1
      }
    }
  ]
}
```
