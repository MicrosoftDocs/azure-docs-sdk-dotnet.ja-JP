<Type Name="IServiceFabricManagementClient" FullName="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient">
  <TypeSignature Language="C#" Value="public interface IServiceFabricManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceFabricManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceFabricManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IServiceFabricManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary />
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-101">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-101">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-102">バージョンの ServiceFabric リソース プロバイダー api</span><span class="sxs-lookup"><span data-stu-id="2ab74-102">The version of the ServiceFabric resouce provider api</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-103">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="2ab74-103">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clusters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.IClustersOperations Clusters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.IClustersOperations Clusters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Clusters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Clusters As IClustersOperations" />
      <MemberSignature Language="F#" Value="member this.Clusters : Microsoft.Azure.Management.ServiceFabric.IClustersOperations" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Clusters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.IClustersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-104">IClustersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-104">Gets the IClustersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterVersions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations ClusterVersions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations ClusterVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.ClusterVersions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterVersions As IClusterVersionsOperations" />
      <MemberSignature Language="F#" Value="member this.ClusterVersions : Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.ClusterVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.IClusterVersionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-105">IClusterVersionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-105">Gets the IClusterVersionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="2ab74-106">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-107">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-107">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-108">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="2ab74-108">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="2ab74-109">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="2ab74-109">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-110">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-110">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="2ab74-111">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="2ab74-111">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.ServiceFabric.IOperations" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-112">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-112">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-113">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ab74-113">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.IServiceFabricManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ab74-114">お客様のサブスクリプション id</span><span class="sxs-lookup"><span data-stu-id="2ab74-114">The customer subscription identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>