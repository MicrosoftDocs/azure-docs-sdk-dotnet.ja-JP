<Type Name="IWithTxtRecordTextValue&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValue&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTxtRecordTextValue&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTxtRecordTextValue`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTxtRecordTextValue(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTxtRecordTextValue&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            最初の Txt レコードを追加できるように TXT レコードの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithText">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValueOrAttachable&lt;ParentT&gt; WithText (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValueOrAttachable`1&lt;!ParentT&gt; WithText(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValue`1.WithText(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithText (text As String) As IWithTxtRecordTextValueOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithText : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValueOrAttachable&lt;'ParentT&gt;" Usage="iWithTxtRecordTextValue.WithText text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTxtRecordTextValueOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text">テキスト値。</param>
        <summary>
            このレコード セット内の指定されたテキスト持つ TXT レコードを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>