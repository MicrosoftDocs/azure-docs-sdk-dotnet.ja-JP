<Type Name="UploadDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class UploadDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UploadDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UploadDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type UploadDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
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
            <span data-ttu-id="46f4e-101">アップロード ディレクトリ操作で指定できるオプションのセットを表します</span><span class="sxs-lookup"><span data-stu-id="46f4e-101">Represents a set of options that may be specified for upload directory operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UploadDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions.#ctor" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions.BlobType" />
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
            <span data-ttu-id="46f4e-102">取得またはコピー先 blob の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="46f4e-102">Gets or sets type of destination blob.</span></span> <span data-ttu-id="46f4e-103">このオプションは、Azure blob ストレージにアップロードする場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="46f4e-103">This option takes effect only when uploading to Azure blob storage.</span></span>
            <span data-ttu-id="46f4e-104">Blob の種類が指定されていない場合は、BlockBlob が使用されます。</span><span class="sxs-lookup"><span data-stu-id="46f4e-104">If blob type is not specified, BlockBlob is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FollowSymlink">
      <MemberSignature Language="C#" Value="public bool FollowSymlink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool FollowSymlink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions.FollowSymlink" />
      <MemberSignature Language="VB.NET" Value="Public Property FollowSymlink As Boolean" />
      <MemberSignature Language="F#" Value="member this.FollowSymlink : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions.FollowSymlink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46f4e-105">取得またはシンボリック リンク ディレクトリに従うかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="46f4e-105">Gets or sets whether to follow symlinked directories.</span></span> <span data-ttu-id="46f4e-106">このオプションは、Unix または Linux のプラットフォームでのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="46f4e-106">This option only works in Unix/Linux platforms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>