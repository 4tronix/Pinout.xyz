<!--
---
name: Masse (Ground)
description: Raspberry Pi Masse Pins
pin:
  '6':
  '9':
  '14':
  '20':
  '25':
  '30':
  '34':
  '39':
-->
#Masse (Ground)

Die Masseanschl�sse des Raspberry Pi sind alle miteinander verbunden. Es ist also egal, welchen
Du verwendets.

Es macht also Sinn einfach den Pin zu verwenden, der am n�hesten zu dein anderen von Dir verwendeten
Pins ist oder alternativ den Pin, der am n�hesten zu dem 5V-Pin liegt, den Du benutzt.

Wenn Du den [SPI](/pinout/spi)-Bus verwendest, dann macht es Sinn den Pin 17 f�r 3v3 Volt und Pin 25
f�r Masse zu verwenden, da sich diese Pins in der n�he zu den SPIO-Pins befinden.
