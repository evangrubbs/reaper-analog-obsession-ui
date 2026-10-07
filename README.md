# reaper-analog-obsession-ui

Unofficial REAPER JSFX UI wrappers for Analog Obsession plugins (BritChannel, BUSTERse, FETish, LAEA, LALA, Rare, SSQ, VariMOon): mixer-strip GUIs.

## Requirements

- REAPER
- The original Analog Obsession plugins you want to use, installed as [VST/VST3 - fill in]:
  - BritChannel
  - BUSTERse
  - FETish
  - LAEA
  - LALA
  - Rare
  - SSQ
  - VariMOon

## Installation

1. In REAPER, go to **Options → Show REAPER resource path in explorer/finder**.
   (On Windows this is usually `C:\Users\<you>\AppData\Roaming\REAPER`.)
2. Copy the contents of this repo's `Effects` folder into the `Effects` folder there.
3. Copy the contents of this repo's `FXChains` folder into the `FXChains` folder there.
4. Restart REAPER, or press F5 in the FX browser.

## Usage

1. Open the Add FX window, scroll to **FX Chains**, and choose the chain you want.
2. Close the plugin's own window after it loads. If it stays open, the embedded UI will show
   "Plugin Open In UI".
3. In the Mixer, right-click the plugin and choose **Show embedded UI in MCP**.

## Disclaimer

This is an unofficial project. It is not affiliated with or endorsed by Analog Obsession or REAPER.
