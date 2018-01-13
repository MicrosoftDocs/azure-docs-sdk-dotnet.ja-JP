<Type Name="PublicIPAddressesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PublicIPAddressesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PublicIPAddressesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5e82-101">PublicIPAddressesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f5e82-101">Extension methods for PublicIPAddressesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As PublicIPAddress) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-103">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-104">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-104">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-105">作成または更新パブリック IP アドレスを操作に指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-105">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-106">作成するか、静的または動的なパブリック IP アドレスを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-106">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-108">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-109">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-109">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-110">作成または更新パブリック IP アドレスを操作に指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-110">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-112">作成するか、静的または動的なパブリック IP アドレスを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-112">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDelete (operations, resourceGroupName, publicIpAddressName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-114">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-115">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-115">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-116">指定されたパブリック IP アドレスを削除します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-116">Deletes the specified public IP address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-118">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-119">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-119">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-121">指定されたパブリック IP アドレスを削除します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-121">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginUpdateTags (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress BeginUpdateTags(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As TagsObject) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-123">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-124">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-124">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-125">パブリック IP アドレス タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-125">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-126">パブリック IP アドレス タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-126">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-128">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-129">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-129">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-130">パブリック IP アドレス タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-130">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-132">パブリック IP アドレス タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-132">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress CreateOrUpdate (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress CreateOrUpdate(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As PublicIPAddress) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-134">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-135">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-135">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-136">作成または更新パブリック IP アドレスを操作に指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-136">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-137">作成するか、静的または動的なパブリック IP アドレスを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-137">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.PublicIPAddress parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-139">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-140">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-140">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-141">作成または更新パブリック IP アドレスを操作に指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-141">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-143">作成するか、静的または動的なパブリック IP アドレスを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-143">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Delete (operations, resourceGroupName, publicIpAddressName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-145">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-146">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-146">The name of the subnet.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-147">指定されたパブリック IP アドレスを削除します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-147">Deletes the specified public IP address.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.DeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-149">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-150">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-150">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-152">指定されたパブリック IP アドレスを削除します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-152">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress Get (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress Get(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, Optional expand As String = null) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.Get (operations, resourceGroupName, publicIpAddressName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-154">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-155">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-155">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f5e82-156">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-157">指定されたリソース グループ内の指定されたパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-157">Gets the specified public IP address in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetAsync (operations, resourceGroupName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-159">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-160">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-160">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f5e82-161">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-163">指定されたリソース グループ内の指定されたパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-163">Gets the specified public IP address in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetPublicIPAddress">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress GetVirtualMachineScaleSetPublicIPAddress (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress GetVirtualMachineScaleSetPublicIPAddress(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddress(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVirtualMachineScaleSetPublicIPAddress (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, ipConfigurationName As String, publicIpAddressName As String, Optional expand As String = null) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetPublicIPAddress : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddress (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, publicIpAddressName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-165">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-166">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-166">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="f5e82-167">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="f5e82-167">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="f5e82-168">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-168">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="f5e82-169">IP 構成の名前です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-169">The name of the IP configuration.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-170">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-170">The name of the public IP Address.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f5e82-171">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-171">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-172">仮想マシン スケール セット内の指定されたパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-172">Get the specified public IP address in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetPublicIPAddressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetVirtualMachineScaleSetPublicIPAddressAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; GetVirtualMachineScaleSetPublicIPAddressAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetPublicIPAddressAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;GetVirtualMachineScaleSetPublicIPAddressAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-174">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-174">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-175">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-175">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="f5e82-176">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="f5e82-176">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="f5e82-177">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-177">The name of the network interface.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="f5e82-178">IP 構成の名前です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-178">The name of the IP configuration.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-179">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-179">The name of the public IP Address.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f5e82-180">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-180">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-182">仮想マシン スケール セット内の指定されたパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-182">Get the specified public IP address in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; List (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; List(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.List(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPublicIPAddressesOperations, resourceGroupName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-184">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-185">リソース グループ内のすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-185">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAll (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAll(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IPublicIPAddressesOperations) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-186">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-187">サブスクリプションのすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-187">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-188">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-190">サブスクリプションのすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-190">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAllNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListAllNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-192">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-193">サブスクリプションのすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-193">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAllNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-197">サブスクリプションのすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-197">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-199">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-201">リソース グループ内のすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-201">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-204">リソース グループ内のすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-204">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-208">リソース グループ内のすべてのパブリック IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-208">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddresses">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddresses (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddresses(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddresses(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetPublicIPAddresses (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddresses : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddresses (operations, resourceGroupName, virtualMachineScaleSetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-210">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-210">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-211">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-211">The name of the virtual machine scale set.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-212">仮想マシン スケール セット レベル上のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-212">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-214">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-214">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-215">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-215">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-217">仮想マシン スケール セット レベル上のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-217">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddressesNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetPublicIPAddressesNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetPublicIPAddressesNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-218">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-219">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-219">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-220">仮想マシン スケール セット レベル上のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-220">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-221">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-222">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-222">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-223">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-224">仮想マシン スケール セット レベル上のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-224">Gets information about all public IP addresses on a virtual machine scale set level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddresses">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddresses (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddresses(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddresses(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMPublicIPAddresses (operations As IPublicIPAddressesOperations, resourceGroupName As String, virtualMachineScaleSetName As String, virtualmachineIndex As String, networkInterfaceName As String, ipConfigurationName As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddresses : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddresses (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-226">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-226">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-227">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-227">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="f5e82-228">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="f5e82-228">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="f5e82-229">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-229">The network interface name.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="f5e82-230">IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-230">The IP configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-231">仮想マシン スケール セット内の仮想マシンの IP 構成内のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-231">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-233">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-233">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="f5e82-234">仮想マシン スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-234">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="f5e82-235">仮想マシンのインデックス。</span><span class="sxs-lookup"><span data-stu-id="f5e82-235">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="f5e82-236">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-236">The network interface name.</span></span>
            </param>
        <param name="ipConfigurationName">
            <span data-ttu-id="f5e82-237">IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-237">The IP configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-239">仮想マシン スケール セット内の仮想マシンの IP 構成内のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-239">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNext (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNext(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNext(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVirtualMachineScaleSetVMPublicIPAddressesNext (operations As IPublicIPAddressesOperations, nextPageLink As String) As IPage(Of PublicIPAddress)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesNext : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-241">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-242">仮想マシン スケール セット内の仮想マシンの IP 構成内のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-242">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f5e82-244">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f5e82-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-246">仮想マシン スケール セット内の仮想マシンの IP 構成内のすべてのパブリック IP アドレスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-246">Gets information about all public IP addresses in a virtual machine IP configuration in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.PublicIPAddress UpdateTags (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.PublicIPAddress UpdateTags(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IPublicIPAddressesOperations, resourceGroupName As String, publicIpAddressName As String, parameters As TagsObject) As PublicIPAddress" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTags (operations, resourceGroupName, publicIpAddressName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-248">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-249">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-249">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-250">パブリック IP アドレス タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-250">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-251">パブリック IP アドレス タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-251">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;" Usage="Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.PublicIPAddressesOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.PublicIPAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5e82-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5e82-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5e82-253">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-253">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f5e82-254">パブリック IP アドレスの名前。</span><span class="sxs-lookup"><span data-stu-id="f5e82-254">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5e82-255">パブリック IP アドレス タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5e82-255">Parameters supplied to update public IP address tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5e82-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5e82-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5e82-257">パブリック IP アドレス タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5e82-257">Updates public IP address tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>