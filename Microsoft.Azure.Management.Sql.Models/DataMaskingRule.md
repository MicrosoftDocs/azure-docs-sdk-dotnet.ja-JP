<Type Name="DataMaskingRule" FullName="Microsoft.Azure.Management.Sql.Models.DataMaskingRule">
  <TypeSignature Language="C#" Value="public class DataMaskingRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataMaskingRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
  <TypeSignature Language="VB.NET" Value="Public Class DataMaskingRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DataMaskingRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5110e-101">データベース データ マスキング ルールを表します。</span><span class="sxs-lookup"><span data-stu-id="5110e-101">Represents a database data masking rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5110e-102">DataMaskingRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5110e-102">Initializes a new instance of the DataMaskingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule (string schemaName, string tableName, string columnName, Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id = null, string name = null, string type = null, string dataMaskingRuleId = null, string aliasName = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState = null, string numberFrom = null, string numberTo = null, string prefixSize = null, string suffixSize = null, string replacementString = null, string location = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schemaName, string tableName, string columnName, valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id, string name, string type, string dataMaskingRuleId, string aliasName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState, string numberFrom, string numberTo, string prefixSize, string suffixSize, string replacementString, string location, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingFunction,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState},System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schemaName As String, tableName As String, columnName As String, maskingFunction As DataMaskingFunction, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional dataMaskingRuleId As String = null, Optional aliasName As String = null, Optional ruleState As Nullable(Of DataMaskingRuleState) = null, Optional numberFrom As String = null, Optional numberTo As String = null, Optional prefixSize As String = null, Optional suffixSize As String = null, Optional replacementString As String = null, Optional location As String = null, Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule : string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingFunction * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingRule" Usage="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule (schemaName, tableName, columnName, maskingFunction, id, name, type, dataMaskingRuleId, aliasName, ruleState, numberFrom, numberTo, prefixSize, suffixSize, replacementString, location, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="columnName" Type="System.String" />
        <Parameter Name="maskingFunction" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingFunction" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="dataMaskingRuleId" Type="System.String" />
        <Parameter Name="aliasName" Type="System.String" />
        <Parameter Name="ruleState" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;" />
        <Parameter Name="numberFrom" Type="System.String" />
        <Parameter Name="numberTo" Type="System.String" />
        <Parameter Name="prefixSize" Type="System.String" />
        <Parameter Name="suffixSize" Type="System.String" />
        <Parameter Name="replacementString" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schemaName"><span data-ttu-id="5110e-103">データ マスク ルールが適用されているスキーマ名です。</span><span class="sxs-lookup"><span data-stu-id="5110e-103">The schema name on which the data masking rule is applied.</span></span></param>
        <param name="tableName"><span data-ttu-id="5110e-104">データ マスク ルールが適用されているテーブル名です。</span><span class="sxs-lookup"><span data-stu-id="5110e-104">The table name on which the data masking rule is applied.</span></span></param>
        <param name="columnName"><span data-ttu-id="5110e-105">データ マスク ルールが適用されている列の名前。</span><span class="sxs-lookup"><span data-stu-id="5110e-105">The column name on which the data masking rule is applied.</span></span></param>
        <param name="maskingFunction"><span data-ttu-id="5110e-106">データ マスク ルールに使用されるマスキング関数。</span><span class="sxs-lookup"><span data-stu-id="5110e-106">The masking function that is used for the data masking rule.</span></span> <span data-ttu-id="5110e-107">使用可能な値が含まれます: 'Default'、'CCN'、'電子メール'、'Number'、'SSN'、'Text'</span><span class="sxs-lookup"><span data-stu-id="5110e-107">Possible values include: 'Default', 'CCN', 'Email', 'Number', 'SSN', 'Text'</span></span></param>
        <param name="id"><span data-ttu-id="5110e-108">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="5110e-108">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="5110e-109">リソース名。</span><span class="sxs-lookup"><span data-stu-id="5110e-109">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="5110e-110">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="5110e-110">Resource type.</span></span></param>
        <param name="dataMaskingRuleId"><span data-ttu-id="5110e-111">ルールの id。</span><span class="sxs-lookup"><span data-stu-id="5110e-111">The rule Id.</span></span></param>
        <param name="aliasName"><span data-ttu-id="5110e-112">エイリアスの名前です。</span><span class="sxs-lookup"><span data-stu-id="5110e-112">The alias name.</span></span> <span data-ttu-id="5110e-113">これはレガシ パラメーターであり、不要になった。</span><span class="sxs-lookup"><span data-stu-id="5110e-113">This is a legacy parameter and is no longer used.</span></span></param>
        <param name="ruleState"><span data-ttu-id="5110e-114">ルールの状態。</span><span class="sxs-lookup"><span data-stu-id="5110e-114">The rule state.</span></span> <span data-ttu-id="5110e-115">ルールを削除するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5110e-115">Used to delete a rule.</span></span> <span data-ttu-id="5110e-116">既存のルールを削除するには、schemaName、tableName、columnName maskingFunction、し無効として ruleState を指定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-116">To delete an existing rule, specify the schemaName, tableName, columnName, maskingFunction, and specify ruleState as disabled.</span></span>
            <span data-ttu-id="5110e-117">ただし、ルールが既に存在しない場合は、ルールは ruleState ruleState の指定された値に関係なく、有効に設定で作成されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-117">However, if the rule doesn't already exist, the rule will be created with ruleState set to enabled, regardless of the provided value of ruleState.</span></span> <span data-ttu-id="5110e-118">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="5110e-118">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="numberFrom"><span data-ttu-id="5110e-119">マスク ルールからのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="5110e-119">The numberFrom property of the masking rule.</span></span> <span data-ttu-id="5110e-120">MaskingFunction が数に設定されているかどうかに必要なそれ以外の場合このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-120">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span></param>
        <param name="numberTo"><span data-ttu-id="5110e-121">データ マスク ルールの 数のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="5110e-121">The numberTo property of the data masking rule.</span></span> <span data-ttu-id="5110e-122">MaskingFunction が数に設定されているかどうかに必要なそれ以外の場合このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-122">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span></param>
        <param name="prefixSize"><span data-ttu-id="5110e-123">MaskingFunction 設定されている場合、テキスト文字列の先頭のマスクされない文字数。</span><span class="sxs-lookup"><span data-stu-id="5110e-123">If maskingFunction is set to Text, the number of characters to show unmasked in the beginning of the string.</span></span> <span data-ttu-id="5110e-124">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-124">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="suffixSize"><span data-ttu-id="5110e-125">MaskingFunction 設定されている場合、テキスト文字列の末尾のマスクを表示する文字数。</span><span class="sxs-lookup"><span data-stu-id="5110e-125">If maskingFunction is set to Text, the number of characters to show unmasked at the end of the string.</span></span>
            <span data-ttu-id="5110e-126">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-126">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="replacementString"><span data-ttu-id="5110e-127">MaskingFunction は、文字列の非表示の部分をマスク用に使用する文字の文字列に設定されて場合います。</span><span class="sxs-lookup"><span data-stu-id="5110e-127">If maskingFunction is set to Text, the character to use for masking the unexposed part of the string.</span></span>
            <span data-ttu-id="5110e-128">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-128">Otherwise, this parameter will be ignored.</span></span></param>
        <param name="location"><span data-ttu-id="5110e-129">データ マスク ルールの場所です。</span><span class="sxs-lookup"><span data-stu-id="5110e-129">The location of the data masking rule.</span></span></param>
        <param name="kind"><span data-ttu-id="5110e-130">データ マスク ルールの種類。</span><span class="sxs-lookup"><span data-stu-id="5110e-130">The kind of Data Masking Rule.</span></span> <span data-ttu-id="5110e-131">Azure ポータルで使用されるメタデータ。</span><span class="sxs-lookup"><span data-stu-id="5110e-131">Metadata, used for Azure portal.</span></span></param>
        <summary>
            <span data-ttu-id="5110e-132">DataMaskingRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5110e-132">Initializes a new instance of the DataMaskingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasName">
      <MemberSignature Language="C#" Value="public string AliasName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberSignature Language="VB.NET" Value="Public Property AliasName As String" />
      <MemberSignature Language="F#" Value="member this.AliasName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.aliasName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-133">取得またはエイリアス名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-133">Gets or sets the alias name.</span></span> <span data-ttu-id="5110e-134">これはレガシ パラメーターであり、不要になった。</span><span class="sxs-lookup"><span data-stu-id="5110e-134">This is a legacy parameter and is no longer used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnName">
      <MemberSignature Language="C#" Value="public string ColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnName As String" />
      <MemberSignature Language="F#" Value="member this.ColumnName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columnName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-135">取得またはデータ マスク ルールが適用されている列名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-135">Gets or sets the column name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingRuleId">
      <MemberSignature Language="C#" Value="public string DataMaskingRuleId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataMaskingRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingRuleId As String" />
      <MemberSignature Language="F#" Value="member this.DataMaskingRuleId : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-136">ルール id を取得します。</span><span class="sxs-lookup"><span data-stu-id="5110e-136">Gets the rule Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-137">データ マスク ルールの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="5110e-137">Gets the kind of Data Masking Rule.</span></span> <span data-ttu-id="5110e-138">Azure ポータルで使用されるメタデータ。</span><span class="sxs-lookup"><span data-stu-id="5110e-138">Metadata, used for Azure portal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-139">データ マスク ルールの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="5110e-139">Gets the location of the data masking rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaskingFunction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberSignature Language="VB.NET" Value="Public Property MaskingFunction As DataMaskingFunction" />
      <MemberSignature Language="F#" Value="member this.MaskingFunction : Microsoft.Azure.Management.Sql.Models.DataMaskingFunction with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maskingFunction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingFunction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-140">取得またはマスキング関数は、データ マスク ルールの使用を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-140">Gets or sets the masking function that is used for the data masking rule.</span></span> <span data-ttu-id="5110e-141">使用可能な値が含まれます: 'Default'、'CCN'、'電子メール'、'Number'、'SSN'、'Text'</span><span class="sxs-lookup"><span data-stu-id="5110e-141">Possible values include: 'Default', 'CCN', 'Email', 'Number', 'SSN', 'Text'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberFrom">
      <MemberSignature Language="C#" Value="public string NumberFrom { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberFrom As String" />
      <MemberSignature Language="F#" Value="member this.NumberFrom : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberFrom")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-142">取得またはマスク ルールからプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-142">Gets or sets the numberFrom property of the masking rule.</span></span> <span data-ttu-id="5110e-143">MaskingFunction が数に設定されているかどうかに必要なそれ以外の場合このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-143">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberTo">
      <MemberSignature Language="C#" Value="public string NumberTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberTo As String" />
      <MemberSignature Language="F#" Value="member this.NumberTo : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-144">取得または、データ マスク ルールの 数のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-144">Gets or sets the numberTo property of the data masking rule.</span></span>
            <span data-ttu-id="5110e-145">MaskingFunction が数に設定されているかどうかに必要なそれ以外の場合このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-145">Required if maskingFunction is set to Number, otherwise this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefixSize">
      <MemberSignature Language="C#" Value="public string PrefixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrefixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefixSize As String" />
      <MemberSignature Language="F#" Value="member this.PrefixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.prefixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-146">取得または設定 maskingFunction がテキスト文字列の先頭のマスクされない文字数に設定されている場合。</span><span class="sxs-lookup"><span data-stu-id="5110e-146">Gets or sets if maskingFunction is set to Text, the number of characters to show unmasked in the beginning of the string.</span></span>
            <span data-ttu-id="5110e-147">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-147">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacementString">
      <MemberSignature Language="C#" Value="public string ReplacementString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplacementString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplacementString As String" />
      <MemberSignature Language="F#" Value="member this.ReplacementString : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replacementString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-148">取得または設定 maskingFunction が文字列の非表示の部分をマスク用に使用する文字の文字列に設定されている場合。</span><span class="sxs-lookup"><span data-stu-id="5110e-148">Gets or sets if maskingFunction is set to Text, the character to use for masking the unexposed part of the string.</span></span> <span data-ttu-id="5110e-149">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-149">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleState As Nullable(Of DataMaskingRuleState)" />
      <MemberSignature Language="F#" Value="member this.RuleState : Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-150">取得またはルールの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-150">Gets or sets the rule state.</span></span> <span data-ttu-id="5110e-151">ルールを削除するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5110e-151">Used to delete a rule.</span></span> <span data-ttu-id="5110e-152">既存のルールを削除するには、schemaName、tableName、columnName maskingFunction、し無効として ruleState を指定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-152">To delete an existing rule, specify the schemaName, tableName, columnName, maskingFunction, and specify ruleState as disabled.</span></span> <span data-ttu-id="5110e-153">ただし、ルールが既に存在しない場合は、ルールは ruleState ruleState の指定された値に関係なく、有効に設定で作成されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-153">However, if the rule doesn't already exist, the rule will be created with ruleState set to enabled, regardless of the provided value of ruleState.</span></span>
            <span data-ttu-id="5110e-154">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="5110e-154">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-155">取得またはデータ マスク ルールが適用されているスキーマ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-155">Gets or sets the schema name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuffixSize">
      <MemberSignature Language="C#" Value="public string SuffixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SuffixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property SuffixSize As String" />
      <MemberSignature Language="F#" Value="member this.SuffixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-156">取得または設定 maskingFunction がテキスト文字列の末尾のマスクを表示する文字数に設定されている場合。</span><span class="sxs-lookup"><span data-stu-id="5110e-156">Gets or sets if maskingFunction is set to Text, the number of characters to show unmasked at the end of the string.</span></span> <span data-ttu-id="5110e-157">それ以外の場合、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="5110e-157">Otherwise, this parameter will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5110e-158">取得またはデータ マスク ルールが適用されているテーブル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5110e-158">Gets or sets the table name on which the data masking rule is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataMaskingRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5110e-159">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5110e-159">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5110e-160">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5110e-160">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>