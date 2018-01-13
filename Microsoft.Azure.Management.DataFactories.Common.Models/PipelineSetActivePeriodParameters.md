<Type Name="PipelineSetActivePeriodParameters" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters">
  <TypeSignature Language="C#" Value="public class PipelineSetActivePeriodParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineSetActivePeriodParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineSetActivePeriodParameters" />
  <TypeSignature Language="F#" Value="type PipelineSetActivePeriodParameters = class" />
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
            <span data-ttu-id="24016-101">セットの有効期間を指定するパラメーターは、アクティブな期間の操作をパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="24016-101">Parameters specifying the active period for the set pipeline active period operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineSetActivePeriodParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24016-102">PipelineSetActivePeriodParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24016-102">Initializes a new instance of the PipelineSetActivePeriodParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineSetActivePeriodParameters (string activePeriodStartTime, string activePeriodEndTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string activePeriodStartTime, string activePeriodEndTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activePeriodStartTime As String, activePeriodEndTime As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters : string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" Usage="new Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters (activePeriodStartTime, activePeriodEndTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activePeriodStartTime" Type="System.String" />
        <Parameter Name="activePeriodEndTime" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="activePeriodStartTime">To be added.</param>
        <param name="activePeriodEndTime">To be added.</param>
        <summary>
            <span data-ttu-id="24016-103">必須の引数で PipelineSetActivePeriodParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24016-103">Initializes a new instance of the PipelineSetActivePeriodParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivePeriodEndTime">
      <MemberSignature Language="C#" Value="public string ActivePeriodEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivePeriodEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivePeriodEndTime As String" />
      <MemberSignature Language="F#" Value="member this.ActivePeriodEndTime : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodEndTime" />
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
            <span data-ttu-id="24016-104">必須。</span><span class="sxs-lookup"><span data-stu-id="24016-104">Required.</span></span> <span data-ttu-id="24016-105">ISO 8601 形式のラウンド トリップでパイプラインの終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="24016-105">Pipeline end time in round-trip ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivePeriodStartTime">
      <MemberSignature Language="C#" Value="public string ActivePeriodStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivePeriodStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivePeriodStartTime As String" />
      <MemberSignature Language="F#" Value="member this.ActivePeriodStartTime : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ActivePeriodStartTime" />
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
            <span data-ttu-id="24016-106">必須。</span><span class="sxs-lookup"><span data-stu-id="24016-106">Required.</span></span> <span data-ttu-id="24016-107">パイプラインは、ラウンド トリップの ISO 8601 形式で時刻を起動します。</span><span class="sxs-lookup"><span data-stu-id="24016-107">Pipeline start time in round-trip ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoResolve">
      <MemberSignature Language="C#" Value="public bool AutoResolve { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoResolve" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.AutoResolve" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoResolve As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoResolve : bool with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.AutoResolve" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24016-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="24016-108">Optional.</span></span> <span data-ttu-id="24016-109">競合するパイプラインのアクティブな期間の自動解決します。</span><span class="sxs-lookup"><span data-stu-id="24016-109">Auto resolve active periods of conflicting pipelines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRecalc">
      <MemberSignature Language="C#" Value="public bool ForceRecalc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceRecalc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ForceRecalc" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRecalc As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceRecalc : bool with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters.ForceRecalc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24016-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="24016-110">Optional.</span></span> <span data-ttu-id="24016-111">実行保留中の期間のすべてのスライスをマークします。</span><span class="sxs-lookup"><span data-stu-id="24016-111">Mark all slices in the period as pending execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>