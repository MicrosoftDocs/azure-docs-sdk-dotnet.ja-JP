<Type Name="BaseMappingUpdate&lt;TStatus&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;TStatus&gt;">
  <TypeSignature Language="C#" Value="public abstract class BaseMappingUpdate&lt;TStatus&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit BaseMappingUpdate`1&lt;TStatus&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class BaseMappingUpdate(Of TStatus)" />
  <TypeSignature Language="F#" Value="type BaseMappingUpdate&lt;'Status&gt; = class&#xA;    interface IMappingUpdate&lt;'Status&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TStatus" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TStatus"><span data-ttu-id="7066b-101">[状態] フィールドの型。</span><span class="sxs-lookup"><span data-stu-id="7066b-101">Type of status field.</span></span></typeparam>
    <summary>
            <span data-ttu-id="7066b-102">シャードにシャードレットをマッピングする更新プログラムの基本クラス。</span><span class="sxs-lookup"><span data-stu-id="7066b-102">Base class for updates to mappings from shardlets to shards.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected BaseMappingUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBeingTakenOffline">
      <MemberSignature Language="C#" Value="protected abstract bool IsBeingTakenOffline (TStatus originalStatus, TStatus updatedStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsBeingTakenOffline(!TStatus originalStatus, !TStatus updatedStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1.IsBeingTakenOffline(`0,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function IsBeingTakenOffline (originalStatus As TStatus, updatedStatus As TStatus) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsBeingTakenOffline : 'Status * 'Status -&gt; bool" Usage="baseMappingUpdate.IsBeingTakenOffline (originalStatus, updatedStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originalStatus" Type="TStatus" />
        <Parameter Name="updatedStatus" Type="TStatus" />
      </Parameters>
      <Docs>
        <param name="originalStatus"><span data-ttu-id="7066b-103">元の状態です。</span><span class="sxs-lookup"><span data-stu-id="7066b-103">Original status.</span></span></param>
        <param name="updatedStatus"><span data-ttu-id="7066b-104">更新された状態です。</span><span class="sxs-lookup"><span data-stu-id="7066b-104">Updated status.</span></span></param>
        <summary>
            <span data-ttu-id="7066b-105">かどうか、現在のマッピングがオフラインになるかを検出します。</span><span class="sxs-lookup"><span data-stu-id="7066b-105">Detects if the current mapping is being taken offline.</span></span>
            </summary>
        <returns><span data-ttu-id="7066b-106">マッピングがオフラインになる場合は、派生型で検出します。</span><span class="sxs-lookup"><span data-stu-id="7066b-106">Detects in the derived types if the mapping is being taken offline.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1.Shard" />
      <MemberSignature Language="VB.NET" Value="Public Property Shard As Shard" />
      <MemberSignature Language="F#" Value="member this.Shard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;'Status&gt;.Shard" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7066b-107">取得またはシャード プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="7066b-107">Gets or sets the Shard property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public TStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate`1.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As TStatus" />
      <MemberSignature Language="F#" Value="member this.Status : 'Status with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.BaseMappingUpdate&lt;'Status&gt;.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7066b-108">取得または Status プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="7066b-108">Gets or sets the Status property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>