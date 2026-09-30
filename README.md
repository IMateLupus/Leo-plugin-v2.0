# Lupus Leo v2 — Eclipse Update Site

p2 update site for version 2 of the Lupus Leo Eclipse plug-in.
It installs as **Lupus Leo v2**, next to the stable 1.x plug-in rather than
over it, and keeps its own settings.

## Install

In Eclipse: **Help → Install New Software…** → **Add…**

| Field | Value |
|-------|-------|
| Name | Lupus Leo 2.0 |
| Location | `https://imatelupus.github.io/Leo-plugin-v2.0/` |

Select **Lupus Consulting Tools → Lupus Leo v2**, then finish the wizard and
restart Eclipse. Updates arrive through **Help → Check for Updates**.

## Requirements

- Eclipse 2024-09 (4.33) or newer
- Java 21 or newer

## Configuration

API keys and SAP credentials are entered per user under
**Window → Preferences → Lupus Leo**. They are held in Eclipse secure
storage and are not part of this site.

## Contents

This repository holds only build output. The source lives in a separate
private repository.
