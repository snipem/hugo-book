
# Collapse

Collapse menus structure the menu. Enable `BookMenuBundle` for this to work.

```toml
  BookMenuBundle = '/menu'
```

The `item` is the heading you want to use as a button for collapsing the menu. `path` is the path to the files within the menu. This is used to uncollapse the menu when one of the entries is selected.

## Example

```tpl
{{</* collapse item="Name of Entry" path="/docs/shortcodes/" */>}}
- [Buttons]({{</* relref "/docs/shortcodes/buttons" */>}})
- [Columns]({{</* relref "/docs/shortcodes/columns" */>}})
- [Expand]({{</* relref "/docs/shortcodes/expand" */>}})
{{</* /collapse */>}}
```