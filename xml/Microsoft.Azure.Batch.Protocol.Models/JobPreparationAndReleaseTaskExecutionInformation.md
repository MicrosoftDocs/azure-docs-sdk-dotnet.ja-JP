<Type Name="JobPreparationAndReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationAndReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobPreparationAndReleaseTaskExecutionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d8a63-101">コンピューティング ノードでジョブの準備とジョブのリリース タスクの状態。</span><span class="sxs-lookup"><span data-stu-id="d8a63-101">The status of the Job Preparation and Job Release tasks on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationAndReleaseTaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-102">JobPreparationAndReleaseTaskExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-102">Initializes a new instance of the JobPreparationAndReleaseTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationAndReleaseTaskExecutionInformation (string poolId = null, string nodeId = null, string nodeUrl = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation jobPreparationTaskExecutionInfo = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation jobReleaseTaskExecutionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, string nodeId, string nodeUrl, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation jobPreparationTaskExecutionInfo, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation jobReleaseTaskExecutionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional poolId As String = null, Optional nodeId As String = null, Optional nodeUrl As String = null, Optional jobPreparationTaskExecutionInfo As JobPreparationTaskExecutionInformation = null, Optional jobReleaseTaskExecutionInfo As JobReleaseTaskExecutionInformation = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation : string * string * string * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation (poolId, nodeId, nodeUrl, jobPreparationTaskExecutionInfo, jobReleaseTaskExecutionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeUrl" Type="System.String" />
        <Parameter Name="jobPreparationTaskExecutionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation" />
        <Parameter Name="jobReleaseTaskExecutionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="d8a63-103">このエントリが参照するコンピューティング ノードを含むプールの ID。</span><span class="sxs-lookup"><span data-stu-id="d8a63-103">The ID of the pool containing the compute node to which this entry refers.</span></span></param>
        <param name="nodeId"><span data-ttu-id="d8a63-104">このエントリが参照するコンピューティング ノードの ID。</span><span class="sxs-lookup"><span data-stu-id="d8a63-104">The ID of the compute node to which this entry refers.</span></span></param>
        <param name="nodeUrl"><span data-ttu-id="d8a63-105">このエントリが参照するコンピューティング ノードの URL です。</span><span class="sxs-lookup"><span data-stu-id="d8a63-105">The URL of the compute node to which this entry refers.</span></span></param>
        <param name="jobPreparationTaskExecutionInfo"><span data-ttu-id="d8a63-106">このコンピューティング ノードでジョブの準備タスクの実行状態に関する情報。</span><span class="sxs-lookup"><span data-stu-id="d8a63-106">Information about the execution status of the Job Preparation task on this compute node.</span></span></param>
        <param name="jobReleaseTaskExecutionInfo"><span data-ttu-id="d8a63-107">このコンピューティング ノードでジョブのリリース タスクの実行状態に関する情報。</span><span class="sxs-lookup"><span data-stu-id="d8a63-107">Information about the execution status of the Job Release task on this compute node.</span></span></param>
        <summary>
            <span data-ttu-id="d8a63-108">JobPreparationAndReleaseTaskExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-108">Initializes a new instance of the JobPreparationAndReleaseTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTaskExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTaskExecutionInfo As JobPreparationTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTaskExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTaskExecutionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-109">取得またはこのコンピューティング ノードでジョブの準備タスクの実行状態に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-109">Gets or sets information about the execution status of the Job Preparation task on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTaskExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTaskExecutionInfo As JobReleaseTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTaskExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTaskExecutionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-110">取得またはこのコンピューティング ノードでジョブのリリース タスクの実行状態に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-110">Gets or sets information about the execution status of the Job Release task on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d8a63-111">ジョブのリリース タスクがノードで実行する場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="d8a63-111">This property is set only if the Job Release task has run on the node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-112">取得または、このエントリが参照するコンピューティング ノードの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-112">Gets or sets the ID of the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUrl">
      <MemberSignature Language="C#" Value="public string NodeUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeUrl As String" />
      <MemberSignature Language="F#" Value="member this.NodeUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-113">取得または、このエントリが参照するコンピューティング ノードの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-113">Gets or sets the URL of the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-114">取得または、このエントリが参照するコンピューティング ノードを含むプールの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-114">Gets or sets the ID of the pool containing the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationAndReleaseTaskExecutionInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d8a63-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d8a63-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8a63-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8a63-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>