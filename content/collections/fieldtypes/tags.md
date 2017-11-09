---
title: Tags
image: /assets/fieldtypes/tags.png
description: Enter "tag" style data, stored as an array.
overview: >
  Users can input “taggable” values, which are formatted
  automatically into a YAML list format, giving you a tag pair style data output.
id: 821a636f-2ebd-4297-b459-47e702f899df
---
You can hit `enter` or `tab` to add a tag; navigate through tabs with your arrow keys; use `backspace` or click
the `x` to delete tags; and drag and drop tags to rearrange them.

Your tags will get saved as a simple YAML list, like this:

``` .language-yaml
- Bears
- Beets
- Battlestar Galactica
```

Note: This fieldtype uses "Tags" in general terms. If you're looking for a way to tag/taxonomize your content, you
may be interested in checking out [taxonomies](/taxonomies) and the [Taxonomy fieldtype](/fieldtypes/taxonomy).

## Example
To display tag values separated by a comma you can use the [join](https://docs.statamic.com/modifiers/join) modifier:

```{{ tags_field | join }}```

Output:

```Bears, Beets, Battlestar Galactica```
