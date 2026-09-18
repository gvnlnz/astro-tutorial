---
layout: ../../layouts/MarkdownPostLayout.astro
title: Il mio secondo articolo del blog
author: Gavio
pubDate: 2026-01-01
description: "Dopo aver imparato un po' di Astro, non riuscivo a smettere!"
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Il logo di Astro su uno sfondo scuro con un arco sfumato viola."
tags: ["astro", "blogging", "imparare in pubblico", "successi"]
---
Di seguito è possibile vedere come creare una rotta Laravel per mostrare una lista di tutti gli utenti:

```php
<?php
use App\Http\Controller\UserController;
use Illuminate\Support\Facades\Route;

Route::get('/users', [UserController::class, 'index'])->name('users.index');
```
