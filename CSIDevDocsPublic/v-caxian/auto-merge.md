---
# required metadata

title: "v-caxian - QualifiesForAutoMerge"
description: v-caxian - my description - QualifiesForAutoMerge
#keywords:
author: shujingMS
ms.author: shujingzhang
manager: jamesyao-msft
ms.date:  10/29/2016
ms.topic: article
ms.service:
ms.subservice:
#ms.technology:
ms.assetid: c44deb70-bd5b-4efa-bcee-4e4b4c8f418c

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:
---


# VS Code Authoring Extensionee Test Shujing

VS Code Markdown Authoring Extension for OPS is a poc to provide authoring help to writers working in OPS and authoring for docs.microsoft.com. It includes several functions, including applying the default docs template to new Markdown files and generating a GUID, applying common formattidng to strings, inserting links and images, and previewing content using your site's CSS.

## Installation steps

1. Copy the installation folder from Sogup.
2. Save ops-platform-extension-poc-0.0.1.vsix to your machine.
3. Open VS Code and click the square icon on the left panel to open the Extensions menu.
4. Click the three dots for "More" and select "Install from VSIX..."
5. Navigate to the extension and select it.
6. VS Code will install the extension and prompt you to restart.

## Prerequisites and assumptions

To effectively use the OPS Authoring extension, you must:
- Clone your entire repo to your local machine and keep it in sync. Functions such as link and image insertion are not reliable if the repo is out of sync.
- For accurate content preview, you need to update your VS Code settings.json file, as described under **Preview Content** below.
