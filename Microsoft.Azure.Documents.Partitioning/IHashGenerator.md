<Type Name="IHashGenerator" FullName="Microsoft.Azure.Documents.Partitioning.IHashGenerator">
  <TypeSignature Language="C#" Value="public interface IHashGenerator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHashGenerator" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHashGenerator" />
  <TypeSignature Language="F#" Value="type IHashGenerator = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for interfaces used with IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            によって使用される、インターフェイス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> Cosmos DB の Azure サービスで一貫したハッシュを使用してデータのパーティション分割します。
            </summary>
    <remarks>
      <para>
            IPartitionResolver で使用するインターフェイスのサポートは廃止されました。 使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。
            </para>
    </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  </Docs>
  <Members>
    <Member MemberName="ComputeHash">
      <MemberSignature Language="C#" Value="public byte[] ComputeHash (byte[] key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] ComputeHash(unsigned int8[] key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.IHashGenerator.ComputeHash(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ComputeHash (key As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member ComputeHash : byte[] -&gt; byte[]" Usage="iHashGenerator.ComputeHash key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key">バイトの配列によって表されるキー</param>
        <summary>
            新しい Azure Cosmos DB サービスで出力されるハッシュを表すバイト配列にバイトの配列をハッシュします。
            </summary>
        <returns>出力されるハッシュを表すバイト配列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>