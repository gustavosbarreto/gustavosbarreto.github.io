---
title: runtime.js, sistema operacional para aplicações na nuvem
date: 2015-08-13 18:00:00 Z
categories:
- operating system
layout: post
---

O [runtime.js](http://runtimejs.org/) é *library operating system* (não encontrei tradução para este termo) para aplicações na nuvem. Seu objetivo
é fornecer um sistema operacional que executa apenas um processo.

Feito em cima do [V8 JavaScript Engine](https://developers.google.com/v8/), o runtime.js roda somente aplicações feitas em JavaScript utilizando o conceito de
*event-driven* e o modelo de IO *non-blocking* inspirado pelo Node.js.

Esse tipo de sistema operacional não tem como objetivo rodar um hardware real e sim em um *Hypervisor*. Atualmente o único
suportado pelo runtime.js é o KVM.

