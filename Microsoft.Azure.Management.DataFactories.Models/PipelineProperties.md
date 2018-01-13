<Type Name="PipelineProperties" FullName="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties">
  <TypeSignature Language="C#" Value="public class PipelineProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineProperties" />
  <TypeSignature Language="F#" Value="type PipelineProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ecf84-101">パイプラインのプロパティ</span><span class="sxs-lookup"><span data-stu-id="ecf84-101">Pipeline properties</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt; activities);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Activity&gt; activities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactories.Models.Activity})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activities As IList(Of Activity))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.PipelineProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt; -&gt; Microsoft.Azure.Management.DataFactories.Models.PipelineProperties" Usage="new Microsoft.Azure.Management.DataFactories.Models.PipelineProperties activities" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt;" />
      </Parameters>
      <Docs>
        <param name="activities">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt; Activities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Activity&gt; Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Property Activities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.Activities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Activities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-102">パイプラインに属しているアクティビティ。</span><span class="sxs-lookup"><span data-stu-id="ecf84-102">Activities that belong to the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; Datasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasets As IList(Of Dataset)" />
      <MemberSignature Language="F#" Value="member this.Datasets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ecf84-103">Optional.</span></span> <span data-ttu-id="ecf84-104">パイプラインで定義されたアクティビティで使用されるデータセットの一覧。</span><span class="sxs-lookup"><span data-stu-id="ecf84-104">List of datasets to be used by activities defined in the pipeline.</span></span> <span data-ttu-id="ecf84-105">このパイプラインに固有であり、datafactory 内で定義されていないデータセットを定義するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="ecf84-105">This can be used to define datasets that are specific to this pipeline and not defined within the datafactory.</span></span> <span data-ttu-id="ecf84-106">このパイプライン内で定義されているデータセットは、このパイプラインでのみ使用でき、共有することはできません。</span><span class="sxs-lookup"><span data-stu-id="ecf84-106">Datasets defined within this pipeline can only be used by this pipeline and cannot be shared.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-107">パイプラインの説明です。</span><span class="sxs-lookup"><span data-stu-id="ecf84-107">Pipeline description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.End : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-108">パイプラインの終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="ecf84-108">The end time of the pipeline.</span></span> <span data-ttu-id="ecf84-109">開始および終了時間は両方とも空です。 パイプラインを作成するには両方が必要、パイプラインの有効期間の設定値を 1 つことはできません値を持ち、他のでない場合。</span><span class="sxs-lookup"><span data-stu-id="ecf84-109">The start and end time can both be empty to create a pipeline; they must both have values to set an active period for the pipeline and one cannot have a value if the other does not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-110">パイプライン要求の処理のエラーです。</span><span class="sxs-lookup"><span data-stu-id="ecf84-110">Error in processing pipeline request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpirationTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ecf84-111">Optional.</span></span> <span data-ttu-id="ecf84-112">パイプラインの作成後に、パイプラインが有効であり、プロビジョニングされた状態が維持される必要がある時間。</span><span class="sxs-lookup"><span data-stu-id="ecf84-112">Duration of time after creation for which the pipeline is valid and should remain provisioned.</span></span> <span data-ttu-id="ecf84-113">到達すると、有効期限があるない、アクティブな場合、または保留中の実行に、パイプラインを自動的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="ecf84-113">The pipeline will be deleted automatically once it reaches the expiration time if it does not have any active or pending runs</span></span>        
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubName">
      <MemberSignature Language="C#" Value="public string HubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.HubName" />
      <MemberSignature Language="VB.NET" Value="Public Property HubName As String" />
      <MemberSignature Language="F#" Value="member this.HubName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.HubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-114">このパイプラインが属しているハブの名前。</span><span class="sxs-lookup"><span data-stu-id="ecf84-114">The name of the Hub that this pipeline belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPaused">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPaused { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPaused" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.IsPaused" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPaused As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPaused : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.IsPaused" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-115">パイプラインの状態です。</span><span class="sxs-lookup"><span data-stu-id="ecf84-115">The status of the pipeline.</span></span> <span data-ttu-id="ecf84-116">ブール値が設定されている場合、パイプラインは一時停止を true にします。</span><span class="sxs-lookup"><span data-stu-id="ecf84-116">Pipeline is paused when boolean is set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineMode">
      <MemberSignature Language="C#" Value="public string PipelineMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.PipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineMode As String" />
      <MemberSignature Language="F#" Value="member this.PipelineMode : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.PipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ecf84-117">Optional.</span></span> <span data-ttu-id="ecf84-118">パイプラインのスケジューリングのメソッドが実行されます。</span><span class="sxs-lookup"><span data-stu-id="ecf84-118">The method of scheduling runs for the pipeline.</span></span> <span data-ttu-id="ecf84-119">いずれかを指定する必要があります<see cref="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.PipelineMode" />です。</span><span class="sxs-lookup"><span data-stu-id="ecf84-119">Must be one of <see cref="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.PipelineMode" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-120">パイプラインのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="ecf84-120">The provisioning state of the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo RuntimeInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeInfo As PipelineRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecf84-121">パイプラインのランタイム情報。</span><span class="sxs-lookup"><span data-stu-id="ecf84-121">Pipeline runtime information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Start : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PipelineProperties.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>                                                         
            <span data-ttu-id="ecf84-122">パイプラインの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="ecf84-122">The start time of the pipeline.</span></span> <span data-ttu-id="ecf84-123">開始および終了時間</span><span class="sxs-lookup"><span data-stu-id="ecf84-123">The start and end time</span></span>  
            <span data-ttu-id="ecf84-124">どちらも空にすることです。 パイプラインを作成するには両方が必要、パイプラインの有効期間を設定する値と 1 つ持つことはできません、</span><span class="sxs-lookup"><span data-stu-id="ecf84-124">can both be empty to create a pipeline; they must both have values to set an active period for the pipeline and one cannot have a</span></span>    
            <span data-ttu-id="ecf84-125">もう一方にない場合の値。</span><span class="sxs-lookup"><span data-stu-id="ecf84-125">value if the other does not.</span></span>                                      
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>