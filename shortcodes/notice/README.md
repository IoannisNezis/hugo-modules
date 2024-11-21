# Notice Shortcode
      },

## Installation for Gethugothemes themes

Add the following code to your module list in the `config/_default/module.toml` file.

```toml
[[imports]]
path = "github.com/gethugothemes/hugo-modules/shortcodes/notice"
```

Add the following code to your `assets/scss/main.scss` or `assets/scss/style.scss` file.

```scss
@import 'notice';
```

<hr>

## Acknowledgments

The notice types are heavily inspired by [Obsidian's Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts).

The svg icons are from [heroicons.com](https://heroicons.com/)

## Shortcode Implementation

```md
{{< notice "note" >}}
{{< /notice >}}

{{< notice "abstract" >}}
{{< /notice >}}
Aliases: `summary`, `tldr`

{{< notice "info" >}}
{{< /notice >}}

{{< notice "todo" >}}
{{< /notice >}}

{{< notice "tip" >}}
{{< /notice >}}
Aliases: `hint`, `important`

{{< notice "success" >}}
{{< /notice >}}
Aliases: `check`, `done`

{{< notice "question" >}}
{{< /notice >}}
Aliases: `help`, `faq`

{{< notice "warning" >}}
{{< /notice >}}
Aliases: `caution`, `attention`

{{< notice "failure" >}}
{{< /notice >}}
Aliases: `fail`, `missing`

{{< notice "danger" >}}
{{< /notice >}}
Aliases: `error`

{{< notice "bug" >}}
{{< /notice >}}

{{< notice "example" >}}
{{< /notice >}}

{{< notice "quote" >}}
{{< /notice >}}
Aliases: `cite`
```
