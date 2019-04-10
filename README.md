# lucky-draw-deployment

[![Build Status](https://tonyxia.visualstudio.com/public/_apis/build/status/LuckyDrawDeployment-CI?branchName=master)](https://tonyxia.visualstudio.com/public/_build/latest?definitionId=6&branchName=master)

## Pre-deployment

Register a Microsoft App on [https://apps.dev.microsoft.com](https://apps.dev.microsoft.com), remember the Application ID and Application Secret/Password

## Post-deployment

Unfortunately, you must do the below steps manually

1. Enable the Teams channel in Bot Service

2. Create 2 tables in the Azure Storage Account which is created during deployment
   * OpenCompetitions
   * CompletedCompetitions

   Support for creating tables is in progress. [See this](https://feedback.azure.com/forums/281804-azure-resource-manager/suggestions/9306108-let-me-define-preconfigured-blob-containers-table)
