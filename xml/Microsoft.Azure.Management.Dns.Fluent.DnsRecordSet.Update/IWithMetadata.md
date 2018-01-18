<Type Name="IWithMetadata" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata">
  <TypeSignature Language="C#" Value="public interface IWithMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMetadata" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMetadata" />
  <TypeSignature Language="F#" Value="type IWithMetadata = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5dc6a-101">メタデータ リソースの変更を許可する更新プログラム。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-101">An update allowing metadata to be modified for the resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithMetadata (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithMetadata(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata.WithMetadata(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMetadata (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMetadata : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate" Usage="iWithMetadata.WithMetadata (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5dc6a-102">メタデータのキー。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-102">The key for the metadata.</span></span></param>
        <param name="value"><span data-ttu-id="5dc6a-103">メタデータの値です。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-103">The value for the metadata.</span></span></param>
        <summary>
            <span data-ttu-id="5dc6a-104">レコード セットをメタデータを追加します。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-104">Adds a metadata to the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5dc6a-105">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-105">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithoutMetadata (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithoutMetadata(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata.WithoutMetadata(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMetadata (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMetadata : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate" Usage="iWithMetadata.WithoutMetadata key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5dc6a-106">削除するメタデータのキー。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-106">The key of the metadata to remove.</span></span></param>
        <summary>
            <span data-ttu-id="5dc6a-107">レコード セットからメタデータを削除します。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-107">Removes a metadata from the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5dc6a-108">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="5dc6a-108">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>