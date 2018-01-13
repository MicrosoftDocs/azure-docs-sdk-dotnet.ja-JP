<Type Name="IWithDescription&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDescription&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDescription`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDescription(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDescription&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            指定する説明を許可するネットワーク ルールの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt; WithDescription (string description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithDescription(string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription`1.WithDescription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDescription (description As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDescription : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDescription.WithDescription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="description">このセキュリティの規則に関連付けるテキストの説明。</param>
        <summary>
            このセキュリティの規則の説明を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>