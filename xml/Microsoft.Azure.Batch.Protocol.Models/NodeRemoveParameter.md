<Type Name="NodeRemoveParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter">
  <TypeSignature Language="C#" Value="public class NodeRemoveParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeRemoveParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeRemoveParameter" />
  <TypeSignature Language="F#" Value="type NodeRemoveParameter = class" />
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
            <span data-ttu-id="29e1a-101">削除するためのオプションは、プールからノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-101">Options for removing compute nodes from a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRemoveParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.#ctor" />
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
            <span data-ttu-id="29e1a-102">NodeRemoveParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-102">Initializes a new instance of the NodeRemoveParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRemoveParameter (System.Collections.Generic.IList&lt;string&gt; nodeList, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; nodeList, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.#ctor(System.Collections.Generic.IList{System.String},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeList As IList(Of String), Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter : System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter (nodeList, resizeTimeout, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeList"><span data-ttu-id="29e1a-103">指定したプールから削除するコンピューティング ノードの Id を含む一覧です。</span><span class="sxs-lookup"><span data-stu-id="29e1a-103">A list containing the IDs of the compute nodes to be removed from the specified pool.</span></span></param>
        <param name="resizeTimeout"><span data-ttu-id="29e1a-104">プールにコンピューティング ノードの削除のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="29e1a-104">The timeout for removal of compute nodes to the pool.</span></span></param>
        <param name="nodeDeallocationOption"><span data-ttu-id="29e1a-105">割り当て解除用に選択されている後のノードとその実行中のタスクの操作を決定します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-105">Determines what to do with a node and its running task(s) after it has been selected for deallocation.</span></span></param>
        <summary>
            <span data-ttu-id="29e1a-106">NodeRemoveParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-106">Initializes a new instance of the NodeRemoveParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeDeallocationOption" />
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
            <span data-ttu-id="29e1a-107">取得または設定の割り当て解除用に選択されている後のノードとその実行中のタスクの操作を決定します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-107">Gets or sets determines what to do with a node and its running task(s) after it has been selected for deallocation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="29e1a-108">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="29e1a-108">The default value is requeue.</span></span> <span data-ttu-id="29e1a-109">使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'</span><span class="sxs-lookup"><span data-stu-id="29e1a-109">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NodeList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NodeList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeList" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NodeList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29e1a-110">取得または指定したプールから削除するコンピューティング ノードの Id を含むリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-110">Gets or sets a list containing the IDs of the compute nodes to be removed from the specified pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.ResizeTimeout" />
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
            <span data-ttu-id="29e1a-111">取得またはプールにコンピューティング ノードの削除のためのタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-111">Gets or sets the timeout for removal of compute nodes to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="29e1a-112">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="29e1a-112">The default value is 15 minutes.</span></span> <span data-ttu-id="29e1a-113">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="29e1a-113">The minimum value is 5 minutes.</span></span> <span data-ttu-id="29e1a-114">5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="29e1a-114">If you specify a value less than 5 minutes, the Batch service returns an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeRemoveParameter.Validate " />
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
            <span data-ttu-id="29e1a-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="29e1a-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29e1a-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="29e1a-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>