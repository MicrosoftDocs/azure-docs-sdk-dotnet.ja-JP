<Type Name="ComputePolicy" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy">
  <TypeSignature Language="C#" Value="public class ComputePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputePolicy" />
  <TypeSignature Language="F#" Value="type ComputePolicy = class" />
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
            <span data-ttu-id="c47c3-101">新しいコンピューティング ポリシーを作成するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c47c3-101">The parameters used to create a new compute policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c47c3-102">ComputePolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-102">Initializes a new instance of the ComputePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicy (string name = null, Nullable&lt;Guid&gt; objectId = null, string objectType = null, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; objectId, string objectType, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.#ctor(System.String,System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional objectId As Nullable(Of Guid) = null, Optional objectType As String = null, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy : string * Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy (name, objectId, objectType, maxDegreeOfParallelismPerJob, minPriorityPerJob)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="objectId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c47c3-103">コンピューティングのポリシーの名前</span><span class="sxs-lookup"><span data-stu-id="c47c3-103">The name of the compute policy</span></span></param>
        <param name="objectId"><span data-ttu-id="c47c3-104">ポリシーを作成するエンティティの AAD のオブジェクト識別子です。</span><span class="sxs-lookup"><span data-stu-id="c47c3-104">The AAD object identifier for the entity to create a policy for.</span></span></param>
        <param name="objectType"><span data-ttu-id="c47c3-105">AAD のオブジェクトの種類、オブジェクト識別子を参照します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-105">The type of AAD object the object identifier refers to.</span></span> <span data-ttu-id="c47c3-106">使用可能な値が含まれます: 'User'、'Group'、'ServicePrincipal'</span><span class="sxs-lookup"><span data-stu-id="c47c3-106">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span></param>
        <param name="maxDegreeOfParallelismPerJob"><span data-ttu-id="c47c3-107">ジョブあたりの並列処理の最大限度このユーザーは、ジョブの送信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="c47c3-107">The maximum degree of parallelism per job this user can use to submit jobs.</span></span></param>
        <param name="minPriorityPerJob"><span data-ttu-id="c47c3-108">ジョブごとの最低の優先順位このユーザーは、ジョブの送信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="c47c3-108">The minimum priority per job this user can use to submit jobs.</span></span></param>
        <summary>
            <span data-ttu-id="c47c3-109">ComputePolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-109">Initializes a new instance of the ComputePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.MaxDegreeOfParallelismPerJob" />
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
            <span data-ttu-id="c47c3-110">取得またはこのユーザー ジョブの送信に使用できるジョブあたりの並列処理の最大限度を設定します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-110">Gets or sets the maximum degree of parallelism per job this user can use to submit jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.MinPriorityPerJob" />
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
            <span data-ttu-id="c47c3-111">取得またはこのユーザー ジョブの送信に使用できるジョブごとの最低の優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-111">Gets or sets the minimum priority per job this user can use to submit jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.Name" />
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
            <span data-ttu-id="c47c3-112">コンピューティングのポリシーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-112">Gets the name of the compute policy</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ObjectId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObjectId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ObjectId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.ObjectId" />
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
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c47c3-113">ポリシーを作成するエンティティの AAD のオブジェクト識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-113">Gets the AAD object identifier for the entity to create a policy for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.ObjectType" />
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
            <span data-ttu-id="c47c3-114">オブジェクト識別子が参照する AAD のオブジェクトの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-114">Gets the type of AAD object the object identifier refers to.</span></span>
            <span data-ttu-id="c47c3-115">使用可能な値が含まれます: 'User'、'Group'、'ServicePrincipal'</span><span class="sxs-lookup"><span data-stu-id="c47c3-115">Possible values include: 'User', 'Group', 'ServicePrincipal'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computePolicy.Validate " />
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
            <span data-ttu-id="c47c3-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c47c3-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c47c3-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c47c3-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>