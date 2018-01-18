<Type Name="JobStage" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage">
  <TypeSignature Language="C#" Value="public class JobStage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStage" />
  <TypeSignature Language="F#" Value="type JobStage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0861a-101">ジョブの特定の段階の詳細。</span><span class="sxs-lookup"><span data-stu-id="0861a-101">The details about the specific stage of a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0861a-102">JobStage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0861a-102">Initializes a new instance of the JobStage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStage (Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus stageStatus, string message = null, string detail = null, string errorCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus stageStatus, string message, string detail, string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (stageStatus As JobStatus, Optional message As String = null, Optional detail As String = null, Optional errorCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage : Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage (stageStatus, message, detail, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stageStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="detail" Type="System.String" />
        <Parameter Name="errorCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="stageStatus"><span data-ttu-id="0861a-103">ステージの状態。</span><span class="sxs-lookup"><span data-stu-id="0861a-103">The stage status.</span></span> <span data-ttu-id="0861a-104">使用可能な値が含まれます: '実行中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="0861a-104">Possible values include: 'Running', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="message"><span data-ttu-id="0861a-105">ジョブのステージのメッセージ。</span><span class="sxs-lookup"><span data-stu-id="0861a-105">The message of the job stage.</span></span></param>
        <param name="detail"><span data-ttu-id="0861a-106">ステージの詳細。</span><span class="sxs-lookup"><span data-stu-id="0861a-106">The details of the stage.</span></span></param>
        <param name="errorCode"><span data-ttu-id="0861a-107">存在する場合、ステージのエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0861a-107">The error code of the stage if any.</span></span></param>
        <summary>
            <span data-ttu-id="0861a-108">JobStage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0861a-108">Initializes a new instance of the JobStage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public string Detail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.Detail" />
      <MemberSignature Language="VB.NET" Value="Public Property Detail As String" />
      <MemberSignature Language="F#" Value="member this.Detail : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0861a-109">取得またはステージの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="0861a-109">Gets or sets the details of the stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0861a-110">取得または存在する場合、ステージのエラー コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="0861a-110">Gets or sets the error code of the stage if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0861a-111">取得またはジョブのステージのメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="0861a-111">Gets or sets the message of the job stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus StageStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus StageStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.StageStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property StageStatus As JobStatus" />
      <MemberSignature Language="F#" Value="member this.StageStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.StageStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stageStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0861a-112">取得またはステージの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0861a-112">Gets or sets the stage status.</span></span> <span data-ttu-id="0861a-113">使用可能な値が含まれます: '実行中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="0861a-113">Possible values include: 'Running', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobStage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0861a-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0861a-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0861a-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0861a-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>