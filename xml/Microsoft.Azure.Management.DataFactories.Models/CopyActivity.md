<Type Name="CopyActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.CopyActivity">
  <TypeSignature Language="C#" Value="public class CopyActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CopyActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.CopyActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class CopyActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type CopyActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Copy")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bf9bb-101">アクティビティをコピーします。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-101">Copy activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyActivity (Microsoft.Azure.Management.DataFactories.Models.CopySource source, Microsoft.Azure.Management.DataFactories.Models.CopySink sink, Microsoft.Azure.Management.DataFactories.Models.CopyTranslator translator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactories.Models.CopySource source, class Microsoft.Azure.Management.DataFactories.Models.CopySink sink, class Microsoft.Azure.Management.DataFactories.Models.CopyTranslator translator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.#ctor(Microsoft.Azure.Management.DataFactories.Models.CopySource,Microsoft.Azure.Management.DataFactories.Models.CopySink,Microsoft.Azure.Management.DataFactories.Models.CopyTranslator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As CopySource, sink As CopySink, Optional translator As CopyTranslator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.CopyActivity : Microsoft.Azure.Management.DataFactories.Models.CopySource * Microsoft.Azure.Management.DataFactories.Models.CopySink * Microsoft.Azure.Management.DataFactories.Models.CopyTranslator -&gt; Microsoft.Azure.Management.DataFactories.Models.CopyActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.CopyActivity (source, sink, translator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Management.DataFactories.Models.CopySource" />
        <Parameter Name="sink" Type="Microsoft.Azure.Management.DataFactories.Models.CopySink" />
        <Parameter Name="translator" Type="Microsoft.Azure.Management.DataFactories.Models.CopyTranslator" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="sink">To be added.</param>
        <param name="translator">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudDataMovementUnits">
      <MemberSignature Language="C#" Value="public Nullable&lt;uint&gt; CloudDataMovementUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int32&gt; CloudDataMovementUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudDataMovementUnits As Nullable(Of UInteger)" />
      <MemberSignature Language="F#" Value="member this.CloudDataMovementUnits : Nullable&lt;uint32&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.CloudDataMovementUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.UInt32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-102">Optional.</span></span> <span data-ttu-id="bf9bb-103">クラウド データの移動単位を 2 つのクラウド データ ソースの間でコピーを実行するために使用するには、(DMU) の最大数。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-103">Maximum number of cloud data movement units (DMU) to use for performing copy between two cloud data sources.</span></span>
            <span data-ttu-id="bf9bb-104">既定値に割り当てられたリソース単一 DMU がある場合より大きい値を使用して、ボトルネックより高いスループットを実現できます。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-104">When the resource allocated to the default single DMU is the bottleneck, using a larger value can achieve higher throughput.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableStaging">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableStaging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableStaging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.EnableStaging" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableStaging As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableStaging : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.EnableStaging" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-105">Optional.</span></span> <span data-ttu-id="bf9bb-106">中間のステージングを使用してデータをコピーするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-106">Specifies whether to copy data via an interim staging.</span></span>
            <span data-ttu-id="bf9bb-107">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-107">Default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionLocation">
      <MemberSignature Language="C#" Value="public string ExecutionLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExecutionLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.ExecutionLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionLocation As String" />
      <MemberSignature Language="F#" Value="member this.ExecutionLocation : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.ExecutionLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-108">コピー アクティビティの実行領域。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-108">The execution region of the Copy Activity.</span></span> <span data-ttu-id="bf9bb-109">例: ADF データの移動にサポートされている領域のいずれかを指定する必要があります。"West US"です。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-109">Should be one of the region supported in ADF Data Movement, e.g. "West US".</span></span> <span data-ttu-id="bf9bb-110">省略可能な領域の値は、https://azure.microsoft.com/en-us/documentation/articles/data-factory-data-movement-activities/#global (値が「データ移動のために使用される領域」の列に属しているを参照)</span><span class="sxs-lookup"><span data-stu-id="bf9bb-110">Optional region values are in https://azure.microsoft.com/en-us/documentation/articles/data-factory-data-movement-activities/#global (See values belong to column "Region used for data movement")</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelCopies">
      <MemberSignature Language="C#" Value="public Nullable&lt;uint&gt; ParallelCopies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int32&gt; ParallelCopies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.ParallelCopies" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelCopies As Nullable(Of UInteger)" />
      <MemberSignature Language="F#" Value="member this.ParallelCopies : Nullable&lt;uint32&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.ParallelCopies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.UInt32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-111">Optional.</span></span> <span data-ttu-id="bf9bb-112">ソースとセッションのオーバー ロードは、他のワークロードの影響を与えることを避けるために、シンクで開かれている同時実行セッションの最大数。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-112">Maximum number of concurrent sessions opened on the source and sink, to avoid session overload and affecting other workloads.</span></span>
            <span data-ttu-id="bf9bb-113">構成されていない場合は、ソースおよびシンクの種類ごとに適切な既定値が選択されます。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-113">If not configured, an appropriate default value will be chosen for each type of source and sink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.CopySink Sink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.CopySink Sink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Sink" />
      <MemberSignature Language="VB.NET" Value="Public Property Sink As CopySink" />
      <MemberSignature Language="F#" Value="member this.Sink : Microsoft.Azure.Management.DataFactories.Models.CopySink with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Sink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.CopySink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-114">アクティビティのシンクをコピーします。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-114">Copy activity sink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.CopySource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.CopySource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As CopySource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.DataFactories.Models.CopySource with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.CopySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-115">アクティビティをコピーします。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-115">Copy activity source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagingSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.StagingSettings StagingSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.StagingSettings StagingSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.StagingSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property StagingSettings As StagingSettings" />
      <MemberSignature Language="F#" Value="member this.StagingSettings : Microsoft.Azure.Management.DataFactories.Models.StagingSettings with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.StagingSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.StagingSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-116">Optional.</span></span> <span data-ttu-id="bf9bb-117">EnableStaging が true の場合は、中間のステージング設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-117">Specifies interim staging settings when EnableStaging is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Translator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.CopyTranslator Translator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.CopyTranslator Translator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Translator" />
      <MemberSignature Language="VB.NET" Value="Public Property Translator As CopyTranslator" />
      <MemberSignature Language="F#" Value="member this.Translator : Microsoft.Azure.Management.DataFactories.Models.CopyTranslator with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyActivity.Translator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.CopyTranslator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf9bb-118">アクティビティ トランスレータをコピーします。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-118">Copy activity translator.</span></span> <span data-ttu-id="bf9bb-119">表示できない場合は、指定すると、表形式の変換プログラムを使用します。</span><span class="sxs-lookup"><span data-stu-id="bf9bb-119">If not specified, tabular translator is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>