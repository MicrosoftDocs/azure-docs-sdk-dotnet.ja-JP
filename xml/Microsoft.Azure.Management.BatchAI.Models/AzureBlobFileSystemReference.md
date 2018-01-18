<Type Name="AzureBlobFileSystemReference" FullName="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference">
  <TypeSignature Language="C#" Value="public class AzureBlobFileSystemReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobFileSystemReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobFileSystemReference" />
  <TypeSignature Language="F#" Value="type AzureBlobFileSystemReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1aeb0-101">サービスをクラスター ノードで Azure Blob ストレージ コンテナーをマウントできるようにするための必要な情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-101">Provides required information, for the service to be able to mount Azure Blob Storage container on the cluster nodes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobFileSystemReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-102">AzureBlobFileSystemReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-102">Initializes a new instance of the AzureBlobFileSystemReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobFileSystemReference (string accountName, string containerName, Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string mountOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string containerName, class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo credentials, string relativeMountPath, string mountOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, containerName As String, credentials As AzureStorageCredentialsInfo, relativeMountPath As String, Optional mountOptions As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference : string * string * Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference (accountName, containerName, credentials, relativeMountPath, mountOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" />
        <Parameter Name="relativeMountPath" Type="System.String" />
        <Parameter Name="mountOptions" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="1aeb0-103">Azure Blob ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-103">Name of the Azure Blob Storage account.</span></span></param>
        <param name="containerName"><span data-ttu-id="1aeb0-104">クラスターにマウントする Azure Blob ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-104">Name of the Azure Blob Storage container to mount on the cluster.</span></span></param>
        <param name="credentials"><span data-ttu-id="1aeb0-105">Azure Blob ストレージ アカウントの資格情報の情報です。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-105">Information of the Azure Blob Storage account credentials.</span></span></param>
        <param name="relativeMountPath"><span data-ttu-id="1aeb0-106">Azure Blob のファイル システムをマウントするコンピューティング ノード上の相対パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-106">Specifies the relative path on the compute node where the Azure Blob file system will be mounted.</span></span></param>
        <param name="mountOptions"><span data-ttu-id="1aeb0-107">Blob のファイル システムの構成に使用できるさまざまなマウント オプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-107">Specifies the various mount options that can be used to configure Blob file system.</span></span></param>
        <summary>
            <span data-ttu-id="1aeb0-108">AzureBlobFileSystemReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-108">Initializes a new instance of the AzureBlobFileSystemReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-109">取得または Azure Blob ストレージ アカウントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-109">Gets or sets name of the Azure Blob Storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-110">取得またはクラスターにマウントする Azure Blob ストレージ コンテナーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-110">Gets or sets name of the Azure Blob Storage container to mount on the cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As AzureStorageCredentialsInfo" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-111">取得または Azure Blob ストレージ アカウントの資格情報の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-111">Gets or sets information of the Azure Blob Storage account credentials.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountOptions">
      <MemberSignature Language="C#" Value="public string MountOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.MountOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MountOptions As String" />
      <MemberSignature Language="F#" Value="member this.MountOptions : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.MountOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-112">取得または設定は、Blob のファイル システムの構成に使用できるさまざまなマウント オプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-112">Gets or sets specifies the various mount options that can be used to configure Blob file system.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.RelativeMountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeMountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-113">取得または設定は、Azure Blob のファイル システムをマウントするコンピューティング ノード上の相対パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-113">Gets or sets specifies the relative path on the compute node where the Azure Blob file system will be mounted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1aeb0-114">$AZ_BATCHAI_MOUNT_ROOT 場所の下にあるすべての blob ファイル システムがマウントされることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-114">Note that all blob file systems will be mounted under $AZ_BATCHAI_MOUNT_ROOT location.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureBlobFileSystemReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aeb0-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1aeb0-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1aeb0-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>