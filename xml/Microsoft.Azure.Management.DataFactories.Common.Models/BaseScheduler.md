<Type Name="BaseScheduler" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler">
  <TypeSignature Language="C#" Value="public abstract class BaseScheduler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit BaseScheduler extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class BaseScheduler" />
  <TypeSignature Language="F#" Value="type BaseScheduler = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="05242-101">スケジューラの定義。</span><span class="sxs-lookup"><span data-stu-id="05242-101">The scheduler definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseScheduler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05242-102">BaseScheduler クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05242-102">Initializes a new instance of the BaseScheduler class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseScheduler (string frequency, uint interval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string frequency, unsigned int32 interval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.#ctor(System.String,System.UInt32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (frequency As String, interval As UInteger)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler : string * uint32 -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler" Usage="new Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler (frequency, interval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="frequency" Type="System.String" />
        <Parameter Name="interval" Type="System.UInt32" />
      </Parameters>
      <Docs>
        <param name="frequency">To be added.</param>
        <param name="interval">To be added.</param>
        <summary>
            <span data-ttu-id="05242-103">必須の引数で BaseScheduler クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="05242-103">Initializes a new instance of the BaseScheduler class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnchorDateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AnchorDateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AnchorDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.AnchorDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AnchorDateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AnchorDateTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.AnchorDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05242-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="05242-104">Optional.</span></span> <span data-ttu-id="05242-105">参照として使用される日付を計算するスライスの開始ポイントし、終了日。</span><span class="sxs-lookup"><span data-stu-id="05242-105">The date used as a reference point for calculating slice start and end dates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Frequency" />
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
            <span data-ttu-id="05242-106">必須。</span><span class="sxs-lookup"><span data-stu-id="05242-106">Required.</span></span> <span data-ttu-id="05242-107">1 分、時間、日などの観点から頻度。</span><span class="sxs-lookup"><span data-stu-id="05242-107">Frequency in terms of minute, hour, day, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public uint Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As UInteger" />
      <MemberSignature Language="F#" Value="member this.Interval : uint32 with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05242-108">必須。</span><span class="sxs-lookup"><span data-stu-id="05242-108">Required.</span></span> <span data-ttu-id="05242-109">スケジューラの実行の間隔です。</span><span class="sxs-lookup"><span data-stu-id="05242-109">The interval of running the scheduler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Offset : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05242-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="05242-110">Optional.</span></span> <span data-ttu-id="05242-111">アンカー日時を基準としたオフセット。</span><span class="sxs-lookup"><span data-stu-id="05242-111">The offset relative to the anchor time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Style">
      <MemberSignature Language="C#" Value="public string Style { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Style" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Style" />
      <MemberSignature Language="VB.NET" Value="Public Property Style As String" />
      <MemberSignature Language="F#" Value="member this.Style : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.BaseScheduler.Style" />
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
            <span data-ttu-id="05242-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="05242-112">Optional.</span></span> <span data-ttu-id="05242-113">スケジューラのスタイル。</span><span class="sxs-lookup"><span data-stu-id="05242-113">The scheduler style.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>