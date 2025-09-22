---
title: rules
author: Christian B.
date: 2025-09-22
tags: [regeln, basics]
status: draft
---
# Dateiregeln
Hier stehen die Regeln, die wir bei jeder Markdown Datei einhalten wollen

## Frontmatter
Frontmatter nennt man einen Header in einer Datei in der Markdown Welt. Er beginnt und endet immer mit drei Bindestrichen und enthält Metainformationen zu der jeweiligen Datei. Die Frontmatter MUSS immer zu Dateibeginn stehen. Obsidian unterstützt uns dabei.

Hier ein Beispiel:

```yaml
---
title: rules
author: Christian B.
date: 2025-09-22
tags: [tag1, tag2]
status: draft
---
```

Die Einhaltung wird automatisch geprüft und es kann nur in das git repo commited werden, wenn die Metadaten vorhanden sind. 