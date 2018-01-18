<Type Name="CopyDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class CopyDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CopyDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CopyDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type CopyDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec307-101">ディレクトリのコピー操作で指定できるオプションのセットを表します</span><span class="sxs-lookup"><span data-stu-id="ec307-101">Represents a set of options that may be specified for copy directory operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.BlobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec307-102">取得またはコピー先 blob の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="ec307-102">Gets or sets type of destination blob.</span></span> <span data-ttu-id="ec307-103">このオプションは、非 Azure blob ストレージから Azure blob ストレージにコピーするときにのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="ec307-103">This option takes effect only when copying from non Azure blob storage to Azure blob storage.</span></span> <span data-ttu-id="ec307-104">Blob の種類が指定されていない場合は、BlockBlob が使用されます。</span><span class="sxs-lookup"><span data-stu-id="ec307-104">If blob type is not specified, BlockBlob is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public char Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance char Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Char" />
      <MemberSignature Language="F#" Value="member this.Delimiter : char with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Char</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec307-105">取得または仮想ディレクトリの blob 名を区切るために使用する区切り文字を示す文字を設定します。</span><span class="sxs-lookup"><span data-stu-id="ec307-105">Gets or sets a char that indicates the delimiter character used to delimit virtual directories in a blob name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSnapshots">
      <MemberSignature Language="C#" Value="public bool IncludeSnapshots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSnapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.IncludeSnapshots" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSnapshots As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSnapshots : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.IncludeSnapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec307-106">取得または Azure blob ストレージからコピーするときにスナップショットを含めるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="ec307-106">Gets or sets a flag indicating whether to include snapshots when copying from Azure blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ec307-107">コピー元 blob のスナップショットが true の場合、このフラグが設定されている場合は、個別のファイルとしてコピー先にコピーされます。</span><span class="sxs-lookup"><span data-stu-id="ec307-107">If this flag is set to true, snapshots of the source blob will be copied to destination as separate files.</span></span> <span data-ttu-id="ec307-108">"X.y"の形式でソース blob 名を指定するには、ここで 'x' は、ファイル名拡張子のない、'y' がファイル名拡張子は blob のスナップショットの対象ファイルの名前形式"x (%snapshot_time_stamp%).y"です。</span><span class="sxs-lookup"><span data-stu-id="ec307-108">Given a source blob name in the form of "x.y", where 'x' is the file name without extension and 'y' is the file name extension, the destination file name of blob snapshot is formatted as "x (%snapshot_time_stamp%).y".</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>