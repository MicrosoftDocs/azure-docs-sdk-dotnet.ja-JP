<Type Name="ManualScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings">
  <TypeSignature Language="C#" Value="public class ManualScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManualScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ManualScaleSettings" />
  <TypeSignature Language="F#" Value="type ManualScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="384eb-101">クラスターの設定を手動でのスケーリングします。</span><span class="sxs-lookup"><span data-stu-id="384eb-101">Manual scale settings for the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="384eb-102">ManualScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="384eb-102">Initializes a new instance of the ManualScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings (int targetNodeCount, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 targetNodeCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor(System.Int32,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.DeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetNodeCount As Integer, Optional nodeDeallocationOption As Nullable(Of DeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings : int * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings (targetNodeCount, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetNodeCount" Type="System.Int32" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="targetNodeCount"><span data-ttu-id="384eb-103">クラスター内の計算ノードの目的の数。</span><span class="sxs-lookup"><span data-stu-id="384eb-103">The desired number of compute nodes in the Cluster.</span></span></param>
        <param name="nodeDeallocationOption"><span data-ttu-id="384eb-104">クラスター サイズが減少している場合は、コンピューティング ノードで実行されているジョブの処理方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="384eb-104">Determines what to do with the job(s) running on compute node if the Cluster size is decreasing.</span></span></param>
        <summary>
            <span data-ttu-id="384eb-105">ManualScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="384eb-105">Initializes a new instance of the ManualScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of DeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="384eb-106">取得または設定は、クラスターのサイズが減少している場合は、コンピューティング ノードで実行されているジョブの処理方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="384eb-106">Gets or sets determines what to do with the job(s) running on compute node if the Cluster size is decreasing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="384eb-107">既定値は requeue です。</span><span class="sxs-lookup"><span data-stu-id="384eb-107">The default value is requeue.</span></span> <span data-ttu-id="384eb-108">使用可能な値が含まれます: 'requeue'、'終了'、'waitforjobcompletion'、'unknown'</span><span class="sxs-lookup"><span data-stu-id="384eb-108">Possible values include: 'requeue', 'terminate', 'waitforjobcompletion', 'unknown'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNodeCount">
      <MemberSignature Language="C#" Value="public int TargetNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="384eb-109">取得またはクラスターで目的のコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="384eb-109">Gets or sets the desired number of compute nodes in the Cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="384eb-110">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="384eb-110">Default is 0.</span></span> <span data-ttu-id="384eb-111">AutoScaleSettings が指定されていない場合は、このターゲットに、クラスターが開始します。</span><span class="sxs-lookup"><span data-stu-id="384eb-111">If autoScaleSettings are not specified, then the Cluster starts with this target.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="manualScaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="384eb-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="384eb-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="384eb-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="384eb-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>