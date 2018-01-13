<Type Name="IWithStandardAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithStandardAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IAttachableStandard&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStandardAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IAttachableStandard`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStandardAttach(Of ParentT)&#xA;Implements IAttachableStandard(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithStandardAttach&lt;'ParentT&gt; = interface&#xA;    interface IAttachableStandard&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IAttachableStandard&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親 CDN プロファイルの更新の段階です。</typeparam>
    <summary>
            CDN プロファイル標準 Akamai や標準 Verizon のエンドポイント定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、または CDN プロファイルのエンドポイントの定義は、親 CDN プロファイル定義に関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCompressionEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithCompressionEnabled (bool compressionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithCompressionEnabled(bool compressionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithCompressionEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCompressionEnabled (compressionEnabled As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCompressionEnabled : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithCompressionEnabled compressionEnabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compressionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="compressionEnabled">True の場合は、圧縮は有効、無効になっていますそれ以外の場合。</param>
        <summary>
            圧縮状態を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithContentTypesToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithContentTypesToCompress (System.Collections.Generic.ISet&lt;string&gt; contentTypesToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithContentTypesToCompress(class System.Collections.Generic.ISet`1&lt;string&gt; contentTypesToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithContentTypesToCompress(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypesToCompress (contentTypesToCompress As ISet(Of String)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypesToCompress : System.Collections.Generic.ISet&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithContentTypesToCompress contentTypesToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithContentTypeToCompress (string contentTypeToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithContentTypeToCompress(string contentTypeToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithContentTypeToCompress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypeToCompress (contentTypeToCompress As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypeToCompress : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithContentTypeToCompress contentTypeToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (hostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">カスタム ドメインのホスト名。</param>
        <summary>
            新しい CDN エンドポイント内でカスタム ドメインを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCode As CountryISOCode) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilter (relativePath, action, countryCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of CountryISOCode)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilters (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilters(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithGeoFilters(System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilters (geoFilters As IList(Of GeoFilter)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilters geoFilters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geoFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="geoFilters">地理的を設定する ボックスの一覧がフィルター処理します。</param>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithHostHeader (string hostHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithHostHeader(string hostHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithHostHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostHeader (hostHeader As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHostHeader : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHostHeader hostHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithHttpAllowed (bool httpAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpAllowed(bool httpAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithHttpAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpAllowed (httpAllowed As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpAllowed httpAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithHttpPort (int httpPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpPort(int32 httpPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpPort (httpPort As Integer) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpPort httpPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithHttpsAllowed (bool httpsAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpsAllowed(bool httpsAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithHttpsAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsAllowed (httpsAllowed As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpsAllowed httpsAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithHttpsPort (int httpsPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpsPort(int32 httpsPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsPort (httpsPort As Integer) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpsPort httpsPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpsPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="httpsPort">ポート番号です。</param>
        <summary>
            HTTPS トラフィック用のポートを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithOriginPath">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithOriginPath (string originPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithOriginPath(string originPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithOriginPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOriginPath (originPath As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOriginPath : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithOriginPath originPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithQueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithQueryStringCachingBehavior (Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithQueryStringCachingBehavior(valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1.WithQueryStringCachingBehavior(Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithQueryStringCachingBehavior (cachingBehavior As QueryStringCachingBehavior) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithQueryStringCachingBehavior : Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithQueryStringCachingBehavior cachingBehavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingBehavior" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior" />
      </Parameters>
      <Docs>
        <param name="cachingBehavior">キャッシュの動作のクエリ文字列。</param>
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