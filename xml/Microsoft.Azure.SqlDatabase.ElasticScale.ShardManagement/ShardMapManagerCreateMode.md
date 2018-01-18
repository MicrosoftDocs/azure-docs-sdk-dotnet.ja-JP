<Type Name="ShardMapManagerCreateMode" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode">
  <TypeSignature Language="C#" Value="public enum ShardMapManagerCreateMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShardMapManagerCreateMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ShardMapManagerCreateMode" />
  <TypeSignature Language="F#" Value="type ShardMapManagerCreateMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="6249f-101">Shard map manager ストレージ表現の作成オプションをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="6249f-101">Describes the creation options for shard map manager storage representation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="KeepExisting">
      <MemberSignature Language="C#" Value="KeepExisting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode KeepExisting = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" />
      <MemberSignature Language="VB.NET" Value="KeepExisting" />
      <MemberSignature Language="F#" Value="KeepExisting = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6249f-102">場合は、シャードのマップ マネージャー データ構造は、ストアに含まれています、このメソッドは例外を生成します。</span><span class="sxs-lookup"><span data-stu-id="6249f-102">If the shard map manager data structures are already present in the store, then this method will raise exception.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ReplaceExisting">
      <MemberSignature Language="C#" Value="ReplaceExisting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode ReplaceExisting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.ReplaceExisting" />
      <MemberSignature Language="VB.NET" Value="ReplaceExisting" />
      <MemberSignature Language="F#" Value="ReplaceExisting = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.ReplaceExisting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6249f-103">シャードのマップ マネージャーのデータ構造がストアに存在、する場合、このメソッド上書きされます。</span><span class="sxs-lookup"><span data-stu-id="6249f-103">If the shard map manager data structures are already present in the store, then this method will overwrite them.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>