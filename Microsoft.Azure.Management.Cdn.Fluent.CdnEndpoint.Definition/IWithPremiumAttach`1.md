<Type Name="IWithPremiumAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPremiumAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachablePremium&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPremiumAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachablePremium`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPremiumAttach(Of ParentT)&#xA;Implements IAttachablePremium(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPremiumAttach&lt;'ParentT&gt; = interface&#xA;    interface IAttachablePremium&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachablePremium&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親 CDN プロファイル定義の段階です。</typeparam>
    <summary>
            CDN プロファイル Premium Verizon エンドポイント定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、または CDN プロファイルのエンドポイントの定義は、親 CDN プロファイル定義に関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (hostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">カスタム ドメインのホスト名。</param>
        <summary>
            新しい CDN エンドポイント用カスタム ドメインを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHostHeader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithHostHeader (string hostHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithHostHeader(string hostHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithHostHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostHeader (hostHeader As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHostHeader : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithHostHeader hostHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithHttpAllowed (bool httpAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithHttpAllowed(bool httpAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithHttpAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpAllowed (httpAllowed As Boolean) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithHttpAllowed httpAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpAllowed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="httpAllowed">True の場合は、HTTP トラフィックが許可されます。</param>
        <summary>
            HTTP トラフィックが許可されたかどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithHttpPort (int httpPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithHttpPort(int32 httpPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpPort (httpPort As Integer) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithHttpPort httpPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithHttpsAllowed (bool httpsAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithHttpsAllowed(bool httpsAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithHttpsAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsAllowed (httpsAllowed As Boolean) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithHttpsAllowed httpsAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithHttpsPort (int httpsPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithHttpsPort(int32 httpsPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsPort (httpsPort As Integer) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithHttpsPort httpsPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithOriginPath (string originPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithOriginPath(string originPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1.WithOriginPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOriginPath (originPath As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOriginPath : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iWithPremiumAttach.WithOriginPath originPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
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
  </Members>
</Type>