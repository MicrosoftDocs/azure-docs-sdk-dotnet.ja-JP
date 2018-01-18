<Type Name="MigrationPlanMsg" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg">
  <TypeSignature Language="C#" Value="public class MigrationPlanMsg" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlanMsg extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlanMsg" />
  <TypeSignature Language="F#" Value="type MigrationPlanMsg = class" />
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
            <span data-ttu-id="1bc12-101">特定の構成によってインポートされたすべてのデータ コンテナーの全体的な移行の計画</span><span class="sxs-lookup"><span data-stu-id="1bc12-101">Overall Migration plan for all data containers imported by the specific config</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanMsg (Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan migrationPlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan migrationPlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.#ctor(Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan -&gt; Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg" Usage="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg migrationPlan" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="migrationPlan" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan" />
      </Parameters>
      <Docs>
        <param name="migrationPlan"></param>
        <summary>
            <span data-ttu-id="1bc12-102">指定された構成の移行計画の全体の構築します。</span><span class="sxs-lookup"><span data-stu-id="1bc12-102">Construct overall migration plan for a specified config</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceName">
      <MemberSignature Language="C#" Value="public string DeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.DeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceName As String" />
      <MemberSignature Language="F#" Value="member this.DeviceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.DeviceName" />
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
            <span data-ttu-id="1bc12-103">取得または設定のターゲット デバイス名</span><span class="sxs-lookup"><span data-stu-id="1bc12-103">Gets or sets target device name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegacyConfigId">
      <MemberSignature Language="C#" Value="public string LegacyConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LegacyConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.LegacyConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property LegacyConfigId As String" />
      <MemberSignature Language="F#" Value="member this.LegacyConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.LegacyConfigId" />
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
            <span data-ttu-id="1bc12-104">取得または設定の移行計画のフェッチの一意の識別子の設定</span><span class="sxs-lookup"><span data-stu-id="1bc12-104">Gets or sets the unique identifier of config whose migration plan is fetched</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationCompleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationCompleted As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationCompleted : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1bc12-105">取得または設定が完了した状態にする計画</span><span class="sxs-lookup"><span data-stu-id="1bc12-105">Gets or sets the plan(s) which are in completed state</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationFailed">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationFailed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationFailed" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationFailed As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationFailed : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1bc12-106">取得または設定な障害が発生した状態にある計画</span><span class="sxs-lookup"><span data-stu-id="1bc12-106">Gets or sets the plan(s) which are in failed state</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationInProgress As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationInProgress : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1bc12-107">取得または設定な進行状況の状態にある計画</span><span class="sxs-lookup"><span data-stu-id="1bc12-107">Gets or set the plan(s) which are in progress state</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationNotStarted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationNotStarted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationNotStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationNotStarted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationNotStarted As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationNotStarted : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationNotStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1bc12-108">取得または設定な未開始状態にある計画</span><span class="sxs-lookup"><span data-stu-id="1bc12-108">Gets or sets the plan(s) which are in not started state</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>