<Type Name="ExportJobsOperationResultInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo">
  <TypeSignature Language="C#" Value="public class ExportJobsOperationResultInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportJobsOperationResultInfo extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportJobsOperationResultInfo&#xA;Inherits OperationResultInfoBase" />
  <TypeSignature Language="F#" Value="type ExportJobsOperationResultInfo = class&#xA;    inherit OperationResultInfoBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e91f2-101">このクラスは、ジョブをエクスポートした後に blob の詳細を送信する使用されます。</span><span class="sxs-lookup"><span data-stu-id="e91f2-101">This class is used to send blob details after exporting jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportJobsOperationResultInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-102">ExportJobsOperationResultInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e91f2-102">Initializes a new instance of the ExportJobsOperationResultInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportJobsOperationResultInfo (string blobUrl = null, string blobSasKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobUrl, string blobSasKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional blobUrl As String = null, Optional blobSasKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo : string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo (blobUrl, blobSasKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobUrl" Type="System.String" />
        <Parameter Name="blobSasKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobUrl"><span data-ttu-id="e91f2-103">ジョブの一覧のシリアル化された文字列のエクスポート先 blob の URL です。</span><span class="sxs-lookup"><span data-stu-id="e91f2-103">URL of the blob into which the serialized string of list of jobs is exported.</span></span></param>
        <param name="blobSasKey"><span data-ttu-id="e91f2-104">Blob にアクセスする SAS キー。</span><span class="sxs-lookup"><span data-stu-id="e91f2-104">SAS key to access the blob.</span></span> <span data-ttu-id="e91f2-105">有効期限が切れる 15 分です。</span><span class="sxs-lookup"><span data-stu-id="e91f2-105">It expires in 15 mins.</span></span></param>
        <summary>
            <span data-ttu-id="e91f2-106">ExportJobsOperationResultInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e91f2-106">Initializes a new instance of the ExportJobsOperationResultInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSasKey">
      <MemberSignature Language="C#" Value="public string BlobSasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.BlobSasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobSasKey As String" />
      <MemberSignature Language="F#" Value="member this.BlobSasKey : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.BlobSasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobSasKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-107">取得または blob にアクセスする SAS キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="e91f2-107">Gets or sets SAS key to access the blob.</span></span> <span data-ttu-id="e91f2-108">有効期限が切れる 15 分です。</span><span class="sxs-lookup"><span data-stu-id="e91f2-108">It expires in 15 mins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUrl">
      <MemberSignature Language="C#" Value="public string BlobUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.BlobUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUrl As String" />
      <MemberSignature Language="F#" Value="member this.BlobUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ExportJobsOperationResultInfo.BlobUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-109">取得またはジョブの一覧のシリアル化された文字列のエクスポート先 blob の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="e91f2-109">Gets or sets URL of the blob into which the serialized string of list of jobs is exported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>