<Type Name="ServicePlacementPreferPrimaryDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementPreferPrimaryDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementPreferPrimaryDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementPreferPrimaryDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementPreferPrimaryDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServicePlacementPolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="5c0e9-101">表す、<see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />サービスのプライマリ レプリカが最適に配置すること、特定のドメインを示します。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-101">Represents a <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> which indicates that the service’s Primary replicas should optimally be placed in a particular domain.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="5c0e9-102">この制約は通常、Service Fabric クラスターが特定のフォールト ドメインの地理的に分散シナリオで、サービスのプライマリ レプリカを配置することを指定するために地理的に配布されているシナリオでのフォールト ドメインと使用します。通常、地域またはデータ センターの境界に配置します。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-102">This constraint is usually used with fault domains in scenarios where the Service Fabric cluster is geographically distributed in order to indicate that a service’s primary replica should be located in a particular fault domain, which in geo-distributed scenarios usually aligns with regional or datacenter boundaries.</span></span> <span data-ttu-id="5c0e9-103">最適化のためであること、プライマリ レプリカなる可能性がありますいない障害、容量の制限、またはその他の制約のためには、このドメイン内にあることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-103">Note that since this is an optimization it is possible that the Primary replica may not end up located in this domain due to failures, capacity limits, or other constraints.</span></span></para>
    </remarks>
    <example>
      <code>
            <span data-ttu-id="5c0e9-104">サービス配置ポリシー ServicePlacementPreferPrimaryDomainPolicyDescription placementPolicy を作成する新しい ServicePlacementPreferPrimaryDomainPolicyDescription(); を =placementPolicy.DomainName =@"fd:\Datacenter1"です。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-104">//create the service placement policy ServicePlacementPreferPrimaryDomainPolicyDescription placementPolicy = new ServicePlacementPreferPrimaryDomainPolicyDescription(); placementPolicy.DomainName = @"fd:\Datacenter1";</span></span>
            
            <span data-ttu-id="5c0e9-105">ステートフル サービスの説明 StatefulServiceDescription ssd に追加する新しい StatefulServiceDescription(); を =ssd。PlacementPolicies.Add(placementPolicy) です。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-105">//add it to the Stateful Service Description StatefulServiceDescription ssd = new StatefulServiceDescription(); ssd.PlacementPolicies.Add(placementPolicy);</span></span></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementPreferPrimaryDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="5c0e9-106">新しいインスタンスを初期化して、<see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-106">initializing a new instance of the <see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
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
          <para><span data-ttu-id="5c0e9-107">取得または優先的に配置する必要があります、プライマリ レプリカ ドメインの文字列名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-107">Gets or sets the string name of the domain in which the Primary replica should be preferentially located.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5c0e9-108">優先的に配置する必要があります、プライマリ レプリカのドメインの文字列名。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-108">The string name of the domain in which the Primary replica should be preferentially located.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementPreferPrimaryDomainPolicyDescription.ToString " />
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
          <para> 
            <span data-ttu-id="5c0e9-109">'PreferPrimaryDomain、DomainName' 形式の PreferPrimaryDomain サービス配置ポリシーの文字列表現を返す</span><span class="sxs-lookup"><span data-stu-id="5c0e9-109">Return a string representation of the PreferPrimaryDomain Service Placement Policy in the form 'PreferPrimaryDomain, DomainName'</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c0e9-110">オブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="5c0e9-110">A string representing the object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>