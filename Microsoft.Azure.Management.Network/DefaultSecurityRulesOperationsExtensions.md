<Type Name="DefaultSecurityRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DefaultSecurityRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DefaultSecurityRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DefaultSecurityRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DefaultSecurityRulesOperationsExtensions = class" />
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
            <span data-ttu-id="4649c-101">DefaultSecurityRulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4649c-101">Extension methods for DefaultSecurityRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.SecurityRule Get (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string defaultSecurityRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.SecurityRule Get(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string defaultSecurityRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDefaultSecurityRulesOperations, resourceGroupName As String, networkSecurityGroupName As String, defaultSecurityRuleName As String) As SecurityRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.SecurityRule" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.Get (operations, resourceGroupName, networkSecurityGroupName, defaultSecurityRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="defaultSecurityRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4649c-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-103">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="4649c-104">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-104">The name of the network security group.</span></span>
            </param>
        <param name="defaultSecurityRuleName">
            <span data-ttu-id="4649c-105">既定のセキュリティの規則の名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-105">The name of the default security rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-106">指定した既定のネットワーク セキュリティ ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-106">Get the specified default network security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; GetAsync (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string defaultSecurityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; GetAsync(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string defaultSecurityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, defaultSecurityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="defaultSecurityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4649c-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-108">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="4649c-109">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-109">The name of the network security group.</span></span>
            </param>
        <param name="defaultSecurityRuleName">
            <span data-ttu-id="4649c-110">既定のセキュリティの規則の名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-110">The name of the default security rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4649c-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4649c-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-112">指定した既定のネットワーク セキュリティ ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-112">Get the specified default network security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; List (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; List(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.List(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDefaultSecurityRulesOperations, resourceGroupName As String, networkSecurityGroupName As String) As IPage(Of SecurityRule)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.List (operations, resourceGroupName, networkSecurityGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4649c-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-114">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="4649c-115">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-115">The name of the network security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-116">ネットワーク セキュリティ グループ内のすべての既定でセキュリティの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-116">Gets all default security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4649c-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-118">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="4649c-119">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4649c-119">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4649c-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4649c-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-121">ネットワーク セキュリティ グループ内のすべての既定でセキュリティの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-121">Gets all default security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; ListNext (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; ListNext(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDefaultSecurityRulesOperations, nextPageLink As String) As IPage(Of SecurityRule)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4649c-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4649c-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-124">ネットワーク セキュリティ グループ内のすべての既定でセキュリティの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-124">Gets all default security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.DefaultSecurityRulesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IDefaultSecurityRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4649c-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4649c-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4649c-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4649c-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4649c-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4649c-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4649c-128">ネットワーク セキュリティ グループ内のすべての既定でセキュリティの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="4649c-128">Gets all default security rules in a network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>