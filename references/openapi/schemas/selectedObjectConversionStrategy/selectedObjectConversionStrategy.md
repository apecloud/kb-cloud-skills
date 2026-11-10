# selectedObjectConversionStrategy

Strategy for converting the selected tree to parameters. levelMapping maps every configured level and applies skipWhenParentLevelsSelectedAll. wholeObject merges duplicate branches and maps only whole selected nodes (selectedAll or leaves), omitting covered descendants. Defaults to levelMapping when omitted.

**Type:** enum

## Values

- `levelMapping`
- `wholeObject`
