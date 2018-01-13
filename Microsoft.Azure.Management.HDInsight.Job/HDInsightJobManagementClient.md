<Type Name="HDInsightJobManagementClient" FullName="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient">
  <TypeSignature Language="C#" Value="public class HDInsightJobManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt;, IDisposable, Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightJobManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt; implements class Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightJobManagementClient&#xA;Inherits ServiceClient(Of HDInsightJobManagementClient)&#xA;Implements IDisposable, IHDInsightJobManagementClient" />
  <TypeSignature Language="F#" Value="type HDInsightJobManagementClient = class&#xA;    inherit ServiceClient&lt;HDInsightJobManagementClient&gt;&#xA;    interface IHDInsightJobManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="61a24-101">HDInsight ジョブ クライアントでは、HDInsight クラスターに対してジョブを管理します。</span><span class="sxs-lookup"><span data-stu-id="61a24-101">The HDInsight job client manages jobs against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightJobManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61a24-102">HDInsightJobManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a24-102">Initializes a new instance of the HDInsightJobManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightJobManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient" Usage="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            <span data-ttu-id="61a24-103">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="61a24-103">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="61a24-104">HDInsightJobManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a24-104">Initializes a new instance of the HDInsightJobManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightJobManagementClient (string clusterDnsName, Hyak.Common.BasicAuthenticationCloudCredentials credentials, Hyak.Common.TransientFaultHandling.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clusterDnsName, class Hyak.Common.BasicAuthenticationCloudCredentials credentials, class Hyak.Common.TransientFaultHandling.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.#ctor(System.String,Hyak.Common.BasicAuthenticationCloudCredentials,Hyak.Common.TransientFaultHandling.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient : string * Hyak.Common.BasicAuthenticationCloudCredentials * Hyak.Common.TransientFaultHandling.RetryPolicy -&gt; Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient" Usage="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient (clusterDnsName, credentials, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterDnsName" Type="System.String" />
        <Parameter Name="credentials" Type="Hyak.Common.BasicAuthenticationCloudCredentials" />
        <Parameter Name="retryPolicy" Type="Hyak.Common.TransientFaultHandling.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="clusterDnsName">
            <span data-ttu-id="61a24-105">必須。</span><span class="sxs-lookup"><span data-stu-id="61a24-105">Required.</span></span> <span data-ttu-id="61a24-106">ジョブ管理の実行対象となるクラスター dns 名。</span><span class="sxs-lookup"><span data-stu-id="61a24-106">The cluster dns name against which the job management is to be performed.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="61a24-107">必須。</span><span class="sxs-lookup"><span data-stu-id="61a24-107">Required.</span></span> <span data-ttu-id="61a24-108">ジョブの送信の基本認証資格情報。</span><span class="sxs-lookup"><span data-stu-id="61a24-108">Basic authentication credentials for job submission.</span></span>
            </param>
        <param name="retryPolicy">
            <span data-ttu-id="61a24-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="61a24-109">Optional.</span></span> <span data-ttu-id="61a24-110">Http の一時的なエラーの再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="61a24-110">Retry Policy for Http Transient errors.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61a24-111">HDInsightJobManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a24-111">Initializes a new instance of the HDInsightJobManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightJobManagementClient (string clusterDnsName, Hyak.Common.BasicAuthenticationCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clusterDnsName, class Hyak.Common.BasicAuthenticationCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.#ctor(System.String,Hyak.Common.BasicAuthenticationCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient : string * Hyak.Common.BasicAuthenticationCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient" Usage="new Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient (clusterDnsName, credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterDnsName" Type="System.String" />
        <Parameter Name="credentials" Type="Hyak.Common.BasicAuthenticationCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="clusterDnsName">
            <span data-ttu-id="61a24-112">必須。</span><span class="sxs-lookup"><span data-stu-id="61a24-112">Required.</span></span> <span data-ttu-id="61a24-113">ジョブ管理の実行対象となるクラスター dns 名。</span><span class="sxs-lookup"><span data-stu-id="61a24-113">The cluster dns name against which the job management is to be performed.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="61a24-114">必須。</span><span class="sxs-lookup"><span data-stu-id="61a24-114">Required.</span></span> <span data-ttu-id="61a24-115">ジョブの送信の基本認証資格情報。</span><span class="sxs-lookup"><span data-stu-id="61a24-115">Basic authentication credentials for job submission.</span></span>
            </param>
        <param name="httpClient">
            <span data-ttu-id="61a24-116">Http クライアント</span><span class="sxs-lookup"><span data-stu-id="61a24-116">The Http client</span></span>
            </param>
        <summary>
            <span data-ttu-id="61a24-117">HDInsightJobManagementClient クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a24-117">Initializes a new instance of the HDInsightJobManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of HDInsightJobManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt; -&gt; unit" Usage="hDInsightJobManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            <span data-ttu-id="61a24-118">複製する HDInsightJobManagementClient のインスタンス</span><span class="sxs-lookup"><span data-stu-id="61a24-118">Instance of HDInsightJobManagementClient to clone to</span></span>
            </param>
        <summary>
            <span data-ttu-id="61a24-119">現在のインスタンスから別の HDInsightJobManagementClient インスタンスにプロパティのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="61a24-119">Clones properties from current instance to another HDInsightJobManagementClient instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterDnsName">
      <MemberSignature Language="C#" Value="public string ClusterDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterDnsName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.ClusterDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ClusterDnsName : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.ClusterDnsName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.ClusterDnsName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-120">ジョブ管理の実行対象となるクラスター dns 名。</span><span class="sxs-lookup"><span data-stu-id="61a24-120">The cluster dns name against which the job management is to be performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Hyak.Common.BasicAuthenticationCloudCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Hyak.Common.BasicAuthenticationCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As BasicAuthenticationCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Hyak.Common.BasicAuthenticationCloudCredentials with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Hyak.Common.BasicAuthenticationCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-121">ジョブの送信の基本認証資格情報。</span><span class="sxs-lookup"><span data-stu-id="61a24-121">Basic authentication credentials for job submission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPollInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultPollInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultPollInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.DefaultPollInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultPollInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultPollInterval : TimeSpan" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.DefaultPollInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-122">HDInsight ジョブ管理クライアントのジョブの状態を取得する既定のポーリング間隔。</span><span class="sxs-lookup"><span data-stu-id="61a24-122">The default poll interval to get job status for the HDInsight Job Management Client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HDInsightRetryPolicy">
      <MemberSignature Language="C#" Value="public static Hyak.Common.TransientFaultHandling.RetryPolicy HDInsightRetryPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Hyak.Common.TransientFaultHandling.RetryPolicy HDInsightRetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.HDInsightRetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property HDInsightRetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.HDInsightRetryPolicy : Hyak.Common.TransientFaultHandling.RetryPolicy" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.HDInsightRetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Hyak.Common.TransientFaultHandling.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-123">HDInsight ジョブ管理クライアントの推奨される再試行ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="61a24-123">Gets the recommended Retry Policy for the HDInsight Job Management Client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagement">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.HDInsight.Job.IJobOperations JobManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Job.IJobOperations JobManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.JobManagement" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property JobManagement As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.JobManagement : Microsoft.Azure.Management.HDInsight.Job.IJobOperations" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.JobManagement" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.JobManagement</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-124">HDInsight クラスターに対してジョブを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="61a24-124">Operations for managing jobs against HDInsight clusters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SdkUserAgent">
      <MemberSignature Language="C#" Value="public string SdkUserAgent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SdkUserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.SdkUserAgent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SdkUserAgent As String" />
      <MemberSignature Language="F#" Value="member this.SdkUserAgent : string" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.SdkUserAgent" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.SdkUserAgent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-125">取得またはユーザー エージェントのヘッダーに追加する SDK UserAgent テキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a24-125">Gets or sets the SDK UserAgent text to be added to the user agent header.</span></span> <span data-ttu-id="61a24-126">さらにさまざまな SDK のバージョンを区別するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="61a24-126">This is used to further differentiate various SDK versions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.UserAgentSuffix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserAgentSuffix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-127">取得またはユーザー エージェントのヘッダーに追加する追加の UserAgent テキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a24-127">Gets or sets the additional UserAgent text to be added to the user agent header.</span></span> <span data-ttu-id="61a24-128">さらにアプリケーションを使用して区別するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="61a24-128">This is used to further differentiate using applications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.Azure.Management.HDInsight.Job.HDInsightJobManagementClient.UserName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a24-129">小文字のみがジョブを実行するためのユーザー名の BasicAuthenticationCloudCredentials からユーザー名。</span><span class="sxs-lookup"><span data-stu-id="61a24-129">The user name from Username of BasicAuthenticationCloudCredentials in lower case used for running job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>