<Type Name="IApplicationGatewayFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayFrontend : Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayFrontend implements class Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, class Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayFrontend&#xA;Implements IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayFrontendIPConfigurationInner), IHasParent(Of IApplicationGateway), IHasPrivateIPAddress, IHasPublicIPAddress, IHasSubnet" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayFrontend = interface&#xA;    interface IHasInner&lt;ApplicationGatewayFrontendIPConfigurationInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasPrivateIPAddress&#xA;    interface IHasSubnet&#xA;    interface IHasPublicIPAddress" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bfe19-101">アプリケーション ゲートウェイのフロント エンドの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="bfe19-101">An immutable client-side representation of an application gateway frontend.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="bfe19-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="bfe19-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.GetSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubnet () As ISubnet" />
      <MemberSignature Language="F#" Value="abstract member GetSubnet : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ISubnet" Usage="iApplicationGatewayFrontend.GetSubnet " />
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
        <return><span data-ttu-id="bfe19-103">関連付けられているサブネットです。</span><span class="sxs-lookup"><span data-stu-id="bfe19-103">The associated subnet.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="IsPrivate">
      <MemberSignature Language="C#" Value="public bool IsPrivate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPrivate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPrivate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivate As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPrivate : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPrivate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfe19-104">取得 true は、フロント エンド プライベート IP アドレスを使用してアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="bfe19-104">Gets true is the frontend is accessible via an private IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublic">
      <MemberSignature Language="C#" Value="public bool IsPublic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPublic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPublic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublic : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPublic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfe19-105">フロント エンドは、パブリック IP アドレス、それ以外の場合は false を使用してアクセスできる場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="bfe19-105">Gets true if the frontend is accessible via a public IP address, else false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>