---
title: "Hybrid Block Concept"
description: "Understand FenixPyre's Hybrid Block feature for protecting files in mixed access scenarios."
slug: /02-core-concepts/hybrid-block
keywords: [fenixpyre, encryption, hybrid-block]
last_updated: 2023-10-01
---

## Why it matters
Hybrid Block prevents unauthorized data exposure by blocking simultaneous access to protected and unprotected files in the same application.

'Hybrid Block' is FenixPyre-specific terminology. It indicates the protection offered when a protected file is open, and a non-protected file is simultaneously attempted to be opened by the same application, such as Microsoft Office or Adobe Acrobat.

FenixPyre does not allow a protected and unprotected file to be open concurrently, to prevent copying or pasting of protected data.

## Next Steps / Related Topics
For more on encryption models, see [encryption-model.md](/02-core-concepts/encryption-model).
