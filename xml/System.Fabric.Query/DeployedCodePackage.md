<Type Name="DeployedCodePackage" FullName="System.Fabric.Query.DeployedCodePackage">
  <TypeSignature Language="C#" Value="public sealed class DeployedCodePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedCodePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedCodePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedCodePackage" />
  <TypeSignature Language="F#" Value="type DeployedCodePackage = class" />
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
      <para><span data-ttu-id="56705-101">配置されたコード パッケージを表します。</span><span class="sxs-lookup"><span data-stu-id="56705-101">Represents a deployed code package.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedCodePackage.CodePackageName" />
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
          <para><span data-ttu-id="56705-102">コード パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-102">Gets the code package name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-103">コード パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="56705-103">The code package name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.Query.DeployedCodePackage.CodePackageVersion" />
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
          <para><span data-ttu-id="56705-104">コード パッケージのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-104">Gets the code package version.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-105">コード パッケージのバージョン。</span><span class="sxs-lookup"><span data-stu-id="56705-105">The code package version.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedCodePackageStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedCodePackageStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedCodePackageStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.DeployedCodePackageStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedCodePackageStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedCodePackageStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedCodePackage.DeployedCodePackageStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-106">コード パッケージの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-106">Gets the code package status.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-107">配置されたコード パッケージのステータス。</span><span class="sxs-lookup"><span data-stu-id="56705-107">The status of the deployed code package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.CodePackageEntryPoint EntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.CodePackageEntryPoint EntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.EntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryPoint As CodePackageEntryPoint" />
      <MemberSignature Language="F#" Value="member this.EntryPoint : System.Fabric.Query.CodePackageEntryPoint" Usage="System.Fabric.Query.DeployedCodePackage.EntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.CodePackageEntryPoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-108">メイン エントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-108">Gets the main entry point.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-109">メイン エントリ ポイント。</span><span class="sxs-lookup"><span data-stu-id="56705-109">The main entry point.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostIsolationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.HostIsolationMode HostIsolationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.HostIsolationMode HostIsolationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.HostIsolationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostIsolationMode As HostIsolationMode" />
      <MemberSignature Language="F#" Value="member this.HostIsolationMode : System.Fabric.HostIsolationMode" Usage="System.Fabric.Query.DeployedCodePackage.HostIsolationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-110">取得、<see cref="T:System.Fabric.HostIsolationMode" />のメイン エントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="56705-110">Get the <see cref="T:System.Fabric.HostIsolationMode" /> for main entry point.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-111"><see cref="T:System.Fabric.HostIsolationMode" />のメイン エントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="56705-111">The <see cref="T:System.Fabric.HostIsolationMode" /> of main entry point.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostType">
      <MemberSignature Language="C#" Value="public System.Fabric.HostType HostType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.HostType HostType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.HostType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostType As HostType" />
      <MemberSignature Language="F#" Value="member this.HostType : System.Fabric.HostType" Usage="System.Fabric.Query.DeployedCodePackage.HostType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-112">取得、<see cref="T:System.Fabric.HostType" />のメイン エントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="56705-112">Get the <see cref="T:System.Fabric.HostType" /> for main entry point.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-113"><see cref="T:System.Fabric.HostType" />のメイン エントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="56705-113">The <see cref="T:System.Fabric.HostType" /> of main entry point.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunFrequencyInterval">
      <MemberSignature Language="C#" Value="public long RunFrequencyInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RunFrequencyInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.RunFrequencyInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunFrequencyInterval As Long" />
      <MemberSignature Language="F#" Value="member this.RunFrequencyInterval : int64" Usage="System.Fabric.Query.DeployedCodePackage.RunFrequencyInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-114">実行頻度の間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-114">Gets the run frequency interval.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-115">実行頻度の間隔。</span><span class="sxs-lookup"><span data-stu-id="56705-115">The run frequency interval.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedCodePackage.ServiceManifestName" />
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
          <para><span data-ttu-id="56705-116">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-116">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-117">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="56705-117">The service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />
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
            <span data-ttu-id="56705-118">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-118">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="56705-119">表す文字列<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="56705-119">A string representing <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="56705-120">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="56705-120">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="56705-121">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="56705-121">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupEntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.CodePackageEntryPoint SetupEntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.CodePackageEntryPoint SetupEntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.SetupEntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SetupEntryPoint As CodePackageEntryPoint" />
      <MemberSignature Language="F#" Value="member this.SetupEntryPoint : System.Fabric.Query.CodePackageEntryPoint" Usage="System.Fabric.Query.DeployedCodePackage.SetupEntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.CodePackageEntryPoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56705-122">セットアップ エントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="56705-122">Gets the setup entry point.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56705-123">セットアップ エントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="56705-123">The setup entry point.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>