<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Application gateway のステージでは、ルーティング ルール更新できるようにするにルーティング規則を関連付けるには、バックエンドの指定を要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackend.ToBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithBackend.ToBackend name" />
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
        <param name="name">既存のバックエンドの名前。</param>
        <summary>
            このアプリケーション ゲートウェイ上の既存のバックエンドを要求のルーティング規則を関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>