<Type Name="StagingStorageAccount" FullName="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount">
  <TypeSignature Language="C#" Value="public class StagingStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StagingStorageAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.StagingStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class StagingStorageAccount" />
  <TypeSignature Language="F#" Value="type StagingStorageAccount = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="efd5a-101">ストレージ アカウントの情報を保持します。</span><span class="sxs-lookup"><span data-stu-id="efd5a-101">Holds storage account information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StagingStorageAccount (string storageAccount, string storageAccountKey, string blobEndpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccount, string storageAccountKey, string blobEndpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As String, storageAccountKey As String, blobEndpoint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.FileStaging.StagingStorageAccount : string * string * string -&gt; Microsoft.Azure.Batch.FileStaging.StagingStorageAccount" Usage="new Microsoft.Azure.Batch.FileStaging.StagingStorageAccount (storageAccount, storageAccountKey, blobEndpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="System.String" />
        <Parameter Name="storageAccountKey" Type="System.String" />
        <Parameter Name="blobEndpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="efd5a-102">使用するストレージ アカウントを指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="efd5a-102">A string specifying the storage account to be used.</span></span></param>
        <param name="storageAccountKey"><span data-ttu-id="efd5a-103">使用するストレージ アカウント キーを指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="efd5a-103">A string specifying the storage account key to be used.</span></span></param>
        <param name="blobEndpoint"><span data-ttu-id="efd5a-104">プライマリ Blob サービスのエンドポイントを指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="efd5a-104">A string specifying the primary Blob service endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="efd5a-105">指定された資格情報とサービス エンドポイントを使用して、StagingStorageAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="efd5a-105">Initializes a new instance of the StagingStorageAccount class using the specified credentials and service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobEndpoint">
      <MemberSignature Language="C#" Value="public string BlobEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.BlobEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.BlobEndpoint : string" Usage="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.BlobEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efd5a-106">Blob ストレージ サービス エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="efd5a-106">The serviced endpoint for blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public string StorageAccount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccount As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : string" Usage="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efd5a-107">使用するストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="efd5a-107">Specifies the storage account to be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountKey">
      <MemberSignature Language="C#" Value="public string StorageAccountKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.StorageAccountKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountKey : string" Usage="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount.StorageAccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efd5a-108">使用するストレージ アカウント キーを指定します。</span><span class="sxs-lookup"><span data-stu-id="efd5a-108">Specifies the storage account key to be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>