<Type Name="IDnsManagementClient" FullName="Microsoft.Azure.Management.Dns.IDnsManagementClient">
  <TypeSignature Language="C#" Value="public interface IDnsManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDnsManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.IDnsManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDnsManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IDnsManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c3ccc-101">DNS 管理クライアントです。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-101">The DNS Management Client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-103">API のバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-103">Specifies the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-104">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-104">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-105">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-105">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-106">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-106">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-107">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-107">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="c3ccc-108">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-108">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-109">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-109">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="c3ccc-110">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-110">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.IRecordSetsOperations RecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.IRecordSetsOperations RecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.RecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecordSets As IRecordSetsOperations" />
      <MemberSignature Language="F#" Value="member this.RecordSets : Microsoft.Azure.Management.Dns.IRecordSetsOperations" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.RecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.IRecordSetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-111">IRecordSetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-111">Gets the IRecordSetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-112">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-112">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-113">Microsoft Azure サブスクリプションを一意に識別する Azure サブスクリプション ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-113">Specifies the Azure subscription ID, which uniquely identifies the Microsoft Azure subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.IZonesOperations Zones { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.IZonesOperations Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.IDnsManagementClient.Zones" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Zones As IZonesOperations" />
      <MemberSignature Language="F#" Value="member this.Zones : Microsoft.Azure.Management.Dns.IZonesOperations" Usage="Microsoft.Azure.Management.Dns.IDnsManagementClient.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.IZonesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3ccc-114">IZonesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c3ccc-114">Gets the IZonesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>