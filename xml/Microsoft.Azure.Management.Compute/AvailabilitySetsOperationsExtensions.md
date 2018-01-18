<Type Name="AvailabilitySetsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AvailabilitySetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AvailabilitySetsOperationsExtensions = class" />
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
            <span data-ttu-id="4c31e-101">AvailabilitySetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4c31e-101">Extension methods for AvailabilitySetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AvailabilitySet CreateOrUpdate (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, Microsoft.Azure.Management.Compute.Models.AvailabilitySet parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AvailabilitySet CreateOrUpdate(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, class Microsoft.Azure.Management.Compute.Models.AvailabilitySet parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.AvailabilitySet)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAvailabilitySetsOperations, resourceGroupName As String, availabilitySetName As String, parameters As AvailabilitySet) As AvailabilitySet" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string * Microsoft.Azure.Management.Compute.Models.AvailabilitySet -&gt; Microsoft.Azure.Management.Compute.Models.AvailabilitySet" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, availabilitySetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AvailabilitySet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.AvailabilitySet" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-103">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-104">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-104">The name of the availability set.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4c31e-105">パラメーターは、可用性セットの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-105">Parameters supplied to the Create Availability Set operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-106">作成または可用性セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-106">Create or update an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, Microsoft.Azure.Management.Compute.Models.AvailabilitySet parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, class Microsoft.Azure.Management.Compute.Models.AvailabilitySet parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.AvailabilitySet,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string * Microsoft.Azure.Management.Compute.Models.AvailabilitySet * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, availabilitySetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.AvailabilitySet" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-108">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-109">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-109">The name of the availability set.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4c31e-110">パラメーターは、可用性セットの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-110">Parameters supplied to the Create Availability Set operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c31e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-112">作成または可用性セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-112">Create or update an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IAvailabilitySetsOperations, resourceGroupName As String, availabilitySetName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.Delete (operations, resourceGroupName, availabilitySetName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-114">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-115">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-115">The name of the availability set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-116">可用性セットを削除します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-116">Delete an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-118">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-119">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-119">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c31e-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-121">可用性セットを削除します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-121">Delete an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AvailabilitySet Get (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AvailabilitySet Get(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAvailabilitySetsOperations, resourceGroupName As String, availabilitySetName As String) As AvailabilitySet" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.AvailabilitySet" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.Get (operations, resourceGroupName, availabilitySetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AvailabilitySet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-123">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-124">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-124">The name of the availability set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-125">可用性セットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-125">Retrieves information about an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; GetAsync (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; GetAsync(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.GetAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-127">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-128">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-128">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c31e-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-130">可用性セットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-130">Retrieves information about an availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; List (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt; List(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.List(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAvailabilitySetsOperations, resourceGroupName As String) As IEnumerable(Of AvailabilitySet)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-132">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-133">リソース グループ内のすべての可用性セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-133">Lists all availability sets in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.AvailabilitySet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-135">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c31e-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-137">リソース グループ内のすべての可用性セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-137">Lists all availability sets in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAvailableSizes(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSizes (operations As IAvailabilitySetsOperations, resourceGroupName As String, availabilitySetName As String) As IEnumerable(Of VirtualMachineSize)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizes : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAvailableSizes (operations, resourceGroupName, availabilitySetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-139">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-140">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-140">The name of the availability set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-141">既存の可用性セットで、新しいバーチャル マシンを作成するために使用するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-141">Lists all available virtual machine sizes that can be used to create a new virtual machine in an existing availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.AvailabilitySetsOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4c31e-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4c31e-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4c31e-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4c31e-143">The name of the resource group.</span></span>
            </param>
        <param name="availabilitySetName">
            <span data-ttu-id="4c31e-144">可用性セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="4c31e-144">The name of the availability set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4c31e-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c31e-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4c31e-146">既存の可用性セットで、新しいバーチャル マシンを作成するために使用するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c31e-146">Lists all available virtual machine sizes that can be used to create a new virtual machine in an existing availability set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>