<Type Name="IWithTxtRecordTextValue&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValue&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTxtRecordTextValue&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTxtRecordTextValue`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValue`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="3a647-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="3a647-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="3a647-102">最初の TXT レコードを追加できるように TXT レコードの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="3a647-102">The stage of the TXT record definition allowing to add first TXT record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithText">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValueOrAttachable&lt;ParentT&gt; WithText (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValueOrAttachable`1&lt;!ParentT&gt; WithText(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValue`1.WithText(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithText (text As String) As IWithTxtRecordTextValueOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithText : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValueOrAttachable&lt;'ParentT&gt;" Usage="iWithTxtRecordTextValue.WithText text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTxtRecordTextValueOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text"><span data-ttu-id="3a647-103">テキスト値。</span><span class="sxs-lookup"><span data-stu-id="3a647-103">The text value.</span></span></param>
        <summary>
            <span data-ttu-id="3a647-104">このレコード セット内の指定されたテキスト持つ Txt レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="3a647-104">Creates a Txt record with the given text in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3a647-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3a647-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>