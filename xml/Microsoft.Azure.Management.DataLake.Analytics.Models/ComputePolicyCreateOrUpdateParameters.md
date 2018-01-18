<Type Name="ComputePolicyCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputePolicyCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type ComputePolicyCreateOrUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="71a48-101">新しいコンピューティング ポリシーを作成するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a48-101">The parameters used to create a new compute policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71a48-102">ComputePolicyCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71a48-102">Initializes a new instance of the ComputePolicyCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyCreateOrUpdateParameters (Guid objectId, string objectType, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid objectId, string objectType, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.#ctor(System.Guid,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (objectId As Guid, objectType As String, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters : Guid * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters (objectId, objectType, maxDegreeOfParallelismPerJob, minPriorityPerJob)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.Guid" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="71a48-103">ポリシーを作成するエンティティの AAD のオブジェクト識別子です。</span><span class="sxs-lookup"><span data-stu-id="71a48-103">The AAD object identifier for the entity to create a policy for.</span></span></param>
        <param name="objectType"><span data-ttu-id="71a48-104">AAD のオブジェクトの種類、オブジェクト識別子を参照します。</span><span class="sxs-lookup"><span data-stu-id="71a48-104">The type of AAD object the object identifier refers to.</span></span> <span data-ttu-id="71a48-105">使用可能な値が含まれます: 'User'、'Group'、'ServicePrincipal'</span><span class="sxs-lookup"><span data-stu-id="71a48-105">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span></param>
        <param name="maxDegreeOfParallelismPerJob"><span data-ttu-id="71a48-106">ジョブあたりの並列処理の最大限度このユーザーは、ジョブの送信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="71a48-106">The maximum degree of parallelism per job this user can use to submit jobs.</span></span> <span data-ttu-id="71a48-107">このプロパティは、ジョブのプロパティ、またはその両方あたり最小優先度を渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a48-107">This property, the min priority per job property, or both must be passed.</span></span></param>
        <param name="minPriorityPerJob"><span data-ttu-id="71a48-108">ジョブごとの最低の優先順位このユーザーは、ジョブの送信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="71a48-108">The minimum priority per job this user can use to submit jobs.</span></span> <span data-ttu-id="71a48-109">このプロパティは、ジョブのプロパティ、またはその両方あたりの並列処理の最大限度を渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a48-109">This property, the max degree of parallelism per job property, or both must be passed.</span></span></param>
        <summary>
            <span data-ttu-id="71a48-110">ComputePolicyCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71a48-110">Initializes a new instance of the ComputePolicyCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71a48-111">取得またはこのユーザー ジョブの送信に使用できるジョブあたりの並列処理の最大限度を設定します。</span><span class="sxs-lookup"><span data-stu-id="71a48-111">Gets or sets the maximum degree of parallelism per job this user can use to submit jobs.</span></span> <span data-ttu-id="71a48-112">このプロパティは、ジョブのプロパティ、またはその両方あたり最小優先度を渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a48-112">This property, the min priority per job property, or both must be passed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71a48-113">取得またはこのユーザー ジョブの送信に使用できるジョブごとの最低の優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="71a48-113">Gets or sets the minimum priority per job this user can use to submit jobs.</span></span> <span data-ttu-id="71a48-114">このプロパティは、ジョブのプロパティ、またはその両方あたりの並列処理の最大限度を渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a48-114">This property, the max degree of parallelism per job property, or both must be passed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public Guid ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As Guid" />
      <MemberSignature Language="F#" Value="member this.ObjectId : Guid with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71a48-115">取得またはポリシーを作成するエンティティの AAD のオブジェクト識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="71a48-115">Gets or sets the AAD object identifier for the entity to create a policy for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71a48-116">取得またはオブジェクトの識別子が参照する AAD のオブジェクトの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="71a48-116">Gets or sets the type of AAD object the object identifier refers to.</span></span> <span data-ttu-id="71a48-117">使用可能な値が含まれます: 'User'、'Group'、'ServicePrincipal'</span><span class="sxs-lookup"><span data-stu-id="71a48-117">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computePolicyCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71a48-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="71a48-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="71a48-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a48-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>