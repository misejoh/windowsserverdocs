---
title: create
description: Reference topic for create, which starts the shadow copy creation process, using the current context and option settings.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: 837aa449-9b60-41ae-9ef1-ef67af6e5918
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# create

Starts the shadow copy creation process, using the current context and option settings. Requires at least one volume in the Shadow Copy Set.

## Syntax

```
create
```

## Remarks

-   You must add at least one volume with the **add volume** command before you can use the **create** command.
-   You can use the **begin backup** command to specify a full backup, rather than a copy backup.
-   After you run the **create** command, you can use the **exec** command to run a duplication script for backup from the shadow copy.

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)