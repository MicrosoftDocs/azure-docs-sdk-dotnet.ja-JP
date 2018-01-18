<Type Name="RecommendedIndexInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner">
  <TypeSignature Language="C#" Value="public class RecommendedIndexInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedIndexInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedIndexInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RecommendedIndexInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3facf-101">インデックスを推奨 Azure SQL データベースを表します。</span><span class="sxs-lookup"><span data-stu-id="3facf-101">Represents an Azure SQL Database recommended index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedIndexInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3facf-102">RecommendedIndexInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3facf-102">Initializes a new instance of the RecommendedIndexInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedIndexInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt; action = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt; state = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt; indexType = null, string schema = null, string table = null, System.Collections.Generic.IList&lt;string&gt; columns = null, System.Collections.Generic.IList&lt;string&gt; includedColumns = null, string indexScript = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; estimatedImpact = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; reportedImpact = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt; action, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt; indexType, string schema, string table, class System.Collections.Generic.IList`1&lt;string&gt; columns, class System.Collections.Generic.IList`1&lt;string&gt; includedColumns, string indexScript, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; estimatedImpact, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; reportedImpact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional action As Nullable(Of RecommendedIndexActions) = null, Optional state As Nullable(Of RecommendedIndexStates) = null, Optional created As Nullable(Of DateTime) = null, Optional lastModified As Nullable(Of DateTime) = null, Optional indexType As Nullable(Of RecommendedIndexTypes) = null, Optional schema As String = null, Optional table As String = null, Optional columns As IList(Of String) = null, Optional includedColumns As IList(Of String) = null, Optional indexScript As String = null, Optional estimatedImpact As IList(Of OperationImpact) = null, Optional reportedImpact As IList(Of OperationImpact) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner (location, id, name, type, tags, action, state, created, lastModified, indexType, schema, table, columns, includedColumns, indexScript, estimatedImpact, reportedImpact)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="action" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="indexType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt;" />
        <Parameter Name="schema" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="includedColumns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="indexScript" Type="System.String" />
        <Parameter Name="estimatedImpact" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;" />
        <Parameter Name="reportedImpact" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="action"><span data-ttu-id="3facf-103">提案されたインデックスの操作です。</span><span class="sxs-lookup"><span data-stu-id="3facf-103">The proposed index action.</span></span> <span data-ttu-id="3facf-104">欠落インデックスを作成、未使用のインデックスを削除したり、パフォーマンスを向上させるために既存のインデックスを再構築できます。</span><span class="sxs-lookup"><span data-stu-id="3facf-104">You can create a missing index, drop an unused index, or rebuild an existing index to improve its performance.</span></span> <span data-ttu-id="3facf-105">使用可能な値は、'Create'、'Drop'、'Rebuild' です。</span><span class="sxs-lookup"><span data-stu-id="3facf-105">Possible values are 'Create', 'Drop', 'Rebuild'.</span></span> <span data-ttu-id="3facf-106">使用可能な値が含まれます 'Create'、'Drop'、'Rebuild'。</span><span class="sxs-lookup"><span data-stu-id="3facf-106">Possible values include: 'Create', 'Drop', 'Rebuild'</span></span></param>
        <param name="state"><span data-ttu-id="3facf-107">推奨設定の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="3facf-107">The current recommendation state.</span></span> <span data-ttu-id="3facf-108">現在のオプションが: 'Active'、'保留中'、'実行'、'確認'、' 保留 Revert'、'元に戻す'、'元に戻された'、'無視'、'有効期限が切れて'、'ブロック'、'Success' です。</span><span class="sxs-lookup"><span data-stu-id="3facf-108">Current options are: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'.</span></span> <span data-ttu-id="3facf-109">使用可能な値が含まれます: 'Active'、'保留中'、'実行'、'確認'、' 保留 Revert'、'元に戻す'、'元に戻された'、'無視'、'有効期限が切れて'、'ブロック'、'成功'</span><span class="sxs-lookup"><span data-stu-id="3facf-109">Possible values include: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'</span></span></param>
        <param name="created"><span data-ttu-id="3facf-110">UTC datetime このリソースが作成された日時を表示 (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="3facf-110">The UTC datetime showing when this resource was created (ISO8601 format).</span></span></param>
        <param name="lastModified"><span data-ttu-id="3facf-111">UTC datetime されたこのリソースの最終変更日 (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="3facf-111">The UTC datetime of when was this resource last changed (ISO8601 format).</span></span></param>
        <param name="indexType"><span data-ttu-id="3facf-112">インデックス (クラスター化、非クラスター化インデックス、列ストア、クラスター化列ストア) の型。</span><span class="sxs-lookup"><span data-stu-id="3facf-112">The type of index (CLUSTERED, NONCLUSTERED, COLUMNSTORE, CLUSTERED COLUMNSTORE).</span></span> <span data-ttu-id="3facf-113">使用可能な値が含まれます: 'クラスター化された'、'非クラスター化'、'COLUMNSTORE'、' クラスター化列ストア '</span><span class="sxs-lookup"><span data-stu-id="3facf-113">Possible values include: 'CLUSTERED', 'NONCLUSTERED', 'COLUMNSTORE', 'CLUSTERED COLUMNSTORE'</span></span></param>
        <param name="schema"><span data-ttu-id="3facf-114">経由でインデックスを作成するテーブルが存在するスキーマ</span><span class="sxs-lookup"><span data-stu-id="3facf-114">The schema where table to build index over resides</span></span></param>
        <param name="table"><span data-ttu-id="3facf-115">インデックスを構築するためのテーブルです。</span><span class="sxs-lookup"><span data-stu-id="3facf-115">The table on which to build index.</span></span></param>
        <param name="columns"><span data-ttu-id="3facf-116">列インデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="3facf-116">Columns over which to build index</span></span></param>
        <param name="includedColumns"><span data-ttu-id="3facf-117">インデックスに含まれる列名の一覧</span><span class="sxs-lookup"><span data-stu-id="3facf-117">The list of column names to be included in the index</span></span></param>
        <param name="indexScript"><span data-ttu-id="3facf-118">フル ビルド インデックス スクリプト</span><span class="sxs-lookup"><span data-stu-id="3facf-118">The full build index script</span></span></param>
        <param name="estimatedImpact"><span data-ttu-id="3facf-119">推定影響は、インデックスの操作をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3facf-119">The estimated impact of doing recommended index action.</span></span></param>
        <param name="reportedImpact"><span data-ttu-id="3facf-120">インデックスの操作が完了した後に報告される値。</span><span class="sxs-lookup"><span data-stu-id="3facf-120">The values reported after index action is complete.</span></span></param>
        <summary>
            <span data-ttu-id="3facf-121">RecommendedIndexInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3facf-121">Initializes a new instance of the RecommendedIndexInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt; Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt; Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As Nullable(Of RecommendedIndexActions)" />
      <MemberSignature Language="F#" Value="member this.Action : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexActions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-122">指定したインデックスの操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-122">Gets the proposed index action.</span></span> <span data-ttu-id="3facf-123">欠落インデックスを作成、未使用のインデックスを削除したり、パフォーマンスを向上させるために既存のインデックスを再構築できます。</span><span class="sxs-lookup"><span data-stu-id="3facf-123">You can create a missing index, drop an unused index, or rebuild an existing index to improve its performance.</span></span> <span data-ttu-id="3facf-124">使用可能な値は、'Create'、'Drop'、'Rebuild' です。</span><span class="sxs-lookup"><span data-stu-id="3facf-124">Possible values are 'Create', 'Drop', 'Rebuild'.</span></span>
            <span data-ttu-id="3facf-125">使用可能な値が含まれます 'Create'、'Drop'、'Rebuild'。</span><span class="sxs-lookup"><span data-stu-id="3facf-125">Possible values include: 'Create', 'Drop', 'Rebuild'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Columns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Columns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Columns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-126">インデックスを作成する列を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-126">Gets columns over which to build index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-127">このリソース (ISO8601 形式) が作成されたときを示す UTC 日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-127">Gets the UTC datetime showing when this resource was created (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedImpact">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; EstimatedImpact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; EstimatedImpact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.EstimatedImpact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EstimatedImpact As IList(Of OperationImpact)" />
      <MemberSignature Language="F#" Value="member this.EstimatedImpact : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.EstimatedImpact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.estimatedImpact")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-128">これが推奨されるインデックス操作の推定の影響を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-128">Gets the estimated impact of doing recommended index action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IncludedColumns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IncludedColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IncludedColumns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludedColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IncludedColumns : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IncludedColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includedColumns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-129">インデックスに含まれる列名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-129">Gets the list of column names to be included in the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexScript">
      <MemberSignature Language="C#" Value="public string IndexScript { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IndexScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IndexScript" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexScript As String" />
      <MemberSignature Language="F#" Value="member this.IndexScript : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IndexScript" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.indexScript")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-130">フル ビルド インデックス スクリプトを取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-130">Gets the full build index script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt; IndexType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt; IndexType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IndexType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexType As Nullable(Of RecommendedIndexTypes)" />
      <MemberSignature Language="F#" Value="member this.IndexType : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.IndexType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.indexType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-131">(クラスター化、非クラスター化インデックス、列ストア、クラスター化列ストア) のインデックスの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-131">Gets the type of index (CLUSTERED, NONCLUSTERED, COLUMNSTORE, CLUSTERED COLUMNSTORE).</span></span> <span data-ttu-id="3facf-132">使用可能な値が含まれます: 'クラスター化された'、'非クラスター化'、'COLUMNSTORE'、' クラスター化列ストア '</span><span class="sxs-lookup"><span data-stu-id="3facf-132">Possible values include: 'CLUSTERED', 'NONCLUSTERED', 'COLUMNSTORE', 'CLUSTERED COLUMNSTORE'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-133">リソース最後変更 (ISO8601 の形式) を時の UTC 日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-133">Gets the UTC datetime of when was this resource last changed (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportedImpact">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; ReportedImpact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt; ReportedImpact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.ReportedImpact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReportedImpact As IList(Of OperationImpact)" />
      <MemberSignature Language="F#" Value="member this.ReportedImpact : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.ReportedImpact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reportedImpact")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.OperationImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-134">インデックスの操作が完了した後に報告される値を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-134">Gets the values reported after index action is complete.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public string Schema { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Schema" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Schema As String" />
      <MemberSignature Language="F#" Value="member this.Schema : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-135">経由でインデックスを作成するテーブルが存在するスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-135">Gets the schema where table to build index over resides</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of RecommendedIndexStates)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexStates&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-136">現在の推奨事項の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-136">Gets the current recommendation state.</span></span> <span data-ttu-id="3facf-137">現在のオプションが: 'Active'、'保留中'、'実行'、'確認'、' 保留 Revert'、'元に戻す'、'元に戻された'、'無視'、'有効期限が切れて'、'ブロック'、'Success' です。</span><span class="sxs-lookup"><span data-stu-id="3facf-137">Current options are: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'.</span></span> <span data-ttu-id="3facf-138">使用可能な値が含まれます: 'Active'、'保留中'、'実行'、'確認'、' 保留 Revert'、'元に戻す'、'元に戻された'、'無視'、'有効期限が切れて'、'ブロック'、'成功'</span><span class="sxs-lookup"><span data-stu-id="3facf-138">Possible values include: 'Active', 'Pending', 'Executing', 'Verifying', 'Pending Revert', 'Reverting', 'Reverted', 'Ignored', 'Expired', 'Blocked', 'Success'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3facf-139">インデックスを構築するためのテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3facf-139">Gets the table on which to build index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>