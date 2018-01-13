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
      <para>ノードに関する非アクティブ化の詳細な情報が含まれています。</para>
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
          <para>同時に複数のタスクでノードが非アクティブになる可能性がありますを取得します。 各タスクは、別のノードの非アクティブ化インテントを指定することができます。 この例では、有効なインテントはすべての非アクティブ化タスク間での最上位のインテント順序が定義されている一時停止として&lt;再起動&lt;RemoveData です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.NodeDeactivationIntent" /> を返します。</para>
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
            現在失敗している安全性チェックの一覧を取得します。
            </para>
        </summary>
        <value>
          <para>失敗の安全性の一覧を確認します。</para>
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
          <para>ノードの非アクティブ化状態を指定します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.NodeDeactivationStatus" /> を返します。</para>
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
          <para>ノードのすべてのノードの非アクティブ化タスクについてを説明します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Collections.Generic.IList`1" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>