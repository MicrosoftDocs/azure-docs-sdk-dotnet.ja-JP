<Type Name="VirtualMachineExtensionsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eb40d-101">VirtualMachineExtensionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="eb40d-101">Extension methods for VirtualMachineExtensionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, extensionParameters As VirtualMachineExtension) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-103">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-104">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-104">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-105">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-105">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="eb40d-106">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-106">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-107">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-107">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-109">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-110">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-110">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-111">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-111">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="eb40d-112">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-112">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb40d-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eb40d-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-114">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-114">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDelete (operations, resourceGroupName, vmName, vmExtensionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-116">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-117">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-117">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-118">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-118">The name of the virtual machine extension.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-119">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-119">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-121">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-122">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-122">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-123">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-123">The name of the virtual machine extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb40d-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eb40d-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-125">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-125">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension CreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension CreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, extensionParameters As VirtualMachineExtension) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-127">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-128">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-128">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-129">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-129">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="eb40d-130">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-130">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-131">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-131">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-133">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-134">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-134">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-135">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-135">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="eb40d-136">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="eb40d-136">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb40d-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eb40d-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-138">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-138">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Delete (operations, resourceGroupName, vmName, vmExtensionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-140">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-141">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-141">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-142">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-142">The name of the virtual machine extension.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-143">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-143">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-145">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-146">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-146">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-147">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-147">The name of the virtual machine extension.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb40d-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eb40d-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-149">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-149">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension Get (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension Get(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, Optional expand As String = null) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Get (operations, resourceGroupName, vmName, vmExtensionName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-151">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-152">拡張子を含む仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-152">The name of the virtual machine containing the extension.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-153">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-153">The name of the virtual machine extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="eb40d-154">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-154">The expand expression to apply on the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-155">拡張機能を取得する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-155">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, vmExtensionName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="eb40d-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="eb40d-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="eb40d-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-157">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="eb40d-158">拡張子を含む仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-158">The name of the virtual machine containing the extension.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="eb40d-159">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="eb40d-159">The name of the virtual machine extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="eb40d-160">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-160">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb40d-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eb40d-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb40d-162">拡張機能を取得する操作です。</span><span class="sxs-lookup"><span data-stu-id="eb40d-162">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>