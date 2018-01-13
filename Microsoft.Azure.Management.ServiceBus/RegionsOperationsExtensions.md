<Type Name="RegionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RegionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RegionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RegionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RegionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6bb7c-101">RegionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-101">Extension methods for RegionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListBySku">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt; ListBySku (this Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt; ListBySku(class Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySku(Microsoft.Azure.Management.ServiceBus.IRegionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySku (operations As IRegionsOperations, sku As String) As IPage(Of PremiumMessagingRegions)" />
      <MemberSignature Language="F#" Value="static member ListBySku : Microsoft.Azure.Management.ServiceBus.IRegionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySku (operations, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRegionsOperations" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6bb7c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="sku">
            <span data-ttu-id="6bb7c-103">Sku の種類。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-103">The sku type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bb7c-104">指定された sku の使用可能なリージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-104">Gets the available Regions for a given sku</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySkuAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt; ListBySkuAsync (this Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string sku, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt; ListBySkuAsync(class Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string sku, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuAsync(Microsoft.Azure.Management.ServiceBus.IRegionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySkuAsync : Microsoft.Azure.Management.ServiceBus.IRegionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuAsync (operations, sku, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions/&lt;ListBySkuAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRegionsOperations" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6bb7c-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-105">The operations group for this extension method.</span></span>
            </param>
        <param name="sku">
            <span data-ttu-id="6bb7c-106">Sku の種類。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-106">The sku type.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6bb7c-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bb7c-108">指定された sku の使用可能なリージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-108">Gets the available Regions for a given sku</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySkuNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt; ListBySkuNext (this Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt; ListBySkuNext(class Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuNext(Microsoft.Azure.Management.ServiceBus.IRegionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySkuNext (operations As IRegionsOperations, nextPageLink As String) As IPage(Of PremiumMessagingRegions)" />
      <MemberSignature Language="F#" Value="static member ListBySkuNext : Microsoft.Azure.Management.ServiceBus.IRegionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRegionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6bb7c-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-109">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6bb7c-110">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-110">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bb7c-111">指定された sku の使用可能なリージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-111">Gets the available Regions for a given sku</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySkuNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt; ListBySkuNextAsync (this Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt; ListBySkuNextAsync(class Microsoft.Azure.Management.ServiceBus.IRegionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuNextAsync(Microsoft.Azure.Management.ServiceBus.IRegionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySkuNextAsync : Microsoft.Azure.Management.ServiceBus.IRegionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions.ListBySkuNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RegionsOperationsExtensions/&lt;ListBySkuNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.PremiumMessagingRegions&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRegionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6bb7c-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-112">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6bb7c-113">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-113">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6bb7c-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6bb7c-115">指定された sku の使用可能なリージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6bb7c-115">Gets the available Regions for a given sku</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>