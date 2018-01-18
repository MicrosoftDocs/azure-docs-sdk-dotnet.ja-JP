<Type Name="AzureBlobStorageHttpLogsConfig" FullName="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobStorageHttpLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobStorageHttpLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureBlobStorageHttpLogsConfig = class" />
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
            <span data-ttu-id="905ca-101">Azure blob ストレージの構成に http を記録します。</span><span class="sxs-lookup"><span data-stu-id="905ca-101">Http logs to azure blob storage configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageHttpLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="905ca-102">AzureBlobStorageHttpLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="905ca-102">Initializes a new instance of the AzureBlobStorageHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageHttpLogsConfig (string sasUrl = null, Nullable&lt;int&gt; retentionInDays = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasUrl, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sasUrl As String = null, Optional retentionInDays As Nullable(Of Integer) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig" Usage="new Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig (sasUrl, retentionInDays, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sasUrl"><span data-ttu-id="905ca-103">読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーの SAS url。</span><span class="sxs-lookup"><span data-stu-id="905ca-103">SAS url to a azure blob container with read/write/list/delete permissions.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="905ca-104">保有期間日数。</span><span class="sxs-lookup"><span data-stu-id="905ca-104">Retention in days.</span></span>
            <span data-ttu-id="905ca-105">日数より古い blob を削除します。</span><span class="sxs-lookup"><span data-stu-id="905ca-105">Remove blobs older than X days.</span></span>
            <span data-ttu-id="905ca-106">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="905ca-106">0 or lower means no retention.</span></span></param>
        <param name="enabled"><span data-ttu-id="905ca-107">構成が有効になっている場合は true、無効になっている場合は false と構成が設定されていない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="905ca-107">True if configuration is enabled, false if it is disabled and null if configuration is not set.</span></span></param>
        <summary>
            <span data-ttu-id="905ca-108">AzureBlobStorageHttpLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="905ca-108">Initializes a new instance of the AzureBlobStorageHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="905ca-109">取得または設定の構成が有効な場合は null 値で無効になっている場合は構成が設定されていない場合は false の場合は true。</span><span class="sxs-lookup"><span data-stu-id="905ca-109">Gets or sets true if configuration is enabled, false if it is disabled and null if configuration is not set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.RetentionInDays" />
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
            <span data-ttu-id="905ca-110">取得または保有期間を日に設定します。</span><span class="sxs-lookup"><span data-stu-id="905ca-110">Gets or sets retention in days.</span></span>
            <span data-ttu-id="905ca-111">日数より古い blob を削除します。</span><span class="sxs-lookup"><span data-stu-id="905ca-111">Remove blobs older than X days.</span></span>
            <span data-ttu-id="905ca-112">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="905ca-112">0 or lower means no retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AzureBlobStorageHttpLogsConfig.SasUrl" />
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
            <span data-ttu-id="905ca-113">取得または読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーに SAS url を設定します。</span><span class="sxs-lookup"><span data-stu-id="905ca-113">Gets or sets SAS url to a azure blob container with read/write/list/delete permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>