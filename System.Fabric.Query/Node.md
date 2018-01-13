<Type Name="Node" FullName="System.Fabric.Query.Node">
  <TypeSignature Language="C#" Value="public sealed class Node" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Node extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Node" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Node" />
  <TypeSignature Language="F#" Value="type Node = class" />
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
      <para>Service Fabric クラスター ノードを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string" Usage="System.Fabric.Query.Node.CodeVersion" />
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
          <para>ノードで実行されている Service Fabric ランタイムのバージョンを取得します。</para>
        </summary>
        <value>
          <para>ノードで実行されている Service Fabric ランタイムのバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigVersion">
      <MemberSignature Language="C#" Value="public string ConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.ConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.ConfigVersion : string" Usage="System.Fabric.Query.Node.ConfigVersion" />
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
          <para>ノードのクラスター構成のバージョンを取得します。</para>
        </summary>
        <value>
          <para>ノードのクラスター構成のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultDomain">
      <MemberSignature Language="C#" Value="public Uri FaultDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri FaultDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.FaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultDomain As Uri" />
      <MemberSignature Language="F#" Value="member this.FaultDomain : Uri" Usage="System.Fabric.Query.Node.FaultDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このノードの障害ドメインを取得します。</para>
          <remarks>
            <para>フォールト ドメインは、電源やネットワーク リソースなど、共有の物理的な依存関係により、同時に障害が発生する可能性があるノードのセットを定義します。 フォールト ドメインは、通常階層を表すし、を使用してそのため、表現<see cref="T:System.Uri" />です。</para>
          </remarks>
        </summary>
        <value>
          <para>このノードの障害ドメインです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Node.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノードの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>ノードの正常性状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressOrFQDN">
      <MemberSignature Language="C#" Value="public string IpAddressOrFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddressOrFQDN" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IpAddressOrFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpAddressOrFQDN As String" />
      <MemberSignature Language="F#" Value="member this.IpAddressOrFQDN : string" Usage="System.Fabric.Query.Node.IpAddressOrFQDN" />
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
          <para>IP アドレスまたはノードの完全修飾ドメイン名 (FQDN) を取得します。</para>
        </summary>
        <value>
          <para>IP アドレスまたはノードの完全修飾ドメイン名 (FQDN) です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSeedNode">
      <MemberSignature Language="C#" Value="public bool IsSeedNode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSeedNode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsSeedNode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSeedNode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSeedNode : bool" Usage="System.Fabric.Query.Node.IsSeedNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>シード ノードかどうかを示す値を取得します。 シード ノードは、特別な種類のノードで自動的に構成し、システムによって内部的に使用します。 </para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>このインスタンスがシード ノード以外の場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStopped">
      <MemberSignature Language="C#" Value="public bool IsStopped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStopped" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsStopped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsStopped As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStopped : bool" Usage="System.Fabric.Query.Node.IsStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            ノードが停止している場合は true。  ノードは停止状態には、NodeTransitionType の停止と StartNodeTransitionAsync に成功した呼び出しのターゲットの場合です。
            </para>
        </summary>
        <value>
          <para>ノードが停止しているかどうか</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeactivationInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDeactivationInfo As NodeDeactivationResult" />
      <MemberSignature Language="F#" Value="member this.NodeDeactivationInfo : System.Fabric.Query.NodeDeactivationResult" Usage="System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeDeactivationResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            ノードの非アクティブ化情報を取得します。
            </para>
        </summary>
        <value>
          <para>ノード非アクティブ化情報。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownAt">
      <MemberSignature Language="C#" Value="public DateTime NodeDownAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeDownAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeDownAt : DateTime" Usage="System.Fabric.Query.Node.NodeDownAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>下にノードの状態が変更されたときに、日付時刻を取得します。</para>
        </summary>
        <value>
          <para>下にノードの状態が変更されたときに日付時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeDownTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeDownTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeDownTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeDownTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeDownAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ダウン時間のノードを取得します。</para>
        </summary>
        <value>
          <para>ダウン時間のノードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.Query.Node.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Service Fabric ノードを一意に識別するために使用する内部 ID を取得します。</para>
        </summary>
        <value>
          <para>Service Fabric ノードを一意に識別するために使用する内部 ID。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.Query.Node.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Service Fabric ノード インスタンスを一意に識別するために使用する内部 ID を取得します。 NodeId は、NodeName から確定的にマップされて、ノードの再起動前後で変わらない ただし、ノードを再起動するたびに、NodeInstanceId が変更されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Numerics.BigInteger" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Node.NodeName" />
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
          <para>ノードの名前を取得します。</para>
        </summary>
        <value>
          <para>ノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeStatus NodeStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.NodeStatus NodeStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeStatus As NodeStatus" />
      <MemberSignature Language="F#" Value="member this.NodeStatus : System.Fabric.Query.NodeStatus" Usage="System.Fabric.Query.Node.NodeStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノードの状態を取得します。</para>
        </summary>
        <value>
          <para>ノードの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeType">
      <MemberSignature Language="C#" Value="public string NodeType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeType As String" />
      <MemberSignature Language="F#" Value="member this.NodeType : string" Usage="System.Fabric.Query.Node.NodeType" />
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
          <para>ノードの種類を取得します。</para>
        </summary>
        <value>
          <para>ノード型。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpAt">
      <MemberSignature Language="C#" Value="public DateTime NodeUpAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeUpAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeUpAt : DateTime" Usage="System.Fabric.Query.Node.NodeUpAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>セットアップにノードの状態が変更されたときに、日付時刻を取得します。</para>
        </summary>
        <value>
          <para>セットアップにノードの状態が変更されたときに日付時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeUpTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeUpTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeUpTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeUpTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeUpAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノードのアップタイムを取得します。</para>
        </summary>
        <value>
          <para>稼働時間のノードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomain">
      <MemberSignature Language="C#" Value="public string UpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.UpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomain : string" Usage="System.Fabric.Query.Node.UpgradeDomain" />
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
          <para>このノードのアップグレード ドメインの値を取得します。 </para>
          <remarks>アップグレード ドメインがシャット ダウンのアップグレードを同時に約ノードのセットを定義します。</remarks>
        </summary>
        <value>
          <para>このノードのアップグレード ドメイン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>