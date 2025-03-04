---
id: introduction
title: What is Avail?
sidebar_label: What is Avail
description: Learn about Avail's data availability chain
keywords:
  - docs
  - avail
  - availability
  - scale
  - rollup
image: https://docs.availproject.org/img/avail/AvailDocs.png
---

import useBaseUrl from '@docusaurus/useBaseUrl';

Avail is a **modular blockchain** that is laser-focused on **data
availability**: ordering, publishing transactions, and making it
possible to verify that block data is available without downloading
the whole block. This modular approach with a strong data availability
layer at the core enables scalability while maintaining security.

Since Avail is data-agnostic, it can support any execution
environment: EVM, WASM, custom new runtimes, etc. The modular approach
also allows a wide array of possible designs to be built on top, such
as sovereign ZK or OP appchains, general purpose rollups, sidechains,
validiums, and more. And they don't require recruiting a new validator
set, only posting transactions on Avail. Independence and flexibility
matched by shared security and scalability.

Applications in Avail are built as one of the designs mentioned above
(such as a ZK sovereign appchain), or can be deployed as contracts on
a modular execution layer.
