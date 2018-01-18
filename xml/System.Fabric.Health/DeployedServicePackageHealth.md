<Type Name="DeployedServicePackageHealth" FullName="System.Fabric.Health.DeployedServicePackageHealth">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="f238d-101">によって返される、展開済みサービス パッケージの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="f238d-101">Describes the health of a deployed service package as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedServicePackageHealth.ApplicationName" />
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
          <para><span data-ttu-id="f238d-102">アプリケーションを一意に識別するアプリケーション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="f238d-102">Gets the application name, which uniquely identifies the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f238d-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="f238d-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.NodeName" />
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
          <para><span data-ttu-id="f238d-104">展開済みサービス パッケージが実行されているノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f238d-104">Gets the node name where the deployed service package is running.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f238d-105">展開済みサービス パッケージが実行されているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="f238d-105">The node name where the deployed service package is running.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.ServiceManifestName" />
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
          <para><span data-ttu-id="f238d-106">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="f238d-106">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f238d-107">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="f238d-107">The service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" />
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
            <span data-ttu-id="f238d-108">展開済みサービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="f238d-108">Gets the ActivationId of deployed service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="f238d-109">展開済みサービス パッケージの ActivationId を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="f238d-109">A string representing ActivationId of deployed service package.</span></span> 
            </para>
          <para>
            <span data-ttu-id="f238d-110">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="f238d-110">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Health.DeployedServicePackageHealth.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="f238d-111">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f238d-111">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealth.ToString " />
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
            <span data-ttu-id="f238d-112">文字列表現を取得、<see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="f238d-112">Gets a string representation of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f238d-113"><see cref="T:System.Fabric.Health.DeployedServicePackageHealth" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="f238d-113">A string representation of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>