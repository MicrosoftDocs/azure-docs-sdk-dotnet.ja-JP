<Type Name="MappingLocation" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation">
  <TypeSignature Language="C#" Value="public enum MappingLocation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MappingLocation extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />
  <TypeSignature Language="VB.NET" Value="Public Enum MappingLocation" />
  <TypeSignature Language="F#" Value="type MappingLocation = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="1998c-101">異なるマッピングが存在する場所です。</span><span class="sxs-lookup"><span data-stu-id="1998c-101">Location where the different mappings exist.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MappingInShardMapAndShard">
      <MemberSignature Language="C#" Value="MappingInShardMapAndShard" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation MappingInShardMapAndShard = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardMapAndShard" />
      <MemberSignature Language="VB.NET" Value="MappingInShardMapAndShard" />
      <MemberSignature Language="F#" Value="MappingInShardMapAndShard = 2" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardMapAndShard" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1998c-102">グローバル ストアとシャードの両方で、存在をマッピングします。</span><span class="sxs-lookup"><span data-stu-id="1998c-102">Mapping present at both global store and shard.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingInShardMapOnly">
      <MemberSignature Language="C#" Value="MappingInShardMapOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation MappingInShardMapOnly = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardMapOnly" />
      <MemberSignature Language="VB.NET" Value="MappingInShardMapOnly" />
      <MemberSignature Language="F#" Value="MappingInShardMapOnly = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardMapOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1998c-103">マッピングがグローバル ストアには、存在しない、シャードにします。</span><span class="sxs-lookup"><span data-stu-id="1998c-103">Mapping is present in global store, but absent on the shard.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingInShardOnly">
      <MemberSignature Language="C#" Value="MappingInShardOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation MappingInShardOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardOnly" />
      <MemberSignature Language="VB.NET" Value="MappingInShardOnly" />
      <MemberSignature Language="F#" Value="MappingInShardOnly = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation.MappingInShardOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1998c-104">マッピングが存在しない場合、グローバル ストアが、シャードに存在します。</span><span class="sxs-lookup"><span data-stu-id="1998c-104">Mapping is absent in global store, but present on the shard.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>