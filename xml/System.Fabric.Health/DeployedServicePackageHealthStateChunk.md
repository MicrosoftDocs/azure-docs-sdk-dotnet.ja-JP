<Type Name="DeployedServicePackageHealthStateChunk" FullName="System.Fabric.Health.DeployedServicePackageHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateChunk" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateChunk = class" />
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
            <span data-ttu-id="d1096-101">展開済みサービス パッケージのヘルス状態チャンク、展開済みサービス パッケージに関する基本的な正常性の情報を含むを表します。</span><span class="sxs-lookup"><span data-stu-id="d1096-101">Represents a deployed service package health state chunk, which contains basic health information about the deployed service package.</span></span>
            <span data-ttu-id="d1096-102">配置済みのアプリケーションの子として含まれます。</span><span class="sxs-lookup"><span data-stu-id="d1096-102">It is included as child of a deployed application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.DeployedServicePackageHealthStateChunk.HealthState" />
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
            <span data-ttu-id="d1096-103">報告された状態のすべてのイベントとアプリケーションの正常性ポリシーに基づく計算された、展開済みサービス パッケージの集計されたヘルス状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="d1096-103">Gets the aggregated health state of the deployed service package, computed based on all reported health events and the application health policy.</span></span>
            </summary>
        <value><span data-ttu-id="d1096-104">展開済みサービス パッケージの集計された正常性状態</span><span class="sxs-lookup"><span data-stu-id="d1096-104">The aggregated health state of the deployed service package .</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateChunk.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealthStateChunk.ServiceManifestName" />
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
            <span data-ttu-id="d1096-105">展開済みサービス パッケージ、一意な識別子、ノード名、およびアプリケーション名の一部であるサービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="d1096-105">Gets the service manifest name, which is part of the deployed service package unique identifier, together with node name and application name.</span></span>
            </summary>
        <value><span data-ttu-id="d1096-106">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="d1096-106">The service manifest name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateChunk.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealthStateChunk.ServicePackageActivationId" />
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
            <span data-ttu-id="d1096-107">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="d1096-107">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="d1096-108"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="d1096-108">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="d1096-109">これを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="d1096-109">This can be obtained by using  <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="d1096-110">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="d1096-110">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="d1096-111">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="d1096-111">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStateChunk.ToString " />
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
            <span data-ttu-id="d1096-112">展開済みサービス パッケージのヘルス状態チャンクの文字列説明を作成します。</span><span class="sxs-lookup"><span data-stu-id="d1096-112">Creates a string description of the deployed service package health state chunk.</span></span>
            </summary>
        <returns><span data-ttu-id="d1096-113">ヘルス状態のチャンクの説明の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="d1096-113">String description of the health state chunk.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>