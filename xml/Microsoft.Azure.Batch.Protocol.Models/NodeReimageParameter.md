<Type Name="NodeReimageParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter">
  <TypeSignature Language="C#" Value="public class NodeReimageParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeReimageParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeReimageParameter" />
  <TypeSignature Language="F#" Value="type NodeReimageParameter = class" />
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
            <span data-ttu-id="a5dfe-101">コンピューティング ノードを再イメージ化のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-101">Options for reimaging a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeReimageParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.#ctor" />
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
            <span data-ttu-id="a5dfe-102">NodeReimageParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-102">Initializes a new instance of the NodeReimageParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeReimageParameter (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nodeReimageOption As Nullable(Of ComputeNodeReimageOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter nodeReimageOption" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeReimageOption"><span data-ttu-id="a5dfe-103">コンピューティング ノードを再イメージ化する場合と実行中のタスクを行うには新機能です。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-103">When to reimage the compute node and what to do with currently running tasks.</span></span></param>
        <summary>
            <span data-ttu-id="a5dfe-104">NodeReimageParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-104">Initializes a new instance of the NodeReimageParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReimageOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; NodeReimageOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; NodeReimageOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.NodeReimageOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeReimageOption As Nullable(Of ComputeNodeReimageOption)" />
      <MemberSignature Language="F#" Value="member this.NodeReimageOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.NodeReimageOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeReimageOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5dfe-105">取得または計算ノードを再イメージ化する場合と、実行中のタスクの処理方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-105">Gets or sets when to reimage the compute node and what to do with currently running tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a5dfe-106">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="a5dfe-106">The default value is requeue.</span></span> <span data-ttu-id="a5dfe-107">使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'</span><span class="sxs-lookup"><span data-stu-id="a5dfe-107">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>