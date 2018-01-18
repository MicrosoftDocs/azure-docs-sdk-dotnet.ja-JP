<Type Name="AzureStorageAccess" FullName="Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess">
  <TypeSignature Language="C#" Value="public class AzureStorageAccess : Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageAccess extends System.Object implements class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageAccess&#xA;Implements IStorageAccess" />
  <TypeSignature Language="F#" Value="type AzureStorageAccess = class&#xA;    interface IStorageAccess" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b9f2f-101">HDInsight クラスターに対してジョブ操作のための記憶域アクセスの詳細を管理します。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-101">Manages storage access details for job operations against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageAccess (string storageAccountName, string storageAccountKey, string defaultStorageContainer, string storageAccountSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountName, string storageAccountKey, string defaultStorageContainer, string storageAccountSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountName As String, storageAccountKey As String, defaultStorageContainer As String, Optional storageAccountSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess : string * string * string * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess" Usage="new Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess (storageAccountName, storageAccountKey, defaultStorageContainer, storageAccountSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="storageAccountKey" Type="System.String" />
        <Parameter Name="defaultStorageContainer" Type="System.String" />
        <Parameter Name="storageAccountSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">
            <span data-ttu-id="b9f2f-102">必須。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-102">Required.</span></span> <span data-ttu-id="b9f2f-103">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-103">The storage account name.</span></span>
            </param>
        <param name="storageAccountKey">
            <span data-ttu-id="b9f2f-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-104">Required.</span></span> <span data-ttu-id="b9f2f-105">ストレージ アカウント キー。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-105">The storage account key.</span></span>
            </param>
        <param name="defaultStorageContainer">
            <span data-ttu-id="b9f2f-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-106">Required.</span></span> <span data-ttu-id="b9f2f-107">既定のストレージ コンテナー名。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-107">The default storage container name.</span></span>
            </param>
        <param name="storageAccountSuffix">
            <span data-ttu-id="b9f2f-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-108">Optional.</span></span> <span data-ttu-id="b9f2f-109">ストレージ アカウントの URI のサフィックスです。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-109">The storage account URI suffix.</span></span> <span data-ttu-id="b9f2f-110">たとえば、"core.chinacloudapi.cn"とします。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-110">For example, "core.chinacloudapi.cn".</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9f2f-111">AzureStorageAccess クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-111">Initializes a new instance of the AzureStorageAccess class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileContent">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetFileContent (string blobReferencePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetFileContent(string blobReferencePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess.GetFileContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFileContent (blobReferencePath As String) As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetFileContent : string -&gt; System.IO.Stream&#xA;override this.GetFileContent : string -&gt; System.IO.Stream" Usage="azureStorageAccess.GetFileContent blobReferencePath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess.GetFileContent(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobReferencePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobReferencePath">
            <span data-ttu-id="b9f2f-112">必須。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-112">Required.</span></span> <span data-ttu-id="b9f2f-113">Url を生成するための blob 参照パス。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-113">Blob reference path for which url to be generated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9f2f-114">Blob 参照のパスからファイルの内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-114">Gets the file content from blob reference path.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b9f2f-115">入力 blob 参照パスのファイルの内容。</span><span class="sxs-lookup"><span data-stu-id="b9f2f-115">Content of the file for the input blob reference path.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>