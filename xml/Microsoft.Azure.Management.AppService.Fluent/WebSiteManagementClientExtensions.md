<Type Name="WebSiteManagementClientExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class WebSiteManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebSiteManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebSiteManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type WebSiteManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="65928-101">WebSiteManagementClient の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="65928-101">Extension methods for WebSiteManagementClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync (operations, name, type, isFqdn, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;CheckNameAvailabilityAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="65928-103">リソース名を確認してください。</span><span class="sxs-lookup"><span data-stu-id="65928-103">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="65928-104">リソースの種類の検証に使用します。</span><span class="sxs-lookup"><span data-stu-id="65928-104">Resource type used for verification.</span></span> <span data-ttu-id="65928-105">使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'</span><span class="sxs-lookup"><span data-stu-id="65928-105">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="65928-106">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="65928-106">Is fully qualified domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-108">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="65928-108">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-109">使用可能なリソース名を確認します。</span><span class="sxs-lookup"><span data-stu-id="65928-109">Check if a resource name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt; GetPublishingUserAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt; GetPublishingUserAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.GetPublishingUserAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPublishingUserAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.GetPublishingUserAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;GetPublishingUserAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-110">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-112">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="65928-112">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-113">ユーザーの発行を取得</span><span class="sxs-lookup"><span data-stu-id="65928-113">Gets publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListGeoRegionsAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListGeoRegionsAsync (operations, sku, linuxWorkersEnabled, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListGeoRegionsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="linuxWorkersEnabled">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListGeoRegionsNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersNextAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner&gt; ListSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner&gt; ListSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSkusAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListSkusAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-114">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-116">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="65928-116">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-117">すべての Sku を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="65928-117">List all SKUs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt; ListSourceControlsAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt; ListSourceControlsAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSourceControlsAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSourceControlsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListSourceControlsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-118">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-120">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="65928-120">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-121">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="65928-121">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt; ListSourceControlsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt; ListSourceControlsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSourceControlsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ListSourceControlsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ListSourceControlsNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="65928-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="65928-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-125">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="65928-125">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-126">Azure の web サイトの利用可能なソース制御を取得します。</span><span class="sxs-lookup"><span data-stu-id="65928-126">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.MoveAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.MoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;MoveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="65928-128">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="65928-128">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="65928-129">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="65928-129">Object that represents the resource to move.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-131">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="65928-131">Move resources between resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-132">リソース グループ間でリソースを移動します。</span><span class="sxs-lookup"><span data-stu-id="65928-132">Move resources between resource groups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt; UpdatePublishingUserAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, Microsoft.Azure.Management.AppService.Fluent.Models.UserInner userDetails, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt; UpdatePublishingUserAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, class Microsoft.Azure.Management.AppService.Fluent.Models.UserInner userDetails, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.UpdatePublishingUserAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,Microsoft.Azure.Management.AppService.Fluent.Models.UserInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePublishingUserAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * Microsoft.Azure.Management.AppService.Fluent.Models.UserInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.UpdatePublishingUserAsync (operations, userDetails, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;UpdatePublishingUserAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-133">The operations group for this extension method.</span></span>
            </param>
        <param name="userDetails">
            <span data-ttu-id="65928-134">発行ユーザーの詳細</span><span class="sxs-lookup"><span data-stu-id="65928-134">Details of publishing user</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-136">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="65928-136">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-137">ユーザーの公開の更新</span><span class="sxs-lookup"><span data-stu-id="65928-137">Updates publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt; UpdateSourceControlAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string sourceControlType, Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt; UpdateSourceControlAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string sourceControlType, class Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.UpdateSourceControlAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSourceControlAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.UpdateSourceControlAsync (operations, sourceControlType, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;UpdateSourceControlAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SourceControlInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-138">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceControlType">
            <span data-ttu-id="65928-139">ソース管理の種類</span><span class="sxs-lookup"><span data-stu-id="65928-139">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="65928-140">ソース管理のトークンの情報</span><span class="sxs-lookup"><span data-stu-id="65928-140">Source control token information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-142">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="65928-142">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-143">更新プログラムのソース制御トークン</span><span class="sxs-lookup"><span data-stu-id="65928-143">Updates source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner&gt; ValidateAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner validateRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner&gt; ValidateAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner validateRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ValidateAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ValidateAsync (operations, resourceGroupName, validateRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ValidateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="65928-145">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="65928-145">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="65928-146">検証する、リソースを持つ要求です。</span><span class="sxs-lookup"><span data-stu-id="65928-146">Request with the resources to validate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-148">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="65928-148">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-149">リソースを作成できる場合を検証します。</span><span class="sxs-lookup"><span data-stu-id="65928-149">Validate if a resource can be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidateMoveAsync (this Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidateMoveAsync(class Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ValidateMoveAsync(Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveAsync : Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient * string * Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions.ValidateMoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.WebSiteManagementClientExtensions/&lt;ValidateMoveAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65928-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="65928-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="65928-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="65928-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="65928-152">移動するリソースを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="65928-152">Object that represents the resource to move.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65928-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="65928-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65928-154">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="65928-154">Validate whether a resource can be moved.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="65928-155">リソースを移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="65928-155">Validate whether a resource can be moved.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>