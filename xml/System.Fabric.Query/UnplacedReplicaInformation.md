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
            <span data-ttu-id="91b88-101">Unplaced レプリカの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="91b88-101">Contains information for an unplaced replica.</span></span>
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
          <para><span data-ttu-id="91b88-102">サービスの名前、そのレプリカを配置できませんでした。</span><span class="sxs-lookup"><span data-stu-id="91b88-102">The name of the service whose replica could not be placed.</span></span> </para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="91b88-103">パーティション Id (Guid) として、サービスがそのレプリカを配置できませんでした。</span><span class="sxs-lookup"><span data-stu-id="91b88-103">The Partition Id (as a Guid) of the service whose replica could not be placed.</span></span> </para>
        </param>
        <param name="reasonsList">
          <para><span data-ttu-id="91b88-104">(と理由の文字列の一覧) サービスのレプリカに配置できません。</span><span class="sxs-lookup"><span data-stu-id="91b88-104">The reasons (as a list of strings) why a service's replicas could not be placed.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="91b88-105">UnplacedReplicaInformation のオブジェクトを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="91b88-105">Constructor that creates an object of UnplacedReplicaInformation.</span></span>
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
            <span data-ttu-id="91b88-106">サービスのレプリカが含まれるを配置できませんでした (Guid) として、パーティション Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="91b88-106">Gets the Partition Id (as a Guid) of the service whose replica could not be placed.</span></span>
            </para>
        </summary>
        <value>
          <para> <span data-ttu-id="91b88-107">パーティション Id を設定する Guid です。</span><span class="sxs-lookup"><span data-stu-id="91b88-107">The Guid to which PartitionId will be set.</span></span> </para>
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
            <span data-ttu-id="91b88-108">レプリカが含まれるを配置できませんでした、サービスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="91b88-108">Gets the name of the service whose replica could not be placed.</span></span>
            </para>
        </summary>
        <value>
          <para> <span data-ttu-id="91b88-109">サービス名を設定する文字列。</span><span class="sxs-lookup"><span data-stu-id="91b88-109">The string to which ServiceName will be set.</span></span> </para>
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
            <span data-ttu-id="91b88-110">サービスのレプリカに配置されません (と文字列の一覧) の理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="91b88-110">Gets the reasons (as a list of strings) why a service's replicas could not be placed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="91b88-111">サービス レプリカが配置でした理由。</span><span class="sxs-lookup"><span data-stu-id="91b88-111">The reasons why service replicas could not be placed.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>