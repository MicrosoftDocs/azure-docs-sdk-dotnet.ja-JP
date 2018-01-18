<Type Name="AzureBlobStorageApplicationLogsConfig" FullName="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobStorageApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureBlobStorageApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ff88-101">アプリケーションでは、azure blob ストレージの構成を記録します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-101">Application logs azure blob storage configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ff88-102">AzureBlobStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-102">Initializes a new instance of the AzureBlobStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig (Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; level = null, string sasUrl = null, Nullable&lt;int&gt; retentionInDays = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; level, string sasUrl, valuetype System.Nullable`1&lt;int32&gt; retentionInDays) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.#ctor(System.Nullable{Microsoft.Azure.Management.WebSites.Models.LogLevel},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional level As Nullable(Of LogLevel) = null, Optional sasUrl As String = null, Optional retentionInDays As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig" Usage="new Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig (level, sasUrl, retentionInDays)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt;" />
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="2ff88-103">ログ レベル。</span><span class="sxs-lookup"><span data-stu-id="2ff88-103">Log level.</span></span> <span data-ttu-id="2ff88-104">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="2ff88-104">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span></param>
        <param name="sasUrl"><span data-ttu-id="2ff88-105">読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーの SAS url。</span><span class="sxs-lookup"><span data-stu-id="2ff88-105">SAS url to a azure blob container with read/write/list/delete permissions.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="2ff88-106">保有期間日数。</span><span class="sxs-lookup"><span data-stu-id="2ff88-106">Retention in days.</span></span>
            <span data-ttu-id="2ff88-107">日数より古い blob を削除します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-107">Remove blobs older than X days.</span></span>
            <span data-ttu-id="2ff88-108">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="2ff88-108">0 or lower means no retention.</span></span></param>
        <summary>
            <span data-ttu-id="2ff88-109">AzureBlobStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-109">Initializes a new instance of the AzureBlobStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ff88-110">取得またはログ レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-110">Gets or sets log level.</span></span> <span data-ttu-id="2ff88-111">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="2ff88-111">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ff88-112">取得または保有期間を日に設定します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-112">Gets or sets retention in days.</span></span>
            <span data-ttu-id="2ff88-113">日数より古い blob を削除します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-113">Remove blobs older than X days.</span></span>
            <span data-ttu-id="2ff88-114">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="2ff88-114">0 or lower means no retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sasUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ff88-115">取得または読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーに SAS url を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ff88-115">Gets or sets SAS url to a azure blob container with read/write/list/delete permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>