<Type Name="RangeMappingUpdate" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate">
  <TypeSignature Language="C#" Value="public sealed class RangeMappingUpdate : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RangeMappingUpdate extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1&lt;valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RangeMappingUpdate&#xA;Inherits BaseMappingUpdate(Of MappingStatus)" />
  <TypeSignature Language="F#" Value="type RangeMappingUpdate = class&#xA;    inherit BaseMappingUpdate&lt;MappingStatus&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TStatus">Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            更新の間のマッピングを表す、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1" />値の<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />そのデータを格納します。 参照してください<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangeMappingUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しい範囲のマッピングの更新プログラム オブジェクトをインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBeingTakenOffline">
      <MemberSignature Language="C#" Value="protected override bool IsBeingTakenOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsBeingTakenOffline(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus originalStatus, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus updatedStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate.IsBeingTakenOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsBeingTakenOffline (originalStatus As MappingStatus, updatedStatus As MappingStatus) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBeingTakenOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus -&gt; bool" Usage="rangeMappingUpdate.IsBeingTakenOffline (originalStatus, updatedStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originalStatus" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />
        <Parameter Name="updatedStatus" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />
      </Parameters>
      <Docs>
        <param name="originalStatus">元の状態です。</param>
        <param name="updatedStatus">更新された状態です。</param>
        <summary>
            かどうか、現在のマッピングがオフラインになるかを検出します。
            </summary>
        <returns>マッピングがオフラインになる場合は、派生型で検出します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>