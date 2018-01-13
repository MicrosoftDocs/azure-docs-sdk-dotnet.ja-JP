<Type Name="NodeHealthQueryDescription" FullName="System.Fabric.Description.NodeHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type NodeHealthQueryDescription = class" />
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
      <para>説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.NodeHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthQueryDescription (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeHealthQueryDescription : string -&gt; System.Fabric.Description.NodeHealthQueryDescription" Usage="new System.Fabric.Description.NodeHealthQueryDescription nodeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。 null または空にすることはできません。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.NodeHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>必須のパラメーターは、null または空にすることはできません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />ノードで報告します。 フィルターに一致するイベントのみが返されます。</para>
        </summary>
        <value>
          <para>正常性イベントを返すフィルター。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、集計のノードの正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />ノードの正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ClusterHealthPolicy" />ノードの正常性を評価するために使用します。</para>
        </value>
        <remarks>
          <para>正常性ストア マニフェストからクラスターの正常性ポリシーを使用して指定されていない場合 (場合が存在する) または既定の厳密な正常性ポリシー。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
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
          <para>ノード名を取得します。</para>
        </summary>
        <value>
          <para>ノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            正常性クエリの説明の文字列表現を取得します。
            </summary>
        <returns>正常性クエリの説明の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>