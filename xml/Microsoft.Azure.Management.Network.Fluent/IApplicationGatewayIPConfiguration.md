<Type Name="IApplicationGatewayIPConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayIPConfiguration implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayIPConfiguration&#xA;Implements IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayIPConfigurationInner), IHasParent(Of IApplicationGateway)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayIPConfiguration = interface&#xA;    interface IHasInner&lt;ApplicationGatewayIPConfigurationInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6b9f9-101">アプリケーション ゲートウェイの IP 構成の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="6b9f9-101">An immutable client-side representation of an application gateway IP configuration.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6b9f9-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="6b9f9-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.GetSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubnet () As ISubnet" />
      <MemberSignature Language="F#" Value="abstract member GetSubnet : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ISubnet" Usage="iApplicationGatewayIPConfiguration.GetSubnet " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ISubnet</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="6b9f9-103">ノートには、アプリケーション ゲートウェイ サブネットをこの結果、Azure に別個の呼び出し。</span><span class="sxs-lookup"><span data-stu-id="6b9f9-103">The subnet the application gateway is in Note, this results in a separate call to Azure.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="NetworkId">
      <MemberSignature Language="C#" Value="public string NetworkId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetworkId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.NetworkId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkId As String" />
      <MemberSignature Language="F#" Value="member this.NetworkId : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.NetworkId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b9f9-104">アプリケーション ゲートウェイが、仮想ネットワークのリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="6b9f9-104">Gets the resource ID of the virtual network the application gateway is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetName">
      <MemberSignature Language="C#" Value="public string SubnetName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.SubnetName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubnetName As String" />
      <MemberSignature Language="F#" Value="member this.SubnetName : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.SubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b9f9-105">そのアプリケーション ゲートウェイ サブネットの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6b9f9-105">Gets the name of the subnet the application gateway is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>