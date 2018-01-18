<Type Name="AutoPoolSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification">
  <TypeSignature Language="C#" Value="public class AutoPoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoPoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoPoolSpecification" />
  <TypeSignature Language="F#" Value="type AutoPoolSpecification = class" />
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
            <span data-ttu-id="0ffa9-101">一時 '自動プール' の特性を指定します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-101">Specifies characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="0ffa9-102">ジョブが送信されるときに、バッチ サービスはこの自動プールを作成します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-102">The Batch service will create this auto pool when the job is submitted.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor" />
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
            <span data-ttu-id="0ffa9-103">AutoPoolSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-103">Initializes a new instance of the AutoPoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification (Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix = null, Nullable&lt;bool&gt; keepAlive = null, Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix, valuetype System.Nullable`1&lt;bool&gt; keepAlive, class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.PoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification (poolLifetimeOption, autoPoolIdPrefix, keepAlive, pool)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolLifetimeOption" Type="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption" />
        <Parameter Name="autoPoolIdPrefix" Type="System.String" />
        <Parameter Name="keepAlive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolLifetimeOption"><span data-ttu-id="0ffa9-104">作成した自動プール、およびスケジュールで複数のジョブ プールに割り当てられたの最小有効期間。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-104">The minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span></param>
        <param name="autoPoolIdPrefix"><span data-ttu-id="0ffa9-105">プールが自動的に作成された一意の識別子を追加するプレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-105">A prefix to be added to the unique identifier when a pool is automatically created.</span></span></param>
        <param name="keepAlive"><span data-ttu-id="0ffa9-106">その有効期間の期限が切れた後は、自動プールを維持するかどうか。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-106">Whether to keep an auto pool alive after its lifetime expires.</span></span></param>
        <param name="pool"><span data-ttu-id="0ffa9-107">自動プールのプール仕様。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-107">The pool specification for the auto pool.</span></span></param>
        <summary>
            <span data-ttu-id="0ffa9-108">AutoPoolSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-108">Initializes a new instance of the AutoPoolSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolIdPrefix">
      <MemberSignature Language="C#" Value="public string AutoPoolIdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoPoolIdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolIdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AutoPoolIdPrefix : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolIdPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ffa9-109">取得またはプールが自動的に作成された一意の識別子を追加するプレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-109">Gets or sets a prefix to be added to the unique identifier when a pool is automatically created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0ffa9-110">バッチ サービスは、各自動プールの作成時に一意の識別子を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-110">The Batch service assigns each auto pool a unique identifier on creation.</span></span> <span data-ttu-id="0ffa9-111">さまざまな目的で作成されたプールを区別するために割り当てられている ID に、プレフィックスを追加するには、この要素を指定できます。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-111">To distinguish between pools created for different purposes, you can specify this element to add a prefix to the ID that is assigned.</span></span> <span data-ttu-id="0ffa9-112">プレフィックスは、最大 20 文字にすることができます。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-112">The prefix can be up to 20 characters long.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAlive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KeepAlive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KeepAlive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAlive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KeepAlive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepAlive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ffa9-113">取得またはその有効期間の期限が切れた後は、自動プールを維持するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-113">Gets or sets whether to keep an auto pool alive after its lifetime expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0ffa9-114">(PoolLifetimeOption 設定によって決まります)、その有効期間の期限が切れた後に、Batch サービスが、プールを削除 false の場合、つまり、ジョブまたはジョブがスケジュール設定を完了します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-114">If false, the Batch service deletes the pool once its lifetime (as determined by the poolLifetimeOption setting) expires; that is, when the job or job schedule completes.</span></span> <span data-ttu-id="0ffa9-115">True の場合、バッチ サービスは削除されません、プールに自動的に。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-115">If true, the Batch service does not delete the pool automatically.</span></span> <span data-ttu-id="0ffa9-116">このオプションを使用して作成された自動プールを削除するユーザーの責任です。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-116">It is up to the user to delete auto pools created with this option.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberSignature Language="VB.NET" Value="Public Property Pool As PoolSpecification" />
      <MemberSignature Language="F#" Value="member this.Pool : Microsoft.Azure.Batch.Protocol.Models.PoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ffa9-117">取得または自動プールのプール仕様を設定します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-117">Gets or sets the pool specification for the auto pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolLifetimeOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolLifetimeOption As PoolLifetimeOption" />
      <MemberSignature Language="F#" Value="member this.PoolLifetimeOption : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolLifetimeOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ffa9-118">取得または作成した自動プール、およびスケジュールで複数のジョブ プールに割り当てられたの最小有効期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-118">Gets or sets the minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0ffa9-119">使用可能な値が含まれます: 'jobSchedule'、'ジョブ'</span><span class="sxs-lookup"><span data-stu-id="0ffa9-119">Possible values include: 'jobSchedule', 'job'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoPoolSpecification.Validate " />
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
            <span data-ttu-id="0ffa9-120">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0ffa9-121">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0ffa9-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>