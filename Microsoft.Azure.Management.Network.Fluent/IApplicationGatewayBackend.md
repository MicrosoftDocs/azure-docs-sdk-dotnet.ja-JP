<Type Name="IApplicationGatewayBackend" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayBackend : Microsoft.Azure.Management.Network.Fluent.IHasBackendNics, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayBackend implements class Microsoft.Azure.Management.Network.Fluent.IHasBackendNics, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayBackend&#xA;Implements IChildResource(Of IApplicationGateway), IHasBackendNics, IHasInner(Of ApplicationGatewayBackendAddressPoolInner), IHasParent(Of IApplicationGateway)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayBackend = interface&#xA;    interface IHasInner&lt;ApplicationGatewayBackendAddressPoolInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasBackendNics" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasBackendNics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddressPoolInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アプリケーション ゲートウェイのバックエンドの変更できないクライアント側表現。
            </summary>
    <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Addresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress&gt; Addresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress&gt; Addresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend.Addresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Addresses As IReadOnlyList(Of ApplicationGatewayBackendAddress)" />
      <MemberSignature Language="F#" Value="member this.Addresses : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend.Addresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            FQDN でインデックス付けされた、アプリケーション ゲートウェイのバックエンドでアドレスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsFqdn">
      <MemberSignature Language="C#" Value="public bool ContainsFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend.ContainsFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsFqdn (fqdn As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsFqdn : string -&gt; bool" Usage="iApplicationGatewayBackend.ContainsFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">完全修飾ドメイン名 (FQDN) です。</param>
        <summary>
            このバックエンド アドレス プールにより指定された FQDN が参照されているかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>このバックエンド、それ以外の場合は false で指定された FQDN が参照されている場合は true。</return>
      </Docs>
    </Member>
    <Member MemberName="ContainsIPAddress">
      <MemberSignature Language="C#" Value="public bool ContainsIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend.ContainsIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsIPAddress (ipAddress As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsIPAddress : string -&gt; bool" Usage="iApplicationGatewayBackend.ContainsIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">IP アドレス。</param>
        <summary>
            指定した IP アドレスがこのバックエンド アドレス プールで参照されているかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>このバックエンド、それ以外の場合は false を指定した IP アドレスが参照されている場合は true。</return>
      </Docs>
    </Member>
  </Members>
</Type>