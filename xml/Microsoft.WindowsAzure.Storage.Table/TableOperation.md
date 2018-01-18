<Type Name="TableOperation" FullName="Microsoft.WindowsAzure.Storage.Table.TableOperation">
  <TypeSignature Language="C#" Value="public class TableOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class TableOperation" />
  <TypeSignature Language="F#" Value="type TableOperation = class" />
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
            <span data-ttu-id="5b4d1-101">1 つのテーブル操作を表します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-101">Represents a single table operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Delete (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Delete(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Delete(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Delete entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-102"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />テーブルから削除するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be deleted from the table.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-103">指定されたエンティティをテーブルから削除する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-103">Creates a new table operation that deletes the given entity from a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-104"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-104">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entity">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.ITableEntity Entity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.ITableEntity Entity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableOperation.Entity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Entity As ITableEntity" />
      <MemberSignature Language="F#" Value="member this.Entity : Microsoft.WindowsAzure.Storage.Table.ITableEntity" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Entity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.ITableEntity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4d1-105">有効になっているエンティティを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-105">Gets the entity that is being operated upon.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Insert (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Insert(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Insert(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Insert entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-106"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />テーブルに挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-106">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be inserted into the table.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-107">指定されたエンティティをテーブルに挿入する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-107">Creates a new table operation that inserts the given entity into a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-108"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-108">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Insert (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity, bool echoContent);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Insert(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity, bool echoContent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Insert(Microsoft.WindowsAzure.Storage.Table.ITableEntity,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity, echoContent As Boolean) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.WindowsAzure.Storage.Table.ITableEntity * bool -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Insert (entity, echoContent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
        <Parameter Name="echoContent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-109"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />テーブルに挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-109">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be inserted into the table.</span></span></param>
        <param name="echoContent">
          <span data-ttu-id="5b4d1-110"><c>true</c>場合はメッセージ ペイロードは挿入操作への応答で返される必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-110"><c>true</c> if the message payload should be returned in the response to the insert operation.</span></span> <span data-ttu-id="5b4d1-111"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-111"><c>false</c> otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-112">指定されたエンティティをテーブルに挿入する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-112">Creates a new table operation that inserts the given entity into a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-113"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-113">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrMerge">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation InsertOrMerge (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation InsertOrMerge(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.InsertOrMerge(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrMerge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrMerge : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.InsertOrMerge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-114"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />挿入またはマージするオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-114">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be inserted or merged.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-115">エンティティが存在しない場合、テーブルに指定されたエンティティを挿入する新しいテーブル操作を作成しますエンティティが存在する場合、その内容は、指定したエンティティにマージされます。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-115">Creates a new table operation that inserts the given entity into a table if the entity does not exist; if the entity does exist then its contents are merged with the provided entity.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-116"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-116">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation InsertOrReplace (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation InsertOrReplace(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.InsertOrReplace(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrReplace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrReplace : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.InsertOrReplace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-117"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />挿入または置換するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-117">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be inserted or replaced.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-118">エンティティが存在しない場合、テーブルに指定されたエンティティを挿入する新しいテーブル操作を作成しますエンティティが存在する場合、その内容は、指定したエンティティに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-118">Creates a new table operation that inserts the given entity into a table if the entity does not exist; if the entity does exist then its contents are replaced with the provided entity.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-119"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-119">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Merge (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Merge(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Merge(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Merge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-120"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />マージするオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-120">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be merged.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-121">テーブル内の既存のエンティティに特定のエンティティの内容と結合する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-121">Creates a new table operation that merges the contents of the given entity with the existing entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-122"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-122">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableOperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Table.TableOperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As TableOperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : Microsoft.WindowsAzure.Storage.Table.TableOperationType" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4d1-123">操作の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-123">Gets the type of operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Replace (Microsoft.WindowsAzure.Storage.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Replace(class Microsoft.WindowsAzure.Storage.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Replace(Microsoft.WindowsAzure.Storage.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Replace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Replace : Microsoft.WindowsAzure.Storage.Table.ITableEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Replace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-124"><see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />置き換えられるオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-124">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> object to be replaced.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-125">テーブル内の指定されたエンティティの内容を置き換える新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-125">Creates a new table operation that replaces the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-126"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-126">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve (partitionKey As String, rowkey As String, Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve (partitionKey, rowkey, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="5b4d1-127">取得するエンティティのパーティション キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-127">A string containing the partition key of the entity to be retrieved.</span></span></param>
        <param name="rowkey"><span data-ttu-id="5b4d1-128">取得するエンティティの行キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-128">A string containing the row key of the entity to be retrieved.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="5b4d1-129">投影の列名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-129">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-130">テーブル内の指定されたエンティティの内容を取得する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-130">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-131"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-131">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve&lt;TElement&gt; (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectColumns = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntity;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve&lt;(class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve``1(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TElement As ITableEntity) (partitionKey As String, rowkey As String, Optional selectColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity)" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve (partitionKey, rowkey, selectColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="5b4d1-132">取得するエンティティの型のクラスです。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-132">The class of type for the entity to retrieve.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="5b4d1-133">取得するエンティティのパーティション キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-133">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowkey"><span data-ttu-id="5b4d1-134">取得するエンティティの行キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-134">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="selectColumns"><span data-ttu-id="5b4d1-135">投影の列名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-135">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-136">テーブル内の指定されたエンティティの内容を取得する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-136">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-137"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-137">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve&lt;TResult&gt; (string partitionKey, string rowkey, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation Retrieve&lt;TResult&gt;(string partitionKey, string rowkey, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve``1(System.String,System.String,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TResult) (partitionKey As String, rowkey As String, resolver As EntityResolver(Of TResult), Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.Retrieve (partitionKey, rowkey, resolver, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="5b4d1-138">戻り値の型を指定した<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />に指定されたエンティティを解決します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-138">The return type which the specified <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> will resolve the given entity to.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="5b4d1-139">取得するエンティティのパーティション キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-139">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowkey"><span data-ttu-id="5b4d1-140">取得するエンティティの行キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-140">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="resolver"><span data-ttu-id="5b4d1-141"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果内の特定の型として取得するエンティティを射影する実装。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-141">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" /> implementation to project the entity to retrieve as a particular type in the result.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="5b4d1-142">投影の列名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-142">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-143">テーブル内の指定されたエンティティの内容を取得する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-143">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-144"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-144">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKey">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableOperation RotateEncryptionKey (Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableOperation RotateEncryptionKey(class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableOperation.RotateEncryptionKey(Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RotateEncryptionKey (entity As KeyRotationEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member RotateEncryptionKey : Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity -&gt; Microsoft.WindowsAzure.Storage.Table.TableOperation" Usage="Microsoft.WindowsAzure.Storage.Table.TableOperation.RotateEncryptionKey entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5b4d1-145"><see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />回転そのキーが存在するエンティティ。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-145">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" /> entity to have its key rotated.</span></span>  <span data-ttu-id="5b4d1-146">"ExecuteQueryForKeyRotation()"呼び出しへの呼び出しの出力にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-146">Must be the output of a call to an "ExecuteQueryForKeyRotation()" call.</span></span></param>
        <summary>
            <span data-ttu-id="5b4d1-147">指定されたエンティティ、テーブル内のコンテンツの暗号化キーを回転する新しいテーブル操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-147">Creates a new table operation that rotates the content encryption key of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4d1-148"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b4d1-148">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>