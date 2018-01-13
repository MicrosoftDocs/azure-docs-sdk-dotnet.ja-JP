<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Application gateway のステージでは、ルーティング ルールの更新を許可するルーティング規則を関連付ける既存のリスナーを指定を要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener.FromListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithListener.FromListener name" />
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
        <param name="name">参照するリスナーの名前。</param>
        <summary>
            要求のルーティング規則を既存のフロント エンド リスナーに関連付けます。
            また、一度に 2 つ以上の要求ルーティング ルールによって指定されたリスナーを使用できることに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>