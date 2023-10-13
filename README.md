# Visual Studio Dapr Extension

The Dapr extension for Visual Studio enables you to view, manage, diagnose, and debug Dapr services within Visual Studio.

## Prerequisites

* [Visual Studio 2022 17.7.x](https://visualstudio.microsoft.com/vs/) [Community, Professional, or Enterprise] [ARM64 or AMD64]
* [Dapr 1.11 or later](https://dapr.io)

## Installation

### Visual Studio Marketplace

> [!NOTE]
> Release builds of the Visual Studio Dapr Extension are not yet available via the Visual Studio marketplace.

### Intermediate Builds

Intermediate builds are available via an additional Visual Studio extension gallery.

> [!WARNING]
> Intermediate builds may contain incomplete features, are not extensively tested, may not meet your quality standards, and are intended for evaluation and feedback purposes. Use at your own risk.

To get started, add the gallery to Visual Studio:

1. From Visual Studio, select **Tools > Options**
1. In the Options window, select **Environment > Extensions**
1. Under **Additional Extensions Galleries**, click **Add**
1. Update the name and URL:

   * **Name:** Dapr
   * **Url:** https://aka.ms/vs-dapr-gallery

   ![Screenshot of the Visual Studio Options dialog with the Environments > Extensions category selected and showing the addition of the extension gallery.](assets/readme/VisualStudioOptionsExtensions.png)

1. Click **Apply** to review the changes, and then **OK** to confirm and close the window
1. From Visual Studio, select **Extensions > Manage Extensions**
1. In the left menu, under **Online**, select the **Dapr** gallery you just created
1. Click **Download** to download the extension

   ![Screenshot of the Visual Studio Manage Extensions dialog with the Dapr extension gallery selected and showing the extension to be downloaded.](assets/readme/VisualStudioManageExtensions.png)

1. Once the extension download is complete, close all Visual Studio windows to start the installation
1. In the installation window, click **Modify** to finish installing

   ![Screenshot of the Visual Studio extension (VSIX) installation window and showing the Modify button.](assets/readme/VisualStudioExtensionInstallation.png)

1. Once modifications are complete, click **Close** to close the installation window

## Use

### Starting with the Dapr Extension

1. Open your solution in Visual Studio
1. Right-click the solution in Solution Explorer and select **Add > Dapr Run File**

   ![Screenshot of Visual Studio Solution Explorer with the solution context menu open and showing the Add > Dapr Run File command.](assets/readme/SolutionAddDaprRunFile.png)

1. You can now edit and add to the created `dapr.yaml` file

   ![Screenshot of Visual Studio with the generated Dapr run file open in the YAML editor.](assets/readme/EditDaprRunFile.png)

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

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
