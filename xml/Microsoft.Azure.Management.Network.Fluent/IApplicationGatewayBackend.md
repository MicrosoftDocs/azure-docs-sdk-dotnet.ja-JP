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
            <span data-ttu-id="f512a-101">アプリケーション ゲートウェイのバックエンドの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="f512a-101">An immutable client-side representation of an application gateway backend.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f512a-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="f512a-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
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
            <span data-ttu-id="f512a-103">FQDN でインデックス付けされた、アプリケーション ゲートウェイのバックエンドでアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f512a-103">Gets addresses on the backend of the application gateway, indexed by their FQDN.</span></span>
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
        <param name="fqdn"><span data-ttu-id="f512a-104">完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="f512a-104">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="f512a-105">このバックエンド アドレス プールにより指定された FQDN が参照されているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="f512a-105">Checks whether the specified FQDN is referenced by this backend address pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f512a-106">このバックエンド、それ以外の場合は false で指定された FQDN が参照されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="f512a-106">True if the specified FQDN is referenced by this backend, else false.</span></span></return>
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
        <param name="ipAddress"><span data-ttu-id="f512a-107">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="f512a-107">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="f512a-108">指定した IP アドレスがこのバックエンド アドレス プールで参照されているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="f512a-108">Checks whether the specified IP address is referenced by this backend address pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f512a-109">このバックエンド、それ以外の場合は false を指定した IP アドレスが参照されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="f512a-109">True if the specified IP address is referenced by this backend, else false.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>