<Type Name="ImportExportResponse" FullName="Microsoft.Azure.Management.Sql.Models.ImportExportResponse">
  <TypeSignature Language="C#" Value="public class ImportExportResponse : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImportExportResponse extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ImportExportResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ImportExportResponse&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ImportExportResponse = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f31e1-101">インポート/エクスポートの Get 操作で応答します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-101">Response for Import/Export Get operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportExportResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-102">ImportExportResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-102">Initializes a new instance of the ImportExportResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportExportResponse (string id = null, string name = null, string type = null, string requestType = null, Nullable&lt;Guid&gt; requestId = null, string serverName = null, string databaseName = null, string status = null, string lastModifiedTime = null, string queuedTime = null, string blobUri = null, string errorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string requestType, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string serverName, string databaseName, string status, string lastModifiedTime, string queuedTime, string blobUri, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional requestType As String = null, Optional requestId As Nullable(Of Guid) = null, Optional serverName As String = null, Optional databaseName As String = null, Optional status As String = null, Optional lastModifiedTime As String = null, Optional queuedTime As String = null, Optional blobUri As String = null, Optional errorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ImportExportResponse : string * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ImportExportResponse" Usage="new Microsoft.Azure.Management.Sql.Models.ImportExportResponse (id, name, type, requestType, requestId, serverName, databaseName, status, lastModifiedTime, queuedTime, blobUri, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="requestType" Type="System.String" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="lastModifiedTime" Type="System.String" />
        <Parameter Name="queuedTime" Type="System.String" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f31e1-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="f31e1-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="f31e1-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="f31e1-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="f31e1-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="f31e1-105">Resource type.</span></span></param>
        <param name="requestType"><span data-ttu-id="f31e1-106">操作の要求の種類。</span><span class="sxs-lookup"><span data-stu-id="f31e1-106">The request type of the operation.</span></span></param>
        <param name="requestId"><span data-ttu-id="f31e1-107">操作の要求の種類。</span><span class="sxs-lookup"><span data-stu-id="f31e1-107">The request type of the operation.</span></span></param>
        <param name="serverName"><span data-ttu-id="f31e1-108">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f31e1-108">The name of the server.</span></span></param>
        <param name="databaseName"><span data-ttu-id="f31e1-109">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f31e1-109">The name of the database.</span></span></param>
        <param name="status"><span data-ttu-id="f31e1-110">サーバーからステータス メッセージが返されます。</span><span class="sxs-lookup"><span data-stu-id="f31e1-110">The status message returned from the server.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="f31e1-111">操作の状態には、最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-111">The operation status last modified time.</span></span></param>
        <param name="queuedTime"><span data-ttu-id="f31e1-112">操作がキューに置かれた時間。</span><span class="sxs-lookup"><span data-stu-id="f31e1-112">The operation queued time.</span></span></param>
        <param name="blobUri"><span data-ttu-id="f31e1-113">Blob の uri。</span><span class="sxs-lookup"><span data-stu-id="f31e1-113">The blob uri.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="f31e1-114">サーバーからエラー メッセージが返されます。</span><span class="sxs-lookup"><span data-stu-id="f31e1-114">The error message returned from the server.</span></span></param>
        <summary>
            <span data-ttu-id="f31e1-115">ImportExportResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-115">Initializes a new instance of the ImportExportResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.BlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-116">Blob の uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-116">Gets the blob uri.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-117">データベースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-117">Gets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-118">サーバーから返されるエラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-118">Gets the error message returned from the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public string LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As String" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-119">最終更新時刻の操作状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-119">Gets the operation status last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueuedTime">
      <MemberSignature Language="C#" Value="public string QueuedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueuedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.QueuedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueuedTime As String" />
      <MemberSignature Language="F#" Value="member this.QueuedTime : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.QueuedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queuedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-120">操作を取得しますキューに置かれた時間。</span><span class="sxs-lookup"><span data-stu-id="f31e1-120">Gets the operation queued time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-121">操作の要求の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-121">Gets the request type of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestType">
      <MemberSignature Language="C#" Value="public string RequestType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.RequestType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestType As String" />
      <MemberSignature Language="F#" Value="member this.RequestType : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.RequestType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-122">操作の要求の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-122">Gets the request type of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-123">サーバーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-123">Gets the name of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportExportResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.ImportExportResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f31e1-124">サーバーから返されたステータス メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f31e1-124">Gets the status message returned from the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>