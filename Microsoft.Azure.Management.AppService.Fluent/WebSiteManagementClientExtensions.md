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
            WebSiteManagementClient の拡張メソッド。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            リソース名を確認してください。
            </param>
        <param name="type">
            リソースの種類の検証に使用します。 使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'
            </param>
        <param name="isFqdn">
            完全修飾ドメイン名です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            使用可能なリソース名を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            使用可能なリソース名を確認します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ユーザーの発行を取得
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ユーザーの発行を取得
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Sku を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            すべての Sku を一覧表示します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure の web サイトの利用可能なソース制御を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure の web サイトの利用可能なソース制御を取得します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure の web サイトの利用可能なソース制御を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure の web サイトの利用可能なソース制御を取得します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="moveResourceEnvelope">
            移動するリソースを表すオブジェクト。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ間でリソースを移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ間でリソースを移動します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="userDetails">
            発行ユーザーの詳細
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ユーザーの公開の更新
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ユーザーの公開の更新
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceControlType">
            ソース管理の種類
            </param>
        <param name="requestMessage">
            ソース管理のトークンの情報
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新プログラムのソース制御トークン
            </summary>
        <returns>To be added.</returns>
        <remarks>
            更新プログラムのソース制御トークン
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="validateRequest">
            検証する、リソースを持つ要求です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを作成できる場合を検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソースを作成できる場合を検証します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="moveResourceEnvelope">
            移動するリソースを表すオブジェクト。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを移動できるかどうかを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソースを移動できるかどうかを検証します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>