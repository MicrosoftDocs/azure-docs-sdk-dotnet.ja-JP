<Type Name="NodeDeactivationResult" FullName="System.Fabric.Query.NodeDeactivationResult">
  <TypeSignature Language="C#" Value="public sealed class NodeDeactivationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeDeactivationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeDeactivationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeDeactivationResult" />
  <TypeSignature Language="F#" Value="type NodeDeactivationResult = class" />
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
      <para><span data-ttu-id="667ac-101">ノードに関する非アクティブ化の詳細な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="667ac-101">Contains the detailed deactivation information about a node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EffectiveIntent">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeDeactivationIntent EffectiveIntent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeDeactivationIntent EffectiveIntent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.EffectiveIntent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EffectiveIntent As NodeDeactivationIntent" />
      <MemberSignature Language="F#" Value="member this.EffectiveIntent : System.Fabric.NodeDeactivationIntent" Usage="System.Fabric.Query.NodeDeactivationResult.EffectiveIntent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="667ac-102">同時に複数のタスクでノードが非アクティブになる可能性がありますを取得します。</span><span class="sxs-lookup"><span data-stu-id="667ac-102">A node may get deactivated by multiple tasks at the same time.</span></span> <span data-ttu-id="667ac-103">各タスクは、別のノードの非アクティブ化インテントを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="667ac-103">Each task may specify a different node deactivation intent.</span></span> <span data-ttu-id="667ac-104">この例では、有効なインテントはすべての非アクティブ化タスク間での最上位のインテント順序が定義されている一時停止として&lt;再起動&lt;RemoveData です。</span><span class="sxs-lookup"><span data-stu-id="667ac-104">In this case, effective intent is highest intent among all deactivation tasks, where ordering is defined as Pause &lt; Restart &lt; RemoveData.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="667ac-105"><see cref="T:System.Fabric.NodeDeactivationIntent" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="667ac-105">Returns <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingSafetyChecks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt; PendingSafetyChecks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.SafetyCheck&gt; PendingSafetyChecks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.PendingSafetyChecks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingSafetyChecks As IList(Of SafetyCheck)" />
      <MemberSignature Language="F#" Value="member this.PendingSafetyChecks : System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt;" Usage="System.Fabric.Query.NodeDeactivationResult.PendingSafetyChecks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="667ac-106">現在失敗している安全性チェックの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="667ac-106">Gets a list of safety checks that are currently failing.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="667ac-107">失敗の安全性の一覧を確認します。</span><span class="sxs-lookup"><span data-stu-id="667ac-107">The list of failing safety checks.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeDeactivationStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeDeactivationStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As NodeDeactivationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.NodeDeactivationStatus" Usage="System.Fabric.Query.NodeDeactivationResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="667ac-108">ノードの非アクティブ化状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="667ac-108">Specifies the deactivation status for a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="667ac-109"><see cref="T:System.Fabric.NodeDeactivationStatus" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="667ac-109">Returns <see cref="T:System.Fabric.NodeDeactivationStatus" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt; Tasks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.NodeDeactivationTask&gt; Tasks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.Tasks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tasks As IList(Of NodeDeactivationTask)" />
      <MemberSignature Language="F#" Value="member this.Tasks : System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt;" Usage="System.Fabric.Query.NodeDeactivationResult.Tasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="667ac-110">ノードのすべてのノードの非アクティブ化タスクについてを説明します。</span><span class="sxs-lookup"><span data-stu-id="667ac-110">Contains information about all the node deactivation tasks for a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="667ac-111"><see cref="T:System.Collections.Generic.IList`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="667ac-111">Returns <see cref="T:System.Collections.Generic.IList`1" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>