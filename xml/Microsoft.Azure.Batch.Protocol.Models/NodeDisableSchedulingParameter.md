<Type Name="NodeDisableSchedulingParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter">
  <TypeSignature Language="C#" Value="public class NodeDisableSchedulingParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeDisableSchedulingParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeDisableSchedulingParameter" />
  <TypeSignature Language="F#" Value="type NodeDisableSchedulingParameter = class" />
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
            <span data-ttu-id="c1423-101">コンピューティング ノード上のスケジュールを無効にするオプションです。</span><span class="sxs-lookup"><span data-stu-id="c1423-101">Options for disabling scheduling on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeDisableSchedulingParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter.#ctor" />
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
            <span data-ttu-id="c1423-102">NodeDisableSchedulingParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1423-102">Initializes a new instance of the NodeDisableSchedulingParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeDisableSchedulingParameter (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nodeDisableSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter nodeDisableSchedulingOption" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeDisableSchedulingOption"><span data-ttu-id="c1423-103">コンピューティング ノードでタスクのスケジュール設定を無効にするときにタスクを実行中の対処方法。</span><span class="sxs-lookup"><span data-stu-id="c1423-103">What to do with currently running tasks when disabling task scheduling on the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="c1423-104">NodeDisableSchedulingParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1423-104">Initializes a new instance of the NodeDisableSchedulingParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDisableSchedulingOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; NodeDisableSchedulingOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; NodeDisableSchedulingOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter.NodeDisableSchedulingOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDisableSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDisableSchedulingOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeDisableSchedulingParameter.NodeDisableSchedulingOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDisableSchedulingOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1423-105">取得または計算ノードでタスクのスケジュール設定を無効にするときにタスクを実行中の処理方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1423-105">Gets or sets what to do with currently running tasks when disabling task scheduling on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c1423-106">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="c1423-106">The default value is requeue.</span></span> <span data-ttu-id="c1423-107">使用可能な値が含まれます: 'キューに再登録'、'終了'、'taskCompletion'</span><span class="sxs-lookup"><span data-stu-id="c1423-107">Possible values include: 'requeue', 'terminate', 'taskCompletion'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>