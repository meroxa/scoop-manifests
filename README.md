# Meroxa Scoop Manifests

This repository contains Scoop manifests that make it easier to install Meroxa CLI on a Windows machine. 

What do I need to get started? 
---------------------------------

Download Scoop onto your Windows machine, to do so, run following steps: 

1. In your PowerShell, run - `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`
2. Then run - `irm get.scoop.sh | iex`


How do I install these manifests? 
---------------------------------

In PowerShell run the following commands:

1. `scoop bucket add meroxa https://github.com/meroxa/scoop-manifests`
2. `scoop install meroxa`


How do I update my CLI? 
---------------------------------

Run `scoop status` and `scoop update meroxa` to upgrade your Meroxa CLI to latest version. 
