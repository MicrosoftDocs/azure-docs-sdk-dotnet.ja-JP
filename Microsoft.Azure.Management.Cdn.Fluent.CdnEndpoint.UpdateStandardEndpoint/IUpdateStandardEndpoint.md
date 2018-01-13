<Type Name="IUpdateStandardEndpoint" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint">
  <TypeSignature Language="C#" Value="public interface IUpdateStandardEndpoint : Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Update.IUpdate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUpdateStandardEndpoint implements class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Update.IUpdate, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUpdateStandardEndpoint&#xA;Implements ISettable(Of IUpdate), IUpdate" />
  <TypeSignature Language="F#" Value="type IUpdateStandardEndpoint = interface&#xA;    interface IUpdate&#xA;    interface ISettable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Update.IUpdate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.ISettable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            CDN プロファイル エンドポイントの更新を許可するエンドポイントのプロパティを指定の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCompressionEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithCompressionEnabled (bool compressionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithCompressionEnabled(bool compressionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithCompressionEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCompressionEnabled (compressionEnabled As Boolean) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithCompressionEnabled : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithCompressionEnabled compressionEnabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compressionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="compressionEnabled">True の場合は、圧縮が有効なります。</param>
        <summary>
            圧縮状態を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithContentTypesToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithContentTypesToCompress (System.Collections.Generic.ISet&lt;string&gt; contentTypesToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithContentTypesToCompress(class System.Collections.Generic.ISet`1&lt;string&gt; contentTypesToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithContentTypesToCompress(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypesToCompress (contentTypesToCompress As ISet(Of String)) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypesToCompress : System.Collections.Generic.ISet&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithContentTypesToCompress contentTypesToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentTypesToCompress" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentTypesToCompress">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithContentTypeToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithContentTypeToCompress (string contentTypeToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithContentTypeToCompress(string contentTypeToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithContentTypeToCompress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypeToCompress (contentTypeToCompress As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypeToCompress : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithContentTypeToCompress contentTypeToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentTypeToCompress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="contentTypeToCompress">一覧に追加するを圧縮する単一のコンテンツ タイプ。</param>
        <summary>
            圧縮するコンテンツの種類を 1 つを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (hostName As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">カスタム ドメインのホスト名です。</param>
        <summary>
            新しい CDN エンドポイント内でカスタム ドメインを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCode As CountryISOCode) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithGeoFilter (relativePath, action, countryCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCode" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode" />
      </Parameters>
      <Docs>
        <param name="relativePath">相対パス。</param>
        <param name="action">アクション。</param>
        <param name="countryCode">ISO 2 文字の国コードです。</param>
        <summary>
            地理的フィルター リストに 1 つのエントリを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of CountryISOCode)) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithGeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt;" />
      </Parameters>
      <Docs>
        <param name="relativePath">相対パス。</param>
        <param name="action">アクション。</param>
        <param name="countryCodes">ISO 2 文字の国コードの一覧。</param>
        <summary>
            一覧については、指定された国 geo フィルター一覧を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilters (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithGeoFilters(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithGeoFilters(System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilters (geoFilters As IList(Of GeoFilter)) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithGeoFilters geoFilters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geoFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="geoFilters">地理的には、一覧がフィルター処理します。</param>
        <summary>
            地理的フィルター一覧を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHostHeader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHostHeader (string hostHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHostHeader(string hostHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithHostHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostHeader (hostHeader As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithHostHeader : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithHostHeader hostHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostHeader">ホスト ヘッダーです。</param>
        <summary>
            ホスト ヘッダーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpAllowed (bool httpAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpAllowed(bool httpAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithHttpAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpAllowed (httpAllowed As Boolean) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithHttpAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithHttpAllowed httpAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpAllowed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="httpAllowed">true の場合は、HTTP トラフィックが許可されます。</param>
        <summary>
            HTTP トラフィックが許可されたかどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpPort (int httpPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpPort(int32 httpPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpPort (httpPort As Integer) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithHttpPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithHttpPort httpPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="httpPort">ポート番号です。</param>
        <summary>
            HTTP トラフィック用のポートを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpsAllowed (bool httpsAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpsAllowed(bool httpsAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithHttpsAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsAllowed (httpsAllowed As Boolean) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithHttpsAllowed httpsAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpsAllowed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="httpsAllowed">true の場合は、HTTPS トラフィックが許可されます。</param>
        <summary>
            HTTPS トラフィックが許可されたかどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpsPort (int httpsPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithHttpsPort(int32 httpsPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsPort (httpsPort As Integer) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithHttpsPort httpsPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpsPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="httpsPort">ポート番号です。</param>
        <summary>
            HTTP トラフィック用のポートを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithOriginPath">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithOriginPath (string originPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithOriginPath(string originPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithOriginPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOriginPath (originPath As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithOriginPath : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithOriginPath originPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originPath">配信元のパス。</param>
        <summary>
            配信元のパスを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutContentTypesToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutContentTypesToCompress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutContentTypesToCompress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithoutContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutContentTypesToCompress () As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithoutContentTypesToCompress : unit -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithoutContentTypesToCompress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            圧縮するコンテンツの種類のリスト全体をクリアします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutContentTypeToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutContentTypeToCompress (string contentTypeToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutContentTypeToCompress(string contentTypeToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithoutContentTypeToCompress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutContentTypeToCompress (contentTypeToCompress As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithoutContentTypeToCompress : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithoutContentTypeToCompress contentTypeToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentTypeToCompress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="contentTypeToCompress">一覧から削除する単一のコンテンツ タイプ。</param>
        <summary>
            一覧からを圧縮するコンテンツの種類を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithoutCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCustomDomain (hostName As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithoutCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithoutCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">カスタム ドメインのホスト名。</param>
        <summary>
            CDN カスタム ドメイン内のエンドポイントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutGeoFilter (string relativePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutGeoFilter(string relativePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithoutGeoFilter(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutGeoFilter (relativePath As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithoutGeoFilter : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithoutGeoFilter relativePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativePath">相対パス。</param>
        <summary>
            地理的フィルター ボックスの一覧からエントリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutGeoFilters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutGeoFilters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithoutGeoFilters() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithoutGeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutGeoFilters () As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithoutGeoFilters : unit -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithoutGeoFilters " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            全体の地理的フィルター一覧をクリアします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithQueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithQueryStringCachingBehavior (Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint WithQueryStringCachingBehavior(valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint.WithQueryStringCachingBehavior(Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithQueryStringCachingBehavior (cachingBehavior As QueryStringCachingBehavior) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithQueryStringCachingBehavior : Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iUpdateStandardEndpoint.WithQueryStringCachingBehavior cachingBehavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingBehavior" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior" />
      </Parameters>
      <Docs>
        <param name="cachingBehavior">クエリ文字列のキャッシュの動作の値を設定します。</param>
        <summary>
            クエリ文字列のキャッシュ動作を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>