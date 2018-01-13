<Type Name="IWithBackendHttpConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfiguration" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Application gateway のステージでは、ルーティング ルールの更新を許可するルーティング規則を関連付けるバックエンド HTTP 設定の構成を指定するを要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">バックエンド HTTP 設定の構成の名前。</param>
        <summary>
            この要求のルーティングの規則に指定されたバックエンド HTTP 設定の構成を関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>