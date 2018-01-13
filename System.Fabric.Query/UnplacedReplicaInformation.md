<Type Name="UnplacedReplicaInformation" FullName="System.Fabric.Query.UnplacedReplicaInformation">
  <TypeSignature Language="C#" Value="public class UnplacedReplicaInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UnplacedReplicaInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.UnplacedReplicaInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class UnplacedReplicaInformation" />
  <TypeSignature Language="F#" Value="type UnplacedReplicaInformation = class" />
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
      <para>
            Unplaced レプリカの情報が含まれています。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnplacedReplicaInformation (string serviceName, Guid partitionId, System.Collections.Generic.IList&lt;string&gt; reasonsList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceName, valuetype System.Guid partitionId, class System.Collections.Generic.IList`1&lt;string&gt; reasonsList) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.UnplacedReplicaInformation.#ctor(System.String,System.Guid,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceName As String, partitionId As Guid, reasonsList As IList(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.UnplacedReplicaInformation : string * Guid * System.Collections.Generic.IList&lt;string&gt; -&gt; System.Fabric.Query.UnplacedReplicaInformation" Usage="new System.Fabric.Query.UnplacedReplicaInformation (serviceName, partitionId, reasonsList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="reasonsList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前、そのレプリカを配置できませんでした。 </para>
        </param>
        <param name="partitionId">
          <para>パーティション Id (Guid) として、サービスがそのレプリカを配置できませんでした。 </para>
        </param>
        <param name="reasonsList">
          <para>(と理由の文字列の一覧) サービスのレプリカに配置できません。 </para>
        </param>
        <summary>
          <para> 
            UnplacedReplicaInformation のオブジェクトを作成するコンス トラクターです。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UnplacedReplicaInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.UnplacedReplicaInformation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            サービスのレプリカが含まれるを配置できませんでした (Guid) として、パーティション Id を取得します。
            </para>
        </summary>
        <value>
          <para> パーティション Id を設定する Guid です。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UnplacedReplicaInformation.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string" Usage="System.Fabric.Query.UnplacedReplicaInformation.ServiceName" />
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
          <para> 
            レプリカが含まれるを配置できませんでした、サービスの名前を取得します。
            </para>
        </summary>
        <value>
          <para> サービス名を設定する文字列。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnplacedReplicaReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; UnplacedReplicaReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; UnplacedReplicaReasons" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UnplacedReplicaInformation.UnplacedReplicaReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnplacedReplicaReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.UnplacedReplicaReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Query.UnplacedReplicaInformation.UnplacedReplicaReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            サービスのレプリカに配置されません (と文字列の一覧) の理由を取得します。
            </para>
        </summary>
        <value>
          <para>サービス レプリカが配置でした理由。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>