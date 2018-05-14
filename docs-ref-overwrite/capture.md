---
uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) summary: *content
---

ファイルの上書きメソッドによって挿入されるコンテンツは次のとおりです。そのため、作成者は、Markown 形式で生成された API ドキュメントに必要な数だけ追加できます。

---
uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) remarks: *content
---

次のコードでは、Azure .NET SDK を使用して Capture メソッドを呼び出す方法を示しています。 

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

