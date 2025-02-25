---
title: A responsive image test
slug: look at me
description: How to deploy a responsive image.
i18nReady: true
category:
  - Two
tags:
  - Image
  - Astro
  - Responsive
pubDate: 2025-02-24
cover: https://images.unsplash.com/photo-1629679264906-544009632b08?q=80&w=1960&h=1102&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
coverAlt: AstroVerse-Aliases
author: VV
---

import { Image } from 'astro:assets';
import church from '/src/assets/mark-de-jong-XeRVnghi1hY-unsplash.jpg';

<Image src={church} alt="A cobble stone road & church" width={3139} height={4880} layout="responsive" />
