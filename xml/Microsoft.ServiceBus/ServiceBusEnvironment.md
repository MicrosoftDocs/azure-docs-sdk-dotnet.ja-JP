<Type Name="ServiceBusEnvironment" FullName="Microsoft.ServiceBus.ServiceBusEnvironment">
  <TypeSignature Language="C#" Value="public static class ServiceBusEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceBusEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceBusEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusEnvironment" />
  <TypeSignature Language="F#" Value="type ServiceBusEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e7c71-101">Service Bus 環境をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-101">Describes the Service Bus environment.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAccessControlUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAccessControlUri (string serviceNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAccessControlUri(string serviceNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAccessControlUri (serviceNamespace As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAccessControlUri : string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri serviceNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceNamespace"><span data-ttu-id="e7c71-102">サービス名前空間の URI を作成します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-102">The service namespace to create the URI for.</span></span></param>
        <summary><span data-ttu-id="e7c71-103">指定されたサービス名前空間のアクセス制御で使用する URI 文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-103">Creates a URI string to use with access control for the specified service namespace.</span></span></summary>
        <returns><span data-ttu-id="e7c71-104">返します、<see cref="T:System.Uri" />指定した URI を格納しています。</span><span class="sxs-lookup"><span data-stu-id="e7c71-104">Returns a <see cref="T:System.Uri" /> that contains the specified URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheme"><span data-ttu-id="e7c71-105">URI のスキーム。</span><span class="sxs-lookup"><span data-stu-id="e7c71-105">The scheme of the URI.</span></span></param>
        <param name="serviceNamespace"><span data-ttu-id="e7c71-106">アプリケーションで使用されるサービスの名前空間。</span><span class="sxs-lookup"><span data-stu-id="e7c71-106">The service namespace used by the application.</span></span></param>
        <param name="servicePath"><span data-ttu-id="e7c71-107">URI のホスト名のセクションに依存しているサービスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7c71-107">The service path that follows the host name section of the URI.</span></span></param>
        <summary><span data-ttu-id="e7c71-108">指定されたスキーム、サービス名前空間、およびサービスのパスを使用して、アプリケーションのサービス バス URI を構築します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-108">Constructs the Service Bus URI for an application, using the specified scheme, service namespace, and service path.</span></span></summary>
        <returns><span data-ttu-id="e7c71-109">返します、<see cref="T:System.Uri" />新しい URI を格納しています。</span><span class="sxs-lookup"><span data-stu-id="e7c71-109">Returns a <see cref="T:System.Uri" /> that contains the new URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String, suppressRelayPathPrefix As Boolean) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string * bool -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath, suppressRelayPathPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
        <Parameter Name="suppressRelayPathPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scheme"><span data-ttu-id="e7c71-110">URI のスキーム。</span><span class="sxs-lookup"><span data-stu-id="e7c71-110">The scheme of the URI.</span></span></param>
        <param name="serviceNamespace"><span data-ttu-id="e7c71-111">アプリケーションで使用されるサービスの名前空間。</span><span class="sxs-lookup"><span data-stu-id="e7c71-111">The service namespace used by the application.</span></span></param>
        <param name="servicePath"><span data-ttu-id="e7c71-112">URI のホスト名のセクションに依存しているサービスのパス。</span><span class="sxs-lookup"><span data-stu-id="e7c71-112">The service path that follows the host name section of the URI.</span></span></param>
        <param name="suppressRelayPathPrefix"><span data-ttu-id="e7c71-113">True の場合、リレー パス プレフィックスが抑制されます。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="e7c71-113">True if the relay path prefix is suppressed; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="e7c71-114">サービス バスの URI をアプリケーションでは、指定されたスキーム、サービス名前空間、およびサービスのパスを使用して、パス プレフィックスを中継を構築します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-114">Constructs the Service Bus URI for an application, using the specified scheme, service namespace, service path, and relayed path prefix.</span></span></summary>
        <returns><span data-ttu-id="e7c71-115">返します、<see cref="T:System.Uri" />新しい URI を格納しています。</span><span class="sxs-lookup"><span data-stu-id="e7c71-115">Returns a <see cref="T:System.Uri" /> that contains the new URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIdentityHostName">
      <MemberSignature Language="C#" Value="public static string DefaultIdentityHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultIdentityHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultIdentityHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultIdentityHostName : string" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e7c71-116">アクセス制御サービスの既定のホスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-116">Gets the default host name for the Access Control Service.</span></span></summary>
        <value><span data-ttu-id="e7c71-117">既定の id のホスト名を返します。</span><span class="sxs-lookup"><span data-stu-id="e7c71-117">Returns the default identity host name.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SystemConnectivity As ConnectivitySettings" />
      <MemberSignature Language="F#" Value="member this.SystemConnectivity : Microsoft.ServiceBus.ConnectivitySettings" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivitySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e7c71-118">シングルトンを取得します<see cref="T:Microsoft.ServiceBus.ConnectivitySettings" />TCP や HTTP ベースのエンドポイントの接続設定を保持するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7c71-118">Gets the singleton <see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> instance that holds the connectivity settings for TCP and HTTP-based endpoints.</span></span></summary>
        <value><span data-ttu-id="e7c71-119">返します、<see cref="T:Microsoft.ServiceBus.ConnectivitySettings" />接続設定を格納しています。</span><span class="sxs-lookup"><span data-stu-id="e7c71-119">Returns a <see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> that contains the connectivity settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>