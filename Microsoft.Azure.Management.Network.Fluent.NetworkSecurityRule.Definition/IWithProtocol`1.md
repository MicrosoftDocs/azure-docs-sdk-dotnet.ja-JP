<Type Name="IWithProtocol&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithProtocol&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithProtocol&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProtocol`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithProtocol`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProtocol(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithProtocol&lt;'ParentT&gt; = interface" />
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
            セキュリティ ルールの定義を指定するに規則が適用されるプロトコルの許可の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAnyProtocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt; WithAnyProtocol ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithAnyProtocol() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithProtocol`1.WithAnyProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAnyProtocol () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAnyProtocol : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithProtocol.WithAnyProtocol " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このルールは、任意のサポートされているプロトコルを適用するは、します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithProtocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt; WithProtocol (string protocol);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithProtocol(string protocol) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithProtocol`1.WithProtocol(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtocol (protocol As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithProtocol : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithProtocol.WithProtocol protocol" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">サポートされるプロトコルのいずれか。</param>
        <summary>
            この規則を適用するプロトコルを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>