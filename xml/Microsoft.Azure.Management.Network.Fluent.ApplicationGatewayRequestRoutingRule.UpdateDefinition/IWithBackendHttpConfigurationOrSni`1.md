<Type Name="IWithBackendHttpConfigurationOrSni&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigurationOrSni&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfigurationOrSni&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.UpdateDefinition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfigurationOrSni`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.UpdateDefinition.IWithServerNameIndication`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1&lt;!ParentT&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigurationOrSni`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfigurationOrSni(Of ParentT)&#xA;Implements IWithBackendHttpConfiguration(Of ParentT), IWithServerNameIndication(Of IWithBackendHttpConfiguration(Of ParentT))" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfigurationOrSni&lt;'ParentT&gt; = interface&#xA;    interface IWithBackendHttpConfiguration&lt;'ParentT&gt;&#xA;    interface IWithServerNameIndication&lt;IWithBackendHttpConfiguration&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.UpdateDefinition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="11df1-101">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="11df1-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="11df1-102">アプリケーション ゲートウェイ要求ルーティング ルール定義できるようにする、アプリケーション ゲートウェイがバックエンドと SSL の複数の web サイトを提供している場合は、サーバー名を示す値を必要とするステージが必要です。</span><span class="sxs-lookup"><span data-stu-id="11df1-102">The stage of an application gateway request routing rule definition allowing to require server name indication if the application gateway is serving multiple websites in its backends and SSL is required.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>