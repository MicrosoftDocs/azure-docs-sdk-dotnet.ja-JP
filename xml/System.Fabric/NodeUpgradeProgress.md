<Type Name="NodeUpgradeProgress" FullName="System.Fabric.NodeUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class NodeUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeUpgradeProgress" />
  <TypeSignature Language="F#" Value="type NodeUpgradeProgress = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="227e6-101">詳細については、アップグレードの進行状況のノードのアウトラインを提供します。</span><span class="sxs-lookup"><span data-stu-id="227e6-101">Provides the outlines for the upgrade progress details of a node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.NodeUpgradeProgress.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="227e6-102">アップグレードの進行状況の詳細情報を持つノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="227e6-102">Gets the name of the node having upgrade progress details.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="227e6-103">アップグレードの進行状況の詳細情報を持つノードの名前。</span><span class="sxs-lookup"><span data-stu-id="227e6-103">The name of the node having upgrade progress details.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingSafetyChecks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt; PendingSafetyChecks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.UpgradeSafetyCheck&gt; PendingSafetyChecks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.PendingSafetyChecks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingSafetyChecks As IList(Of UpgradeSafetyCheck)" />
      <MemberSignature Language="F#" Value="member this.PendingSafetyChecks : System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt;" Usage="System.Fabric.NodeUpgradeProgress.PendingSafetyChecks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.UpgradeSafetyCheck&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="227e6-104">Service Fabric は、対応するノードに対して現在実行中の安全性チェックの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="227e6-104">Gets the list of safety checks that Service Fabric is currently performing on the corresponding node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="227e6-105">Service Fabric が対応するノードに対して現在実行中である、安全性チェックの一覧。</span><span class="sxs-lookup"><span data-stu-id="227e6-105">The list of safety checks that is Service Fabric currently performing on the corresponding node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePhase">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeUpgradePhase UpgradePhase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeUpgradePhase UpgradePhase" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeUpgradeProgress.UpgradePhase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradePhase As NodeUpgradePhase" />
      <MemberSignature Language="F#" Value="member this.UpgradePhase : System.Fabric.NodeUpgradePhase" Usage="System.Fabric.NodeUpgradeProgress.UpgradePhase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="227e6-106">ノードのアップグレード フェーズを取得します。</span><span class="sxs-lookup"><span data-stu-id="227e6-106">Gets the upgrade phase of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="227e6-107">ノードのアップグレード フェーズ。</span><span class="sxs-lookup"><span data-stu-id="227e6-107">The upgrade phase of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>