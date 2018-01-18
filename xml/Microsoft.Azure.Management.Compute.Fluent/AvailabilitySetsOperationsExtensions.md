<Type Name="AvailabilitySetsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AvailabilitySetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AvailabilitySetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8442b-101">AvailabilitySetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8442b-101">Extension methods for AvailabilitySetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, availabilitySetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8442b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8442b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8442b-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8442b-103">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">To be added.</param>
        <param name="parameters">
            <span data-ttu-id="8442b-104">パラメーターは、可用性セットの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8442b-104">Parameters supplied to the Create Availability Set operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8442b-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8442b-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8442b-106">作成または可用性セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="8442b-106">Create or update an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8442b-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8442b-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8442b-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8442b-108">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="8442b-109">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="8442b-109">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8442b-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8442b-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8442b-111">可用性セットを削除します。</span><span class="sxs-lookup"><span data-stu-id="8442b-111">Delete an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.GetAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8442b-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8442b-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8442b-113">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8442b-113">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="8442b-114">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="8442b-114">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8442b-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8442b-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8442b-116">可用性セットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8442b-116">Retrieves information about an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8442b-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8442b-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8442b-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8442b-118">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8442b-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8442b-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8442b-120">リソース グループ内のすべての可用性セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8442b-120">Lists all availability sets in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8442b-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8442b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8442b-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8442b-122">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="8442b-123">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="8442b-123">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8442b-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8442b-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8442b-125">既存の可用性セットで、新しいバーチャル マシンを作成するために使用するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8442b-125">Lists all available virtual machine sizes that can be used to create a new virtual machine in an existing availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>