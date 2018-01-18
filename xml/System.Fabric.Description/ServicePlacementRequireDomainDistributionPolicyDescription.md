<Type Name="ServicePlacementRequireDomainDistributionPolicyDescription" FullName="System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementRequireDomainDistributionPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementRequireDomainDistributionPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementRequireDomainDistributionPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementRequireDomainDistributionPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
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
      <para><span data-ttu-id="199b8-101">同じパーティションからの 2 つのレプリカが同じ障害やアップグレード ドメインに配置しないでくださいを示す配置ポリシーを指定します。</span><span class="sxs-lookup"><span data-stu-id="199b8-101">Specifies the placement policy which indicates that two replicas from the same partition should never be placed in the same fault or upgrade domain.</span></span>  
            <span data-ttu-id="199b8-102">これは一般的ではありませんは、計画外の停止による同時実行の失敗または後続/同時発生したエラーのそれ以外の場合のリスクが増大するサービスに公開できます。</span><span class="sxs-lookup"><span data-stu-id="199b8-102">While this is not common it can expose the service to an increased risk of concurrent failures due to unplanned outages or other cases of subsequent/concurrent failures.</span></span> <span data-ttu-id="199b8-103">たとえば、場所ごとの 1 つのレプリカとの別のデータ センター間でのレプリカが展開されている場合を考えます。</span><span class="sxs-lookup"><span data-stu-id="199b8-103">As an example, consider a case where replicas are deployed across different data center, with one replica per location.</span></span> <span data-ttu-id="199b8-104">データ センターのいずれかがオフラインになったことは通常、データ センターに配置されたレプリカは、残りのデータ センターのいずれかにパックされます。</span><span class="sxs-lookup"><span data-stu-id="199b8-104">In the event that one of the datacenters goes offline, normally the replica that was placed in that datacenter will be packed into one of the remaining datacenters.</span></span> <span data-ttu-id="199b8-105">これが望ましくない場合は、このポリシーを設定してください。</span><span class="sxs-lookup"><span data-stu-id="199b8-105">If this is not desirable then this policy should be set.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementRequireDomainDistributionPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="199b8-106"><see cref="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="199b8-106">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementRequireDomainDistributionPolicyDescription.ToString " />
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
            <span data-ttu-id="199b8-107">'RequiredDomainDistribution、DomainName' 形式の RequiredDomainDistribution サービス配置ポリシーの文字列表現を返す</span><span class="sxs-lookup"><span data-stu-id="199b8-107">Return a string representation of the RequiredDomainDistribution Service Placement Policy in the form 'RequiredDomainDistribution, DomainName'</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="199b8-108">オブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="199b8-108">A string representing the object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>