# v0.0.5

## Changed
- Cell module didn't use a fallback adapter for the `__using__` macro (#16)
- Added back the View.relative_path method (#15)

# v0.0.4

## Changed
- Fixed a bug where the Mix configuration wasn't allowing empty configurations (#13)

# v0.0.3

## Added
- Adapters can are now in a config.ex (#10)

## Changed
- Removed the need to specify an adapter for views and controllers (#10)
- ExCell.Controller is imported instead of using the __using__ macro (#10)

## Removed
- It's no longer possible to specify the adapter through the using Macro (#10)