---
page_type: sample
languages:
- csharp
products:
- dotnet
description: "Add 150 character max description"
urlFragment: "update-this-to-unique-url-stub"
---

# Official Microsoft Sample

The repository contains a script and files to complete exercises in the MS Learn module **Extend your on-premises file share capacity by using Azure File Sync**.

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `resources/CADFolder.zip`    | Folder contains the script create-bad-file.js and three sample data files.             |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CODE_OF_CONDUCT.md`    | Microsoft Open Source Code of Conduct.             |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |
| `SECURITY.md`         | Security statement for sample.               |

## Prerequisites

Use on Windows Server operating system.

## Setup

On the Windows Server you plan to use with Azure File Sync, download the CAD folder with curl. The steps to use the files in the folder are included in the module's exercise units.

## Running the sample

1. Download this sample CAD file with curl.

    ```cmd
    curl https://github.com/MicrosoftDocs/mslearn-extend-share-capacity-with-azure-file-sync/blob/master/resources/CADFolder.zip?raw=true -L -o CADFolder.zip
    ```

1. Expand the zip file.

    ```cmd
    CADFolder.zip
    ```

1. In the **File Explorer** window, select **Compressed Folder Tools**, then select **Extract all** and **Extract**.

After you set up and register your Windows Server with Azure File Sync, use `create-bad-file.js` to create a file that won't sync. 

1. Go to the **CADFolder** in both windows.
1. Open **create-bad-file.js** on the left.
1. See that a new file named, **invalid╘«nameÉ.txt** has been created.
1. This file won't replicate into the Azure file share.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
