<Type Name="ShardMapManagerLoadPolicy" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy">
  <TypeSignature Language="C#" Value="public enum ShardMapManagerLoadPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShardMapManagerLoadPolicy extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Enum ShardMapManagerLoadPolicy" />
  <TypeSignature Language="F#" Value="type ShardMapManagerLoadPolicy = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="892fb-101">初期化に使用されるポリシーについて説明します<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />ストアからです。</span><span class="sxs-lookup"><span data-stu-id="892fb-101">Describes the policy used for initialization of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> from the store.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Eager">
      <MemberSignature Language="C#" Value="Eager" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy Eager = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Eager" />
      <MemberSignature Language="VB.NET" Value="Eager" />
      <MemberSignature Language="F#" Value="Eager = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Eager" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="892fb-102">すべてのシャード マップ、および対応するマッピングを迅速に取得用のキャッシュに読み込みます。</span><span class="sxs-lookup"><span data-stu-id="892fb-102">Load all shard maps and their corresponding mappings into the cache for fast retrieval.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Lazy">
      <MemberSignature Language="C#" Value="Lazy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy Lazy = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Lazy" />
      <MemberSignature Language="VB.NET" Value="Lazy" />
      <MemberSignature Language="F#" Value="Lazy = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy.Lazy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="892fb-103">すべてのシャード マップ、および対応するマッピングを必要に応じてとして読み込みます。</span><span class="sxs-lookup"><span data-stu-id="892fb-103">Load all shard maps and their corresponding mappings on as needed basis.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>