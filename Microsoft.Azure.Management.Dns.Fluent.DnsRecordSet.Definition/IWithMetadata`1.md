<Type Name="IWithMetadata&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMetadata&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithMetadata&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMetadata`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMetadata`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMetadata(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithMetadata&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">UpdateDefinitionStages.WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            レコードのステージでは、メタデータを指定できるように定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;ParentT&gt; WithMetadata (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach`1&lt;!ParentT&gt; WithMetadata(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMetadata`1.WithMetadata(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMetadata (key As String, value As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMetadata : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithMetadata.WithMetadata (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">メタデータのキー。</param>
        <param name="value">メタデータの値です。</param>
        <summary>
            リソースに、メタデータを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>