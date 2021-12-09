---
authors:
- john-doe
date: "2021-05-23T20:00:00+01:00"
tags:
- Documentation
- Shortcodes
title: Mermaid
---

[Mermaid](https://mermaidjs.github.io/) is library for generating SVG charts and diagrams from text.

<!--more-->

## Example

{{< columns >}}

<!-- prettier-ignore -->
```tpl
{{</* mermaid class="text-center"*/>}}
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
        Bob->>Alice: Not so good :(
    else is well
        Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        Bob->>Alice: Thanks for asking
    end
{{</* /mermaid */>}}
```

<--->

<!-- spellchecker-disable -->
<!-- prettier-ignore -->
{{< mermaid class="text-center" >}}
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
        Bob->>Alice: Not so good :(
    else is well
        Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        Bob->>Alice: Thanks for asking
    end
{{< /mermaid >}}

<!-- spellchecker-enable -->

{{< /columns >}}
