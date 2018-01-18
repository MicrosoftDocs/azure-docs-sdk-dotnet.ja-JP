<Type Name="DiagnosticsStorageAccountConfig" FullName="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig">
  <TypeSignature Language="C#" Value="public class DiagnosticsStorageAccountConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticsStorageAccountConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticsStorageAccountConfig" />
  <TypeSignature Language="F#" Value="type DiagnosticsStorageAccountConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25d08-101">診断ストレージ アカウントの構成</span><span class="sxs-lookup"><span data-stu-id="25d08-101">Diagnostics storage account config</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsStorageAccountConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25d08-102">DiagnosticsStorageAccountConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25d08-102">Initializes a new instance of the DiagnosticsStorageAccountConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsStorageAccountConfig (string storageAccountName, string protectedAccountKeyName, string blobEndpoint, string queueEndpoint, string tableEndpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountName, string protectedAccountKeyName, string blobEndpoint, string queueEndpoint, string tableEndpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountName As String, protectedAccountKeyName As String, blobEndpoint As String, queueEndpoint As String, tableEndpoint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig : string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig (storageAccountName, protectedAccountKeyName, blobEndpoint, queueEndpoint, tableEndpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="protectedAccountKeyName" Type="System.String" />
        <Parameter Name="blobEndpoint" Type="System.String" />
        <Parameter Name="queueEndpoint" Type="System.String" />
        <Parameter Name="tableEndpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="25d08-103">診断ストレージ アカウント名</span><span class="sxs-lookup"><span data-stu-id="25d08-103">Diagnostics storage account name</span></span></param>
        <param name="protectedAccountKeyName"><span data-ttu-id="25d08-104">保護された診断のストレージ キー名</span><span class="sxs-lookup"><span data-stu-id="25d08-104">Protected Diagnostics storage key name</span></span></param>
        <param name="blobEndpoint"><span data-ttu-id="25d08-105">診断ストレージ アカウントの blob エンドポイント</span><span class="sxs-lookup"><span data-stu-id="25d08-105">Diagnostics storage account blob endpoint</span></span></param>
        <param name="queueEndpoint"><span data-ttu-id="25d08-106">診断ストレージ アカウント キューのエンドポイント</span><span class="sxs-lookup"><span data-stu-id="25d08-106">Diagnostics storage account queue endpoint</span></span></param>
        <param name="tableEndpoint"><span data-ttu-id="25d08-107">診断ストレージ アカウントのテーブルのエンドポイント</span><span class="sxs-lookup"><span data-stu-id="25d08-107">Diagnostics storage account table endpoint</span></span></param>
        <summary>
            <span data-ttu-id="25d08-108">DiagnosticsStorageAccountConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25d08-108">Initializes a new instance of the DiagnosticsStorageAccountConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobEndpoint">
      <MemberSignature Language="C#" Value="public string BlobEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.BlobEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.BlobEndpoint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.BlobEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d08-109">取得または診断ストレージ アカウントの blob エンドポイントを設定</span><span class="sxs-lookup"><span data-stu-id="25d08-109">Gets or sets diagnostics storage account blob endpoint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedAccountKeyName">
      <MemberSignature Language="C#" Value="public string ProtectedAccountKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectedAccountKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.ProtectedAccountKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedAccountKeyName As String" />
      <MemberSignature Language="F#" Value="member this.ProtectedAccountKeyName : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.ProtectedAccountKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedAccountKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d08-110">取得または設定の保護された診断のストレージ キー名</span><span class="sxs-lookup"><span data-stu-id="25d08-110">Gets or sets protected Diagnostics storage key name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueEndpoint">
      <MemberSignature Language="C#" Value="public string QueueEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueueEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.QueueEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property QueueEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.QueueEndpoint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.QueueEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queueEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d08-111">取得または診断ストレージ アカウント キューのエンドポイントの設定</span><span class="sxs-lookup"><span data-stu-id="25d08-111">Gets or sets diagnostics storage account queue endpoint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountName">
      <MemberSignature Language="C#" Value="public string StorageAccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.StorageAccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountName As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountName : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.StorageAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d08-112">取得または設定診断ストレージ アカウント名</span><span class="sxs-lookup"><span data-stu-id="25d08-112">Gets or sets diagnostics storage account name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableEndpoint">
      <MemberSignature Language="C#" Value="public string TableEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.TableEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property TableEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.TableEndpoint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.TableEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tableEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d08-113">取得または診断ストレージ アカウントのテーブルのエンドポイントの設定</span><span class="sxs-lookup"><span data-stu-id="25d08-113">Gets or sets diagnostics storage account table endpoint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="diagnosticsStorageAccountConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25d08-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="25d08-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="25d08-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="25d08-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>