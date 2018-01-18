<Type Name="JobsListByResourceGroupOptions" FullName="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions">
  <TypeSignature Language="C#" Value="public class JobsListByResourceGroupOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobsListByResourceGroupOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class JobsListByResourceGroupOptions" />
  <TypeSignature Language="F#" Value="type JobsListByResourceGroupOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1def1-101">ListByResourceGroup 操作に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1def1-101">Additional parameters for ListByResourceGroup operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListByResourceGroupOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1def1-102">JobsListByResourceGroupOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1def1-102">Initializes a new instance of the JobsListByResourceGroupOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListByResourceGroupOptions (string filter = null, string select = null, Nullable&lt;int&gt; maxResults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filter, string select, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filter As String = null, Optional select As String = null, Optional maxResults As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions (filter, select, maxResults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="1def1-103">OData $filter 句では.</span><span class="sxs-lookup"><span data-stu-id="1def1-103">An OData $filter clause..</span></span> <span data-ttu-id="1def1-104">GET respnose で返される結果をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1def1-104">Used to filter results that are returned in the GET respnose.</span></span></param>
        <param name="select"><span data-ttu-id="1def1-105">OData の $select 句の場合です。</span><span class="sxs-lookup"><span data-stu-id="1def1-105">An OData $select clause.</span></span> <span data-ttu-id="1def1-106">GET respnose に返されるプロパティを選択するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1def1-106">Used to select the properties to be returned in the GET respnose.</span></span></param>
        <param name="maxResults"><span data-ttu-id="1def1-107">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="1def1-107">The maximum number of items to return in the response.</span></span> <span data-ttu-id="1def1-108">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="1def1-108">A maximum of 1000 files can be returned.</span></span></param>
        <summary>
            <span data-ttu-id="1def1-109">JobsListByResourceGroupOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1def1-109">Initializes a new instance of the JobsListByResourceGroupOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1def1-110">取得または OData $filter 句を設定.</span><span class="sxs-lookup"><span data-stu-id="1def1-110">Gets or sets an OData $filter clause..</span></span> <span data-ttu-id="1def1-111">GET respnose で返される結果をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1def1-111">Used to filter results that are returned in the GET respnose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1def1-112">取得または応答で返されるアイテムの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="1def1-112">Gets or sets the maximum number of items to return in the response.</span></span>
            <span data-ttu-id="1def1-113">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="1def1-113">A maximum of 1000 files can be returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions.Select" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1def1-114">取得または OData $select 句を設定します。</span><span class="sxs-lookup"><span data-stu-id="1def1-114">Gets or sets an OData $select clause.</span></span> <span data-ttu-id="1def1-115">GET respnose に返されるプロパティを選択するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1def1-115">Used to select the properties to be returned in the GET respnose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>