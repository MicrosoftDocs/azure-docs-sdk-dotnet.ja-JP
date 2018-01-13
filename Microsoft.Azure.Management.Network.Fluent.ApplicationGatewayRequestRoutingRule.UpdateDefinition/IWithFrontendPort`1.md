<Type Name="IWithFrontendPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort&lt;'ParentT&gt; = interface" />
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
            Application gateway のステージに関連付けるリスナーと、特定のポート番号とプロトコルのフロント エンドを作成できるようにするルーティング ルールの定義を要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromFrontendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;ParentT&gt; FromFrontendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect`1&lt;!ParentT&gt; FromFrontendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1.FromFrontendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromFrontendHttpPort (portNumber As Integer) As IWithBackendHttpConfigOrRedirect(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromFrontendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;'ParentT&gt;" Usage="iWithFrontendPort.FromFrontendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromFrontendHttpsPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;ParentT&gt; FromFrontendHttpsPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate`1&lt;!ParentT&gt; FromFrontendHttpsPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1.FromFrontendHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromFrontendHttpsPort (portNumber As Integer) As IWithSslCertificate(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromFrontendHttpsPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;'ParentT&gt;" Usage="iWithFrontendPort.FromFrontendHttpsPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">リッスンするポート番号。</param>
        <summary>
            このルールを指定したポート番号と、HTTPS プロトコルの新しいリスナーを関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義上、または別のプロトコルに対する指定したポート番号が既に使用されている場合は null の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>