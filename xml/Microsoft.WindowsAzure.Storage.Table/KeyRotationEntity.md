<Type Name="KeyRotationEntity" FullName="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity">
  <TypeSignature Language="C#" Value="public class KeyRotationEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyRotationEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyRotationEntity" />
  <TypeSignature Language="F#" Value="type KeyRotationEntity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3f9a8-101">キーの交換に使用されるエンティティ</span><span class="sxs-lookup"><span data-stu-id="3f9a8-101">An entity used for key rotation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f9a8-102">取得またはエンティティの現在の ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-102">Gets or sets the entity's current ETag.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-103">エンティティの ETag を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-103">A string containing the ETag for the entity.</span></span></value>
        <remarks><span data-ttu-id="3f9a8-104">この値を設定 ' \*' を更新操作の一部としてエンティティを無条件で上書きします。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-104">Set this value to '\*' to blindly overwrite an entity as part of an update operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.EntityProperty this[string key] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Table.EntityProperty" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="3f9a8-105">プロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-105">A string containing the name of the property.</span></span></param>
        <summary>
            <span data-ttu-id="3f9a8-106">取得またはプロパティの名前を指定されたエンティティのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-106">Gets or sets the entity's property, given the name of the property.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-107"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-107">An <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f9a8-108">取得またはエンティティのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-108">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-109">エンティティのパーティション キー値を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-109">A string containing the partition key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IReadOnlyDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f9a8-110">プロパティ名でインデックス付けされた、テーブル エンティティのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-110">Gets the properties in the table entity, indexed by property name.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-111"><see cref="T:System.Collections.Generic.IDictionary`2" />エンティティのプロパティを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-111">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f9a8-112">取得またはエンティティの行キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-112">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-113">エンティティの行のキー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-113">A string containing the row key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3f9a8-114">取得またはエンティティのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-114">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="3f9a8-115">A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを表すです。</span><span class="sxs-lookup"><span data-stu-id="3f9a8-115">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>