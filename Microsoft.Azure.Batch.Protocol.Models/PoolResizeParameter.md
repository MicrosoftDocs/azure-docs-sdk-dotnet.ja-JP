<Type Name="PoolResizeParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter">
  <TypeSignature Language="C#" Value="public class PoolResizeParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolResizeParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolResizeParameter" />
  <TypeSignature Language="F#" Value="type PoolResizeParameter = class" />
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
            <span data-ttu-id="4c4aa-101">プールのサイズを変更するためのオプションです。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-101">Options for changing the size of a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolResizeParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.#ctor" />
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
            <span data-ttu-id="4c4aa-102">PoolResizeParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-102">Initializes a new instance of the PoolResizeParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolResizeParameter (Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional targetDedicatedNodes As Nullable(Of Integer) = null, Optional targetLowPriorityNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter (targetDedicatedNodes, targetLowPriorityNodes, resizeTimeout, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedNodes"><span data-ttu-id="4c4aa-103">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-103">The desired number of dedicated compute nodes in the pool.</span></span></param>
        <param name="targetLowPriorityNodes"><span data-ttu-id="4c4aa-104">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-104">The desired number of low-priority compute nodes in the pool.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="4c4aa-105">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-105">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span></param>
        <param name="nodeDeallocationOption"><span data-ttu-id="4c4aa-106">プールのサイズが減少している場合のノードとその実行中のタスクで処理を決定します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-106">Determines what to do with a node and its running task(s) if the pool size is decreasing.</span></span></param>
        <summary>
            <span data-ttu-id="4c4aa-107">PoolResizeParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-107">Initializes a new instance of the PoolResizeParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c4aa-108">取得または設定、プールのサイズが減少している場合のノードとその実行中のタスクで処理を決定します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-108">Gets or sets determines what to do with a node and its running task(s) if the pool size is decreasing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c4aa-109">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-109">The default value is requeue.</span></span> <span data-ttu-id="4c4aa-110">使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'</span><span class="sxs-lookup"><span data-stu-id="4c4aa-110">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c4aa-111">取得またはプールから割り当てるコンピューティング ノードの場合のタイムアウトをプールまたはコンピューティング ノードの削除に設定します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-111">Gets or sets the timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4c4aa-112">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-112">The default value is 15 minutes.</span></span> <span data-ttu-id="4c4aa-113">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-113">The minimum value is 5 minutes.</span></span> <span data-ttu-id="4c4aa-114">5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-114">If you specify a value less than 5 minutes, the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c4aa-115">取得またはプールの目的専用のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-115">Gets or sets the desired number of dedicated compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c4aa-116">取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4c4aa-116">Gets or sets the desired number of low-priority compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>