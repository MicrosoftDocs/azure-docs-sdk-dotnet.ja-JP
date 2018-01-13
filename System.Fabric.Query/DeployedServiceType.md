<Type Name="DeployedServiceType" FullName="System.Fabric.Query.DeployedServiceType">
  <TypeSignature Language="C#" Value="public sealed class DeployedServiceType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServiceType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServiceType" />
  <TypeSignature Language="F#" Value="type DeployedServiceType = class" />
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
      <para><span data-ttu-id="321d5-101">展開済みサービスの種類を表します。</span><span class="sxs-lookup"><span data-stu-id="321d5-101">Represents a deployed service type.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedServiceType.CodePackageName" />
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
          <para><span data-ttu-id="321d5-102">コード パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="321d5-102">Gets the code package name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="321d5-103">コード パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="321d5-103">The code package name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
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
          <para><span data-ttu-id="321d5-104">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="321d5-104">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="321d5-105">サービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="321d5-105">The name of the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
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
            <span data-ttu-id="321d5-106">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="321d5-106">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="321d5-107">展開済みサービス パッケージの ActivationId を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="321d5-107">A string representing ActivationId of deployed service package.</span></span> <span data-ttu-id="321d5-108">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="321d5-108">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="321d5-109">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="321d5-109">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
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
          <para><span data-ttu-id="321d5-110">サービス型の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="321d5-110">Gets the service type name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="321d5-111">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="321d5-111">The name of the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeRegistrationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeRegistrationStatus As ServiceTypeRegistrationStatus" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeRegistrationStatus : System.Fabric.Query.ServiceTypeRegistrationStatus" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceTypeRegistrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="321d5-112">サービスの種類の登録状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="321d5-112">Gets the service type registration status.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="321d5-113">サービス型の登録の状態です。</span><span class="sxs-lookup"><span data-stu-id="321d5-113">The status of the service type registration.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>