<Type Name="JobResource" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource">
  <TypeSignature Language="C#" Value="public class JobResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobResource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource" />
  <TypeSignature Language="VB.NET" Value="Public Class JobResource" />
  <TypeSignature Language="F#" Value="type JobResource = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bcad6-101">Data Lake Analytics ジョブのリソース。</span><span class="sxs-lookup"><span data-stu-id="bcad6-101">The Data Lake Analytics job resources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bcad6-102">JobResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bcad6-102">Initializes a new instance of the JobResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResource (string name = null, string resourcePath = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string resourcePath, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional resourcePath As String = null, Optional type As Nullable(Of JobResourceType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource : string * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource (name, resourcePath, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="resourcePath" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bcad6-103">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="bcad6-103">the name of the resource.</span></span></param>
        <param name="resourcePath"><span data-ttu-id="bcad6-104">リソースへのパス。</span><span class="sxs-lookup"><span data-stu-id="bcad6-104">the path to the resource.</span></span></param>
        <param name="type"><span data-ttu-id="bcad6-105">ジョブ リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="bcad6-105">the job resource type.</span></span> <span data-ttu-id="bcad6-106">使用可能な値が含まれます: 'VertexResource'、'JobManagerResource'、'StatisticsResource'、'VertexResourceInUserFolder'、'JobManagerResourceInUserFolder'、'StatisticsResourceInUserFolder'</span><span class="sxs-lookup"><span data-stu-id="bcad6-106">Possible values include: 'VertexResource', 'JobManagerResource', 'StatisticsResource', 'VertexResourceInUserFolder', 'JobManagerResourceInUserFolder', 'StatisticsResourceInUserFolder'</span></span></param>
        <summary>
            <span data-ttu-id="bcad6-107">JobResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bcad6-107">Initializes a new instance of the JobResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcad6-108">取得またはリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bcad6-108">Gets or sets the name of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourcePath">
      <MemberSignature Language="C#" Value="public string ResourcePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourcePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.ResourcePath" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourcePath As String" />
      <MemberSignature Language="F#" Value="member this.ResourcePath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.ResourcePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourcePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcad6-109">取得またはリソースへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="bcad6-109">Gets or sets the path to the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of JobResourceType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcad6-110">取得または、ジョブ リソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="bcad6-110">Gets or sets the job resource type.</span></span> <span data-ttu-id="bcad6-111">使用可能な値が含まれます: 'VertexResource'、'JobManagerResource'、'StatisticsResource'、'VertexResourceInUserFolder'、'JobManagerResourceInUserFolder'、'StatisticsResourceInUserFolder'</span><span class="sxs-lookup"><span data-stu-id="bcad6-111">Possible values include: 'VertexResource', 'JobManagerResource', 'StatisticsResource', 'VertexResourceInUserFolder', 'JobManagerResourceInUserFolder', 'StatisticsResourceInUserFolder'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>