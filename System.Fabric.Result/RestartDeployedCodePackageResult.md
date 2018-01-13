<Type Name="RestartDeployedCodePackageResult" FullName="System.Fabric.Result.RestartDeployedCodePackageResult">
  <TypeSignature Language="C#" Value="public class RestartDeployedCodePackageResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RestartDeployedCodePackageResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartDeployedCodePackageResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartDeployedCodePackageResult" />
  <TypeSignature Language="F#" Value="type RestartDeployedCodePackageResult = class" />
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
            <span data-ttu-id="bf6e2-101">再起動展開パッケージの結果オブジェクトのコードを返します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-101">Returns Restart deployed code package result object.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="bf6e2-102">このクラスは、nodeName、applicationName、serviceManifestName、codePackageName、codePackageInstanceId および配置されたコード パッケージ操作の呼び出しの SelectedReplica 情報を返します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-102">This class returns nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId and SelectedReplica information for which the deployed code package action was called.</span></span> <span data-ttu-id="bf6e2-103">ReplicaSelector は none アプリケーションは selecetd nodename、アプリケーション名、サービス マニフェスト、コード パッケージ名、およびコード パッケージ インスタンス id を使用する場合になります。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-103">ReplicaSelector will be none in case application is selecetd using nodename, application name, service manifest, code package name, and code package instance id.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
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
            <span data-ttu-id="bf6e2-104">アプリケーション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-104">Gets Application name.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-105">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-105">The application name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageInstanceId">
      <MemberSignature Language="C#" Value="public long CodePackageInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CodePackageInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.CodePackageInstanceId : int64" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
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
            <span data-ttu-id="bf6e2-106">コード パッケージ インスタンス id を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-106">Gets code package instance id.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-107">コード パッケージ インスタンス id、long として。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-107">The code package instance id, as a long.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
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
            <span data-ttu-id="bf6e2-108">コード パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-108">Gets code package name.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-109">コード パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-109">The code package name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
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
            <span data-ttu-id="bf6e2-110">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-110">Gets node name.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-111">ノード名。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-111">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedReplica SelectedReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedReplica SelectedReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedReplica As SelectedReplica" />
      <MemberSignature Language="F#" Value="member this.SelectedReplica : System.Fabric.SelectedReplica" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf6e2-112">選択したレプリカを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-112">Gets selected replica.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-113">SelectedReplica オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-113">The SelectedReplica object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
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
            <span data-ttu-id="bf6e2-114">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-114">Gets service manifest name.</span></span>
            </summary>
        <value><span data-ttu-id="bf6e2-115">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-115">The service manifest name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
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
            <span data-ttu-id="bf6e2-116">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-116">Gets the ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="bf6e2-117">展開済みサービス パッケージの ActivationId を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-117">A string representing ActivationId of deployed service package.</span></span> <span data-ttu-id="bf6e2-118">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合は、その場合は既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-118">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specfied, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="bf6e2-119">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-119">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartDeployedCodePackageResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartDeployedCodePackageResult.ToString " />
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
            <span data-ttu-id="bf6e2-120">RestartDeployedCodePackageResult 内のデータを文字列として書式設定します。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-120">Formats the data inside RestartDeployedCodePackageResult as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="bf6e2-121">書式設定された文字列。</span><span class="sxs-lookup"><span data-stu-id="bf6e2-121">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>