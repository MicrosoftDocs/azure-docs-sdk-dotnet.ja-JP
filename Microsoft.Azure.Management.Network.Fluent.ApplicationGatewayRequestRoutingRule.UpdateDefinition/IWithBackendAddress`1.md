<Type Name="IWithBackendAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendAddress&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendAddress`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1" />
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
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</typeparam>
    <summary>
            Application gateway のステージは、ルーティング ルールの定義をこの要求のルーティング規則で使用されるバックエンド アドレスを追加する許可を要求します。
            [なし] がまだこの規則に関連付ける場合は、新しいバックエンドが作成されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1.ToBackendFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendFqdn (fqdn As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">完全修飾ドメイン名です。</param>
        <summary>
            このルールに関連付けられているバックエンドに、FQDN (完全修飾ドメイン名) を追加します。
            バックエンドが行われていない場合このルールに関連付けられていない、新しいと、自動生成された名前で作成されます。
            この呼び出しは、複数の Fqdn を追加する、シーケンスで使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1.ToBackendIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendIPAddress (ipAddress As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">IP アドレス。</param>
        <summary>
            このルールに関連付けられているバックエンドに IP アドレスを追加します。
            バックエンドが行われていない場合このルールに関連付けられていない、新しいと、自動生成された名前で作成されます。
            この呼び出しは、複数の IP アドレスを追加する、シーケンスで使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>