<Type Name="TableQuery" FullName="Microsoft.Azure.CosmosDB.Table.TableQuery">
  <TypeSignature Language="C#" Value="public class TableQuery" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableQuery extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />
  <TypeSignature Language="VB.NET" Value="Public Class TableQuery" />
  <TypeSignature Language="F#" Value="type TableQuery = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1a73e-101">指定されたテーブルに対するクエリを表します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-101">Represents a query against a specified table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a73e-102">指定されたテーブルに対するクエリを表します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-102">Represents a query against a specified table.</span></span>
            </summary>
        <remarks><span data-ttu-id="1a73e-103">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスは、クエリが実行されるときに使用するクエリ パラメーターを集計します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-103">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance aggregates the query parameters to use when the query is executed.</span></span> <span data-ttu-id="1a73e-104">1 つ、 <c>executeQuery</c>または<c>executeQuerySegmented</c>メソッドの<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />クエリの実行に呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="1a73e-104">One of the <c>executeQuery</c> or <c>executeQuerySegmented</c> methods of <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> must be called to execute the query.</span></span> <span data-ttu-id="1a73e-105">パラメーターはエンコードされ、テーブルのクエリを実行すると、サーバーに渡されます。</span><span class="sxs-lookup"><span data-stu-id="1a73e-105">The parameters are encoded and passed to the server when the table query is executed.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CombineFilters">
      <MemberSignature Language="C#" Value="public static string CombineFilters (string filterA, string operatorString, string filterB);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CombineFilters(string filterA, string operatorString, string filterB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.CombineFilters(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CombineFilters (filterA As String, operatorString As String, filterB As String) As String" />
      <MemberSignature Language="F#" Value="static member CombineFilters : string * string * string -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.CombineFilters (filterA, operatorString, filterB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterA" Type="System.String" />
        <Parameter Name="operatorString" Type="System.String" />
        <Parameter Name="filterB" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterA"><span data-ttu-id="1a73e-106">最初の書式付きフィルター条件を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-106">A string containing the first formatted filter condition.</span></span></param>
        <param name="operatorString"><span data-ttu-id="1a73e-107">(AND、OR) を使用する演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-107">A string containing the operator to use (AND, OR).</span></span></param>
        <param name="filterB"><span data-ttu-id="1a73e-108">2 番目の書式付きフィルター条件を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-108">A string containing the second formatted filter condition.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-109">2 つのフィルター条件に指定された論理演算子を使用してフィルター条件を作成します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-109">Creates a filter condition using the specified logical operator on two filter conditions.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-110">結合されたフィルター式を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-110">A string containing the combined filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Copy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Copy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Copy" />
      <MemberSignature Language="VB.NET" Value="Public Function Copy () As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Copy : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Copy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a73e-111">この TableQuery オブジェクトのシャロー コピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-111">Make a shallow copy of this TableQuery object.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-112">新しく作成された簡易コピー。</span><span class="sxs-lookup"><span data-stu-id="1a73e-112">The newly created shallow copy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterString">
      <MemberSignature Language="C#" Value="public string FilterString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.FilterString" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterString As String" />
      <MemberSignature Language="F#" Value="member this.FilterString : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.FilterString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a73e-113">取得またはテーブルのクエリで使用するフィルター式を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-113">Gets or sets the filter expression to use in the table query.</span></span>
            </summary>
        <value><span data-ttu-id="1a73e-114">クエリで使用するフィルター式を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-114">A string containing the filter expression to use in the query.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterCondition">
      <MemberSignature Language="C#" Value="public static string GenerateFilterCondition (string propertyName, string operation, string givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterCondition(string propertyName, string operation, string givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterCondition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterCondition (propertyName As String, operation As String, givenValue As String) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterCondition : string * string * string -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterCondition (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-115">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-115">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-116">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-116">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-117">プロパティと比較する値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-117">A string containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-118">文字列値のプロパティ フィルター条件文字列を生成します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-118">Generates a property filter condition string for the string value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-119">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-119">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBinary">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBinary (string propertyName, string operation, byte[] givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBinary(string propertyName, string operation, unsigned int8[] givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBinary(System.String,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBinary (propertyName As String, operation As String, givenValue As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBinary : string * string * byte[] -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBinary (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-120">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-120">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-121">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-121">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-122">プロパティと比較する値を含むバイト配列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-122">A byte array containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-123">バイナリ値のプロパティ フィルター条件文字列を生成します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-123">Generates a property filter condition string for the binary value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-124">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-124">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForBool">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForBool (string propertyName, string operation, bool givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForBool(string propertyName, string operation, bool givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBool(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForBool (propertyName As String, operation As String, givenValue As Boolean) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForBool : string * string * bool -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForBool (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-125">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-125">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-126">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-126">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-127">A <c>bool</c>プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-127">A <c>bool</c> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-128">プロパティ フィルター条件文字列をブール値を生成します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-128">Generates a property filter condition string for the boolean value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-129">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-129">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDate">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDate (string propertyName, string operation, DateTimeOffset givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDate(string propertyName, string operation, valuetype System.DateTimeOffset givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDate(System.String,System.String,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDate (propertyName As String, operation As String, givenValue As DateTimeOffset) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDate : string * string * DateTimeOffset -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDate (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-130">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-130">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-131">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-131">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-132">A<see cref="T:System.DateTimeOffset" />プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-132">A <see cref="T:System.DateTimeOffset" /> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-133">プロパティ フィルター条件文字列を生成、<see cref="T:System.DateTimeOffset" />値。</span><span class="sxs-lookup"><span data-stu-id="1a73e-133">Generates a property filter condition string for the <see cref="T:System.DateTimeOffset" /> value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-134">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-134">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForDouble">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForDouble (string propertyName, string operation, double givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForDouble(string propertyName, string operation, float64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDouble(System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForDouble (propertyName As String, operation As String, givenValue As Double) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForDouble : string * string * double -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForDouble (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-135">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-135">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-136">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-136">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-137">A<see cref="T:System.Double" />プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-137">A <see cref="T:System.Double" /> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-138">プロパティ フィルター条件文字列を生成、<see cref="T:System.Double" />値。</span><span class="sxs-lookup"><span data-stu-id="1a73e-138">Generates a property filter condition string for the <see cref="T:System.Double" /> value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-139">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-139">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForGuid">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForGuid (string propertyName, string operation, Guid givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForGuid(string propertyName, string operation, valuetype System.Guid givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForGuid(System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForGuid (propertyName As String, operation As String, givenValue As Guid) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForGuid : string * string * Guid -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForGuid (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-140">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-140">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-141">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-141">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-142">A<see cref="T:System.Guid" />プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-142">A <see cref="T:System.Guid" /> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-143">プロパティ フィルター条件文字列を生成、<see cref="T:System.Guid" />値。</span><span class="sxs-lookup"><span data-stu-id="1a73e-143">Generates a property filter condition string for the <see cref="T:System.Guid" /> value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-144">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-144">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForInt">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForInt (string propertyName, string operation, int givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForInt(string propertyName, string operation, int32 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForInt(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForInt (propertyName As String, operation As String, givenValue As Integer) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForInt : string * string * int -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForInt (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-145">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-145">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-146">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-146">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-147"><see cref="T:System.Int32" />プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-147">An <see cref="T:System.Int32" /> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-148">プロパティ フィルター条件文字列を生成、<see cref="T:System.Int32" />値。</span><span class="sxs-lookup"><span data-stu-id="1a73e-148">Generates a property filter condition string for an <see cref="T:System.Int32" /> value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-149">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-149">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateFilterConditionForLong">
      <MemberSignature Language="C#" Value="public static string GenerateFilterConditionForLong (string propertyName, string operation, long givenValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateFilterConditionForLong(string propertyName, string operation, int64 givenValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForLong(System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateFilterConditionForLong (propertyName As String, operation As String, givenValue As Long) As String" />
      <MemberSignature Language="F#" Value="static member GenerateFilterConditionForLong : string * string * int64 -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.GenerateFilterConditionForLong (propertyName, operation, givenValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="givenValue" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="1a73e-150">比較するプロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-150">A string containing the name of the property to compare.</span></span></param>
        <param name="operation"><span data-ttu-id="1a73e-151">使用する比較演算子を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-151">A string containing the comparison operator to use.</span></span></param>
        <param name="givenValue"><span data-ttu-id="1a73e-152"><see cref="T:System.Int64" />プロパティと比較する値を含むです。</span><span class="sxs-lookup"><span data-stu-id="1a73e-152">An <see cref="T:System.Int64" /> containing the value to compare with the property.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-153">プロパティ フィルター条件文字列を生成、<see cref="T:System.Int64" />値。</span><span class="sxs-lookup"><span data-stu-id="1a73e-153">Generates a property filter condition string for an <see cref="T:System.Int64" /> value.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-154">書式付きフィルター条件を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-154">A string containing the formatted filter condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Project&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Project&lt;T&gt; (T entity, params string[] columns);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Project&lt;T&gt;(!!T entity, string[] columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Project``1(``0,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Project(Of T) (entity As T, ParamArray columns As String()) As T" />
      <MemberSignature Language="F#" Value="static member Project : 'T * string[] -&gt; 'T" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.Project (entity, columns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="entity" Type="T" />
        <Parameter Name="columns" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="1a73e-155">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="1a73e-155">The entity type of the query.</span></span></typeparam>
        <param name="entity"><span data-ttu-id="1a73e-156">プロジェクトからログオフするエンティティのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="1a73e-156">The entity instance to project off of.</span></span></param>
        <param name="columns"><span data-ttu-id="1a73e-157">クエリの実行時に返されるエンティティのプロパティの名前を含む文字列オブジェクトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="1a73e-157">A list of string objects containing the names of the entity properties to return when the query is executed.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-158">テーブルに対してクエリを実行時に返されるエンティティのプロパティの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-158">Specifies the names of the entity properties to return when the query is executed against the table.</span></span> 
            </summary>
        <returns><span data-ttu-id="1a73e-159">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンス エンティティのプロパティを返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-159">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the entity properties to return.</span></span></returns>
        <remarks><span data-ttu-id="1a73e-160">Project 句は、サーバーから返されるプロパティを制限するために使用、クエリでは省略可能です。</span><span class="sxs-lookup"><span data-stu-id="1a73e-160">The Project clause is optional on a query, used to limit the properties returned from the server.</span></span> <span data-ttu-id="1a73e-161">既定では、クエリは、エンティティから、すべてのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-161">By default, a query will return all properties from the entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Select (System.Collections.Generic.IList&lt;string&gt; columns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Select(class System.Collections.Generic.IList`1&lt;string&gt; columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Select(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select (columns As IList(Of String)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Select columns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="columns"><span data-ttu-id="1a73e-162">クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列オブジェクトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="1a73e-162">A list of string objects containing the property names of the table entity properties to return when the query is executed.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-163">テーブル クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を定義します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-163">Defines the property names of the table entity properties to return when the table query is executed.</span></span> 
            </summary>
        <returns><span data-ttu-id="1a73e-164">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンス テーブル エンティティのプロパティを返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-164">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the table entity properties to return.</span></span></returns>
        <remarks><span data-ttu-id="1a73e-165">Select 句は、サーバーから返されるテーブルのプロパティを制限するために使用、テーブルのクエリでは省略可能です。</span><span class="sxs-lookup"><span data-stu-id="1a73e-165">The select clause is optional on a table query, used to limit the table properties returned from the server.</span></span> <span data-ttu-id="1a73e-166">既定では、クエリは、テーブル エンティティから、すべてのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-166">By default, a query will return all properties from the table entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SelectColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SelectColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.SelectColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SelectColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.SelectColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a73e-167">取得またはテーブルのクエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-167">Gets or sets the property names of the table entity properties to return when the table query is executed.</span></span>
            </summary>
        <value><span data-ttu-id="1a73e-168">クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列のリスト。</span><span class="sxs-lookup"><span data-stu-id="1a73e-168">A list of strings containing the property names of the table entity properties to return when the query is executed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Take (Nullable&lt;int&gt; take);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Take(valuetype System.Nullable`1&lt;int32&gt; take) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Take(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (take As Nullable(Of Integer)) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Take : Nullable&lt;int&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Take take" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="take" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="take"><span data-ttu-id="1a73e-169">テーブル クエリで返されるエンティティの最大数。</span><span class="sxs-lookup"><span data-stu-id="1a73e-169">The maximum number of entities for the table query to return.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-170">クエリから返されるエンティティの数の上限の境界を定義します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-170">Defines the upper bound for the number of entities the query returns.</span></span>
            </summary>
        <returns><span data-ttu-id="1a73e-171">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスのエンティティの数を返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-171">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the number of entities to return.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TakeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TakeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery.TakeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TakeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TakeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery.TakeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a73e-172">取得またはテーブルのクエリが返すエンティティの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-172">Gets or sets the number of entities the table query will return.</span></span> 
            </summary>
        <value><span data-ttu-id="1a73e-173">テーブル クエリで返されるエンティティの最大数。</span><span class="sxs-lookup"><span data-stu-id="1a73e-173">The maximum number of entities for the table query to return.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery Where (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery Where(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery.Where(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (filter As String) As TableQuery" />
      <MemberSignature Language="F#" Value="member this.Where : string -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery" Usage="tableQuery.Where filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="1a73e-174">テーブル クエリに適用するフィルター式を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="1a73e-174">A string containing the filter expression to apply to the table query.</span></span></param>
        <summary>
            <span data-ttu-id="1a73e-175">テーブル クエリのフィルター式を定義します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-175">Defines a filter expression for the table query.</span></span> <span data-ttu-id="1a73e-176">指定したフィルター式を満たすエンティティのみが、クエリによって返されます。</span><span class="sxs-lookup"><span data-stu-id="1a73e-176">Only entities that satisfy the specified filter expression will be returned by the query.</span></span> 
            </summary>
        <returns><span data-ttu-id="1a73e-177">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスのフィルターでエンティティを返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="1a73e-177">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the filter on entities to return.</span></span></returns>
        <remarks><span data-ttu-id="1a73e-178">フィルター式の設定は省略可能です。既定では、テーブルのクエリでフィルター式が指定されていない場合、テーブル内のすべてのエンティティが返されます。</span><span class="sxs-lookup"><span data-stu-id="1a73e-178">Setting a filter expression is optional; by default, all entities in the table are returned if no filter expression is specified in the table query.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>