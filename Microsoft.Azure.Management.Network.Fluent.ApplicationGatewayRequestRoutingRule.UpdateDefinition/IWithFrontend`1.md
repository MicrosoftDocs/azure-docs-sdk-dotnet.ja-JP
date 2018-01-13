<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</typeparam>
    <summary>
            Application gateway のステージでは、ルーティング ルールの定義に適用する規則のフロント エンドを指定する許可を要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; FromPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; FromPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1.FromPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイのプライベート (内部) フロント エンドに適用するルールを有効にします。
            プライベート フロント エンド IP 構成がまだ存在しない場合は、自動生成の名前で作成されます。
            アプリケーション ゲートウェイには、そのプライベート フロント エンドの指定されたサブネットはない場合、は、withExistingSubnet(...) を使用して、アプリケーション ゲートウェイ定義の省略可能な設定で、特定のサブネットが指定されていない限り、自動的に 1 つ作成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; FromPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; FromPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1.FromPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイのパブリック (インターネット側) フロント エンドに適用するルールを有効にします。
            パブリック フロント エンド IP 構成がまだ存在しない場合は、自動生成の名前で作成されます。
            アプリケーション ゲートウェイには、そのパブリック フロント エンドに対して指定されたパブリック IP アドレスがない、1 つが自動的に作成を使用して、アプリケーション ゲートウェイ定義の省略可能な設定で特定のパブリック IP アドレスが指定されていません。withExistingPublicIPAddress(...) または withNewPublicIPAddress(...) します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>