# docsify-ko-fi

> Simple add customized Ko-fi buttons

<!-- panels:start -->

<!-- div:title-panel -->

## Installation

Add the **docsify-ko-fi** script after the docsify core.

```haml
<!-- docsify (latest v4.x.x)-->
<script src="https://cdn.jsdelivr.net/npm/docsify@4"></script>

<!-- docsify-ko-fi (latest) -->
<script src="https://cdn.jsdelivr.net/npm/docsify-ko-fi"></script>
```

## Usage

- `id` the Ko-fi **username** / **id**
- `color` the button color

<!-- div:left-panel -->

```markdown
<!-- ko-fi :id=<id> :color=<color> -->
    Support Me on Ko-fi
<!-- ko-fi -->
```

<!-- div:right-panel -->

<!-- ko-fi :id=fcannizzaro :color=#1599d6 -->
    Support Me on Ko-fi
<!-- ko-fi -->

<!-- panels:end -->

## Features

<!-- panels:start -->

<!-- div:left-panel -->

### Custom text

Use a custom text inside the ko-fi comments.

<!-- div:right-panel -->

<!-- ko-fi :id=fcannizzaro :color=#e0123b -->
    Tip me
<!-- ko-fi -->

<!-- ko-fi :id=fcannizzaro :color=#794bc4 -->
    Donate
<!-- ko-fi -->

<!-- panels:end -->

<!-- panels:start -->

<!-- div:left-panel -->

### Automatic contrast text color

The text color will change according the button's background color.

<!-- div:right-panel -->

<!-- ko-fi :id=fcannizzaro :color=#ffffff -->
     Buy me a coffee
<!-- ko-fi -->

<!-- ko-fi :id=fcannizzaro :color=#000000 -->
     Buy me a coffee
<!-- ko-fi -->

<!-- panels:end -->

