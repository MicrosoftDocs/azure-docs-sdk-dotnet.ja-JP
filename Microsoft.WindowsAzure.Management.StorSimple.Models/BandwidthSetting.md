<Type Name="BandwidthSetting" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting">
  <TypeSignature Language="C#" Value="public class BandwidthSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BandwidthSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class BandwidthSetting" />
  <TypeSignature Language="F#" Value="type BandwidthSetting = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="093eb-101">このクラスは、帯域幅の設定を表します。</span><span class="sxs-lookup"><span data-stu-id="093eb-101">This class represents band width setting</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="093eb-102">BandwidthSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="093eb-102">Initializes a new instance of the BandwidthSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSetting (string name, System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; schedules, int createdFromTemplateId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; schedules, int32 createdFromTemplateId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.#ctor(System.String,System.Collections.Generic.List{Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, schedules As List(Of BandwidthSchedule), createdFromTemplateId As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting : string * System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; * int -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting (name, schedules, createdFromTemplateId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="schedules" Type="System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt;" />
        <Parameter Name="createdFromTemplateId" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="schedules">To be added.</param>
        <param name="createdFromTemplateId">To be added.</param>
        <summary>
            <span data-ttu-id="093eb-103">必須の引数で BandwidthSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="093eb-103">Initializes a new instance of the BandwidthSetting class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedFromTemplateId">
      <MemberSignature Language="C#" Value="public int CreatedFromTemplateId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CreatedFromTemplateId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.CreatedFromTemplateId" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedFromTemplateId As Integer" />
      <MemberSignature Language="F#" Value="member this.CreatedFromTemplateId : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.CreatedFromTemplateId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-104">必須。</span><span class="sxs-lookup"><span data-stu-id="093eb-104">Required.</span></span> <span data-ttu-id="093eb-105">取得または帯域幅の設定の作成元のテンプレートの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="093eb-105">Gets or sets the id of the template from which the bandwidth setting is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="093eb-106">Optional.</span></span> <span data-ttu-id="093eb-107">取得または帯域幅の設定のインスタンス id を設定</span><span class="sxs-lookup"><span data-stu-id="093eb-107">Gets or sets the instance id of the bandwidth setting</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-108">必須。</span><span class="sxs-lookup"><span data-stu-id="093eb-108">Required.</span></span> <span data-ttu-id="093eb-109">取得または帯域幅の設定の名前を設定</span><span class="sxs-lookup"><span data-stu-id="093eb-109">Gets or sets the name of the bandwidth setting</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.OperationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationInProgress As OperationInProgress" />
      <MemberSignature Language="F#" Value="member this.OperationInProgress : Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.OperationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="093eb-110">Optional.</span></span> <span data-ttu-id="093eb-111">取得または実行中の操作があるかどうかを示す値を設定</span><span class="sxs-lookup"><span data-stu-id="093eb-111">Gets or sets a value indicating whether there is an operation in progress</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; Schedules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; Schedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.Schedules" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedules As IList(Of BandwidthSchedule)" />
      <MemberSignature Language="F#" Value="member this.Schedules : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.Schedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSchedule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-112">必須。</span><span class="sxs-lookup"><span data-stu-id="093eb-112">Required.</span></span> <span data-ttu-id="093eb-113">取得または帯域幅は現在の帯域幅設定を関連付けられているスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="093eb-113">Gets or sets bandwidth schedule associated current bandwidth setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeCount">
      <MemberSignature Language="C#" Value="public int VolumeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 VolumeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.VolumeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.VolumeCount : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BandwidthSetting.VolumeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="093eb-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="093eb-114">Optional.</span></span> <span data-ttu-id="093eb-115">取得または帯域幅の設定を適用するボリュームの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="093eb-115">Gets or sets the count of volumes to which the bandwidth setting is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>