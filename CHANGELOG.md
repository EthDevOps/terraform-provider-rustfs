## 0.1.1

BUG FIXES:

* `rustfs_policy`: exclude the policy `Name` from the request body. Fixes
  policy create/update failing with `unknown field 'Name'` against RustFS
  servers that reject unknown body fields.

## 0.1.0 (Unreleased)

FEATURES:
