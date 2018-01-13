<Type Name="DeployedServicePackageHealthState" FullName="System.Fabric.Health.DeployedServicePackageHealthState">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="acac2-101">エンティティの識別子と、集計された正常性状態を含む、展開済みサービス パッケージのヘルス状態を表します。</span><span class="sxs-lookup"><span data-stu-id="acac2-101">Represents the health state of a deployed service package, containing the entity identifier and the aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ApplicationName" />
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
          <para><span data-ttu-id="acac2-102">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="acac2-102">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="acac2-103"><see cref="T:System.Uri" />アプリケーション名を表すです。</span><span class="sxs-lookup"><span data-stu-id="acac2-103">The <see cref="T:System.Uri" /> representing the application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.NodeName" />
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
          <para><span data-ttu-id="acac2-104">展開済みサービス パッケージが実行されているノードのノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="acac2-104">Gets the node name of the node where the deployed service package is running.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="acac2-105">A<see cref="T:System.String" />ノード名を表すです。</span><span class="sxs-lookup"><span data-stu-id="acac2-105">A <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ServiceManifestName" />
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
          <para><span data-ttu-id="acac2-106">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="acac2-106">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="acac2-107">A<see cref="T:System.String" />サービス マニフェスト名を表すです。</span><span class="sxs-lookup"><span data-stu-id="acac2-107">A <see cref="T:System.String" /> representing the service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthState.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealthState.ServicePackageActivationId" />
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
            <span data-ttu-id="acac2-108">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="acac2-108">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="acac2-109"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="acac2-109">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="acac2-110">これを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="acac2-110">This can be obtained by using  <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="acac2-111">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="acac2-111">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="acac2-112">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="acac2-112">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthState.ToString " />
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
            <span data-ttu-id="acac2-113">識別子と、集計された正常性状態を含む、展開済みサービス パッケージのヘルス状態の文字の説明を作成します。</span><span class="sxs-lookup"><span data-stu-id="acac2-113">Creates a string description of the deployed service package health state, containing the identifier and the aggregated health state.</span></span>
            </summary>
        <returns><span data-ttu-id="acac2-114">説明の文字列、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />です。</span><span class="sxs-lookup"><span data-stu-id="acac2-114">String description of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>