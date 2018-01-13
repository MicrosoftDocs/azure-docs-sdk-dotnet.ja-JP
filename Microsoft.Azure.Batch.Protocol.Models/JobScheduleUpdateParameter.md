<Type Name="JobScheduleUpdateParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter">
  <TypeSignature Language="C#" Value="public class JobScheduleUpdateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleUpdateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleUpdateParameter" />
  <TypeSignature Language="F#" Value="type JobScheduleUpdateParameter = class" />
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
            <span data-ttu-id="9f6b6-101">ジョブのスケジュールに対する変更のセット。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-101">The set of changes to be made to a job schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleUpdateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.#ctor" />
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
            <span data-ttu-id="9f6b6-102">JobScheduleUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-102">Initializes a new instance of the JobScheduleUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleUpdateParameter (Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, class Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.Schedule,Microsoft.Azure.Batch.Protocol.Models.JobSpecification,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter : Microsoft.Azure.Batch.Protocol.Models.Schedule * Microsoft.Azure.Batch.Protocol.Models.JobSpecification * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter (schedule, jobSpecification, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Protocol.Models.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="schedule"><span data-ttu-id="9f6b6-103">これに基づいてジョブを作成するスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-103">The schedule according to which jobs will be created.</span></span></param>
        <param name="jobSpecification"><span data-ttu-id="9f6b6-104">このスケジュールを作成するジョブの詳細です。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-104">Details of the jobs to be created on this schedule.</span></span></param>
        <param name="metadata"><span data-ttu-id="9f6b6-105">メタデータとしてジョブのスケジュールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-105">A list of name-value pairs associated with the job schedule as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="9f6b6-106">JobScheduleUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-106">Initializes a new instance of the JobScheduleUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.JobSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6b6-107">取得または、このスケジュールを作成するジョブの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-107">Gets or sets details of the jobs to be created on this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9f6b6-108">更新プログラムでは、更新が行われた後に開始されたジョブのみに影響します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-108">Updates affect only jobs that are started after the update has taken place.</span></span> <span data-ttu-id="9f6b6-109">現在アクティブなジョブは、古い指定で続行します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-109">Any currently active job continues with the older specification.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6b6-110">取得またはメタデータとしてジョブのスケジュールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-110">Gets or sets a list of name-value pairs associated with the job schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9f6b6-111">この要素を指定しないと、一覧が空の既定値になります実際には、既存のメタデータが削除されます。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-111">If you do not specify this element, it takes the default value of an empty list; in effect, any existing metadata is deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Protocol.Models.Schedule with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Schedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6b6-112">取得またはこれに基づいてジョブを作成するスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-112">Gets or sets the schedule according to which jobs will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9f6b6-113">この要素を指定しない場合と同じであるに渡す場合、既定のスケジュール: すぐに実行するのには、1 つのジョブがスケジュールされています。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-113">If you do not specify this element, it is equivalent to passing the default schedule: that is, a single job scheduled to run immediately.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobScheduleUpdateParameter.Validate " />
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
            <span data-ttu-id="9f6b6-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9f6b6-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9f6b6-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>