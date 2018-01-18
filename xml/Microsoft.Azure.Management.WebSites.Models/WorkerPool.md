<Type Name="WorkerPool" FullName="Microsoft.Azure.Management.WebSites.Models.WorkerPool">
  <TypeSignature Language="C#" Value="public class WorkerPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkerPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.WorkerPool" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkerPool" />
  <TypeSignature Language="F#" Value="type WorkerPool = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ead55-101">App Service 環境のワーカー プールです。</span><span class="sxs-lookup"><span data-stu-id="ead55-101">Worker pool of an App Service Environment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ead55-102">WorkerPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ead55-102">Initializes a new instance of the WorkerPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkerPool (Nullable&lt;int&gt; workerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode = null, string workerSize = null, Nullable&lt;int&gt; workerCount = null, System.Collections.Generic.IList&lt;string&gt; instanceNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; workerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode, string workerSize, valuetype System.Nullable`1&lt;int32&gt; workerCount, class System.Collections.Generic.IList`1&lt;string&gt; instanceNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WorkerPool.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions},System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional workerSizeId As Nullable(Of Integer) = null, Optional computeMode As Nullable(Of ComputeModeOptions) = null, Optional workerSize As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional instanceNames As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.WorkerPool : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.WorkerPool" Usage="new Microsoft.Azure.Management.WebSites.Models.WorkerPool (workerSizeId, computeMode, workerSize, workerCount, instanceNames)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="workerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computeMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;" />
        <Parameter Name="workerSize" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="instanceNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="workerSizeId"><span data-ttu-id="ead55-103">このワーカー プールを参照しているワーカー サイズ ID です。</span><span class="sxs-lookup"><span data-stu-id="ead55-103">Worker size ID for referencing this worker pool.</span></span></param>
        <param name="computeMode"><span data-ttu-id="ead55-104">共有または専用のアプリケーションをホストします。</span><span class="sxs-lookup"><span data-stu-id="ead55-104">Shared or dedicated app hosting.</span></span> <span data-ttu-id="ead55-105">使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="ead55-105">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span></param>
        <param name="workerSize"><span data-ttu-id="ead55-106">ワーカー プールのインスタンスの VM サイズです。</span><span class="sxs-lookup"><span data-stu-id="ead55-106">VM size of the worker pool instances.</span></span></param>
        <param name="workerCount"><span data-ttu-id="ead55-107">ワーカー プールのインスタンスの数。</span><span class="sxs-lookup"><span data-stu-id="ead55-107">Number of instances in the worker pool.</span></span></param>
        <param name="instanceNames"><span data-ttu-id="ead55-108">ワーカー プール (読み取り専用) のすべてのインスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="ead55-108">Names of all instances in the worker pool (read only).</span></span></param>
        <summary>
            <span data-ttu-id="ead55-109">WorkerPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ead55-109">Initializes a new instance of the WorkerPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPool.ComputeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeMode As Nullable(Of ComputeModeOptions)" />
      <MemberSignature Language="F#" Value="member this.ComputeMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPool.ComputeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead55-110">取得または共有または専用のアプリケーションのホスティングを設定します。</span><span class="sxs-lookup"><span data-stu-id="ead55-110">Gets or sets shared or dedicated app hosting.</span></span> <span data-ttu-id="ead55-111">使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="ead55-111">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPool.InstanceNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPool.InstanceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead55-112">(読み取り専用) ワーカー プールのすべてのインスタンスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ead55-112">Gets names of all instances in the worker pool (read only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead55-113">取得またはワーカー プールのインスタンスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ead55-113">Gets or sets number of instances in the worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSize">
      <MemberSignature Language="C#" Value="public string WorkerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSize As String" />
      <MemberSignature Language="F#" Value="member this.WorkerSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead55-114">取得またはワーカー プールのインスタンスの VM サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="ead55-114">Gets or sets VM size of the worker pool instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WorkerPool.WorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead55-115">取得または、このワーカー プールを参照しているワーカー サイズ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="ead55-115">Gets or sets worker size ID for referencing this worker pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>