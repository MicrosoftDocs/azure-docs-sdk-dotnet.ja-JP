<Type Name="FileShareDataset" FullName="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset">
  <TypeSignature Language="C#" Value="public class FileShareDataset : Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileShareDataset extends Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class FileShareDataset&#xA;Inherits DatasetTypeProperties" />
  <TypeSignature Language="F#" Value="type FileShareDataset = class&#xA;    inherit DatasetTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("FileShare")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="87eaa-101">内部設置型ファイル システムの場合は。</span><span class="sxs-lookup"><span data-stu-id="87eaa-101">An on-premises file system.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileShareDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.Compression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.Compression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As Compression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactories.Models.Compression with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.Compression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-102">データの圧縮方法はファイルで使用します。</span><span class="sxs-lookup"><span data-stu-id="87eaa-102">The data compression method used on files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileFilter">
      <MemberSignature Language="C#" Value="public string FileFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FileFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property FileFilter As String" />
      <MemberSignature Language="F#" Value="member this.FileFilter : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FileFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-103">ワイルドカードによってファイル セットをフィルターします。</span><span class="sxs-lookup"><span data-stu-id="87eaa-103">Files sets filter by wildcard.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public string FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As String" />
      <MemberSignature Language="F#" Value="member this.FileName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-104">ファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="87eaa-104">The name of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public string FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As String" />
      <MemberSignature Language="F#" Value="member this.FolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-105">ファイル フォルダーの名前。</span><span class="sxs-lookup"><span data-stu-id="87eaa-105">The name of the file folder.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As StorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactories.Models.StorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-106">ファイルの形式です。</span><span class="sxs-lookup"><span data-stu-id="87eaa-106">The format of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionedBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.PartitionedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionedBy As IList(Of Partition)" />
      <MemberSignature Language="F#" Value="member this.PartitionedBy : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.PartitionedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-107">パスで使用されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="87eaa-107">The partitions to be used by the path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseBinaryTransfer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseBinaryTransfer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseBinaryTransfer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.UseBinaryTransfer" />
      <MemberSignature Language="VB.NET" Value="Public Property UseBinaryTransfer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseBinaryTransfer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.FileShareDataset.UseBinaryTransfer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87eaa-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="87eaa-108">Optional.</span></span> <span data-ttu-id="87eaa-109">リンクされたサービスは、accociated 場合にのみ使用できます<see cref="T:Microsoft.Azure.Management.DataFactories.Models.FtpServerLinkedService" />です。</span><span class="sxs-lookup"><span data-stu-id="87eaa-109">Can only be used when accociated Linked Service is <see cref="T:Microsoft.Azure.Management.DataFactories.Models.FtpServerLinkedService" />.</span></span>
            <span data-ttu-id="87eaa-110">True の場合、バイナリ モードでは、FTP サーバーからの送信中にデータ表現です。</span><span class="sxs-lookup"><span data-stu-id="87eaa-110">If true, data representation during transmission from FTP server is in Binary mode.</span></span>
            <span data-ttu-id="87eaa-111">False の場合、FTP サーバーからの送信中にデータ表現は、ASCII モードでです。</span><span class="sxs-lookup"><span data-stu-id="87eaa-111">If false, data representation during transmission from FTP server is in ASCII mode.</span></span>
            <span data-ttu-id="87eaa-112">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="87eaa-112">Default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>