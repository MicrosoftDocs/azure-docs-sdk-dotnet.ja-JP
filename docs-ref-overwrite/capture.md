---
<span data-ttu-id="f87af-101">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) summary: *content</span><span class="sxs-lookup"><span data-stu-id="f87af-101">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) summary: *content</span></span>
---

<span data-ttu-id="f87af-102">ファイルの上書きメソッドによって挿入されるコンテンツは次のとおりです。そのため、作成者は、Markown 形式で生成された API ドキュメントに必要な数だけ追加できます。</span><span class="sxs-lookup"><span data-stu-id="f87af-102">Here is content that is injected by the overwrite file method, so writers can add as much as they want to the generated API documentation in Markown format.</span></span>

---
<span data-ttu-id="f87af-103">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) remarks: *content</span><span class="sxs-lookup"><span data-stu-id="f87af-103">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) remarks: *content</span></span>
---

<span data-ttu-id="f87af-104">次のコードでは、Azure .NET SDK を使用して Capture メソッドを呼び出す方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="f87af-104">The code below demonstrates how to call the Capture method using the Azure .NET SDK.</span></span> 

```csharp
using Microsoft.Azure.Management.Compute;
using Microsoft.Azure.Management.Compute.Models;
using Microsoft.Rest;

namespace MyAzureVmClientApp
{
    class Program
    {
        static void Main(string[] args)
        {
            var token = "[Token Obtained from ADAL]";

            var credential = new TokenCredentials(token);

            var captureResponse = 
                new ComputeManagementClient(credential)
                .VirtualMachines
                    .Capture(
                        "myResourceGroup",
                        "myVmName",
                        new VirtualMachineCaptureParameters
                        {
                            DestinationContainerName = "myblobcontainer",
                            OverwriteVhds = true,
                            VhdPrefix = "backup"
                        });
        }
    }
}
```

