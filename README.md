<!-- BEGIN_ACTION_DOC -->
# Release Existence Action

### Description
Check if a release for given tag exists
### Action Type
Composite

### Author
Roche/Genentech - Insights Engineering

### Inputs
* `release-tag`:

  _Description_: The name of tag for which it should be checked whether the release exists.
    If not specified, then the current tag is used.

  _Required_: `false`

  _Default_: `""`

### Outputs
* `release-exists`:

  _Description_: Whether the release for given tag exists

<!-- END_ACTION_DOC -->
