<Type Name="ClustersListOptions" FullName="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions">
  <TypeSignature Language="C#" Value="public class ClustersListOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClustersListOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ClustersListOptions" />
  <TypeSignature Language="F#" Value="type ClustersListOptions = class" />
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
            <span data-ttu-id="b895e-101">List 操作に対して追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b895e-101">Additional parameters for List operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClustersListOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b895e-102">ClustersListOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b895e-102">Initializes a new instance of the ClustersListOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClustersListOptions (string filter = null, string select = null, Nullable&lt;int&gt; maxResults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filter, string select, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filter As String = null, Optional select As String = null, Optional maxResults As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" Usage="new Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions (filter, select, maxResults)" />
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
        <param name="filter"><span data-ttu-id="b895e-103">OData $filter 句では.</span><span class="sxs-lookup"><span data-stu-id="b895e-103">An OData $filter clause..</span></span> <span data-ttu-id="b895e-104">GET respnose で返される結果をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b895e-104">Used to filter results that are returned in the GET respnose.</span></span></param>
        <param name="select"><span data-ttu-id="b895e-105">OData の $select 句の場合です。</span><span class="sxs-lookup"><span data-stu-id="b895e-105">An OData $select clause.</span></span> <span data-ttu-id="b895e-106">GET respnose に返されるプロパティを選択するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b895e-106">Used to select the properties to be returned in the GET respnose.</span></span></param>
        <param name="maxResults"><span data-ttu-id="b895e-107">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="b895e-107">The maximum number of items to return in the response.</span></span> <span data-ttu-id="b895e-108">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="b895e-108">A maximum of 1000 files can be returned.</span></span></param>
        <summary>
            <span data-ttu-id="b895e-109">ClustersListOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b895e-109">Initializes a new instance of the ClustersListOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.Filter" />
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
            <span data-ttu-id="b895e-110">取得または OData $filter 句を設定.</span><span class="sxs-lookup"><span data-stu-id="b895e-110">Gets or sets an OData $filter clause..</span></span> <span data-ttu-id="b895e-111">GET respnose で返される結果をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b895e-111">Used to filter results that are returned in the GET respnose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.MaxResults" />
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
            <span data-ttu-id="b895e-112">取得または応答で返されるアイテムの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b895e-112">Gets or sets the maximum number of items to return in the response.</span></span>
            <span data-ttu-id="b895e-113">最大で 1000 のファイルが返されます。</span><span class="sxs-lookup"><span data-stu-id="b895e-113">A maximum of 1000 files can be returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions.Select" />
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
            <span data-ttu-id="b895e-114">取得または OData $select 句を設定します。</span><span class="sxs-lookup"><span data-stu-id="b895e-114">Gets or sets an OData $select clause.</span></span> <span data-ttu-id="b895e-115">GET respnose に返されるプロパティを選択するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b895e-115">Used to select the properties to be returned in the GET respnose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>