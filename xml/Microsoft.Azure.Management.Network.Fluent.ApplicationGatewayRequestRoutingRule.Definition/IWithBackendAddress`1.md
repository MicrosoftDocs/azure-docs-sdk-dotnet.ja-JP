<Type Name="IWithBackendAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendAddress&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressBeta&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendAddress`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressBeta`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendAddress(Of ParentT)&#xA;Implements IBeta, IWithBackendAddressBeta(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackendAddress&lt;'ParentT&gt; = interface&#xA;    interface IWithBackendAddressBeta&lt;'ParentT&gt;&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressBeta&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b6590-101">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="b6590-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b6590-102">Application gateway のステージは、ルーティング ルールの定義をこの要求のルーティング規則で使用されるバックエンド アドレスを追加する許可を要求します。</span><span class="sxs-lookup"><span data-stu-id="b6590-102">The stage of an application gateway request routing rule definition allowing to add an address to the backend used by this request routing rule.</span></span>
            <span data-ttu-id="b6590-103">[なし] がまだこの規則に関連付ける場合は、新しいバックエンドが作成されます。</span><span class="sxs-lookup"><span data-stu-id="b6590-103">A new backend will be created if none is associated with this rule yet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddress`1.ToBackendFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendFqdn (fqdn As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="b6590-104">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="b6590-104">A fully qualified domain name.</span></span></param>
        <summary>
            <span data-ttu-id="b6590-105">このルールに関連付けられているバックエンドに、FQDN (完全修飾ドメイン名) を追加します。</span><span class="sxs-lookup"><span data-stu-id="b6590-105">Adds an FQDN (fully qualified domain name) to the backend associated with this rule.</span></span>
            <span data-ttu-id="b6590-106">バックエンドが行われていない場合このルールに関連付けられていない、新しいと、自動生成された名前で作成されます。</span><span class="sxs-lookup"><span data-stu-id="b6590-106">If no backend has been associated with this rule yet, a new one will be created with an auto-generated name.</span></span>
            <span data-ttu-id="b6590-107">この呼び出しは、複数の Fqdn を追加する、シーケンスで使用できます。</span><span class="sxs-lookup"><span data-stu-id="b6590-107">This call can be used in a sequence to add multiple FQDNs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b6590-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b6590-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddress`1.ToBackendIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendIPAddress (ipAddress As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="b6590-109">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="b6590-109">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="b6590-110">このルールに関連付けられているバックエンドに IP アドレスを追加します。</span><span class="sxs-lookup"><span data-stu-id="b6590-110">Adds an IP address to the backend associated with this rule.</span></span>
            <span data-ttu-id="b6590-111">バックエンドが行われていない場合このルールに関連付けられていない、新しいと、自動生成された名前で作成されます。</span><span class="sxs-lookup"><span data-stu-id="b6590-111">If no backend has been associated with this rule yet, a new one will be created with an auto-generated name.</span></span>
            <span data-ttu-id="b6590-112">この呼び出しは、複数の IP アドレスを追加する、シーケンスで使用できます。</span><span class="sxs-lookup"><span data-stu-id="b6590-112">This call can be used in a sequence to add multiple IP addresses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b6590-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b6590-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>