<Type Name="JobSchedulePatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter">
  <TypeSignature Language="C#" Value="public class JobSchedulePatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSchedulePatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulePatchParameter" />
  <TypeSignature Language="F#" Value="type JobSchedulePatchParameter = class" />
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
            <span data-ttu-id="0b15d-101">ジョブのスケジュールに対する変更のセット。</span><span class="sxs-lookup"><span data-stu-id="0b15d-101">The set of changes to be made to a job schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulePatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.#ctor" />
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
            <span data-ttu-id="0b15d-102">JobSchedulePatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-102">Initializes a new instance of the JobSchedulePatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulePatchParameter (Microsoft.Azure.Batch.Protocol.Models.Schedule schedule = null, Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, class Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.Schedule,Microsoft.Azure.Batch.Protocol.Models.JobSpecification,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter : Microsoft.Azure.Batch.Protocol.Models.Schedule * Microsoft.Azure.Batch.Protocol.Models.JobSpecification * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter (schedule, jobSpecification, metadata)" />
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
        <param name="schedule"><span data-ttu-id="0b15d-103">これに基づいてジョブを作成するスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="0b15d-103">The schedule according to which jobs will be created.</span></span></param>
        <param name="jobSpecification"><span data-ttu-id="0b15d-104">このスケジュールを作成するジョブの詳細。</span><span class="sxs-lookup"><span data-stu-id="0b15d-104">The details of the jobs to be created on this schedule.</span></span></param>
        <param name="metadata"><span data-ttu-id="0b15d-105">メタデータとしてジョブのスケジュールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="0b15d-105">A list of name-value pairs associated with the job schedule as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="0b15d-106">JobSchedulePatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-106">Initializes a new instance of the JobSchedulePatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.JobSpecification" />
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
            <span data-ttu-id="0b15d-107">取得または、このスケジュールを作成するジョブの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-107">Gets or sets the details of the jobs to be created on this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0b15d-108">更新プログラムでは、更新が行われた後に開始されたジョブのみに影響します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-108">Updates affect only jobs that are started after the update has taken place.</span></span> <span data-ttu-id="0b15d-109">現在アクティブなジョブは、古い指定で続行します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-109">Any currently active job continues with the older specification.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Metadata" />
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
            <span data-ttu-id="0b15d-110">取得またはメタデータとしてジョブのスケジュールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-110">Gets or sets a list of name-value pairs associated with the job schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0b15d-111">指定しない場合、この要素のメタデータを既存は変更されません。</span><span class="sxs-lookup"><span data-stu-id="0b15d-111">If you do not specify this element, existing metadata is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Protocol.Models.Schedule with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Schedule" />
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
            <span data-ttu-id="0b15d-112">取得またはこれに基づいてジョブを作成するスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-112">Gets or sets the schedule according to which jobs will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0b15d-113">この要素を指定しない場合、既存のスケジュールはまま変更されません。</span><span class="sxs-lookup"><span data-stu-id="0b15d-113">If you do not specify this element, the existing schedule is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobSchedulePatchParameter.Validate " />
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
            <span data-ttu-id="0b15d-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0b15d-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0b15d-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0b15d-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>