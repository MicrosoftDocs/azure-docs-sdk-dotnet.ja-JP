<Type Name="ClusterHealthChunkQueryDescription" FullName="System.Fabric.Description.ClusterHealthChunkQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthChunkQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthChunkQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthChunkQueryDescription = class" />
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
            クラスターの正常性のチャンク クエリの入力をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthChunkQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthChunkQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Description.ClusterHealthChunkQueryDescription" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt; ApplicationFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthStateFilter&gt; ApplicationFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationFilters As IList(Of ApplicationHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ApplicationFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt;" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" />をアプリケーションの子の正常性状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" />をアプリケーションの子の正常性状態に適用できます。</value>
        <remarks>一覧には、1 つの既定のアプリケーション フィルターや、クエリによって返される粒度が細かいエンティティに特定のアプリケーションまたはアプリケーションのアプリケーションのフィルターを含めることができます。
            フィルターに一致するすべてのアプリケーションの子は、クラスターの子として返されます。
            空の場合、アプリケーションは返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicies">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationHealthPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicies As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicies : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ApplicationHealthPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クラスターからのアプリケーションの正常性を評価するために使用するアプリケーションの正常性ポリシーを取得します。 
            </summary>
        <value>アプリケーションの正常性ポリシーは、指定したアプリケーションの正常性を評価するために使用します。</value>
        <remarks>各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。
            アプリケーションが、マップで指定されていない場合、アプリケーション マニフェストで検出された表す ApplicationHealthPolicy が評価のため使用されます。 マップは、既定では空です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.ClusterHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterHealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.ClusterHealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.ClusterHealthPolicy" />
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
            取得または設定、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。 
            </summary>
        <value><see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。</value>
        <remarks>ポリシーは、クラスターとノードの集計された正常性状態で報告されるイベントの集計された正常性状態の評価に使用されます。
            指定されていない場合は、マニフェストまたは既定のクラスターの正常性ポリシーに説明されているクラスターの正常性ポリシーが使用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt; NodeFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.NodeHealthStateFilter&gt; NodeFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthChunkQueryDescription.NodeFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeFilters As IList(Of NodeHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.NodeFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt;" Usage="System.Fabric.Description.ClusterHealthChunkQueryDescription.NodeFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.NodeHealthStateFilter" />をノードの子の正常性状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.NodeHealthStateFilter" />をノードの子の正常性状態に適用できます。</value>
        <remarks>
            フィルターに一致するすべてのノードの子は、クラスターの子として返されます。
            空の場合、ノードは返されません。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>