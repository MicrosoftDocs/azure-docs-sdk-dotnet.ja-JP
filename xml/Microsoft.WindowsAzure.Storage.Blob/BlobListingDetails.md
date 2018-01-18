<Type Name="BlobListingDetails" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails">
  <TypeSignature Language="C#" Value="public enum BlobListingDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BlobListingDetails extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
  <TypeSignature Language="VB.NET" Value="Public Enum BlobListingDetails" />
  <TypeSignature Language="F#" Value="type BlobListingDetails = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b8ff7-101">一連の blob を一覧表示するときに含める項目を指定します。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-101">Specifies which items to include when listing a set of blobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails All = int32(15)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 15" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>15</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-102">すべての利用可能なコミットされた blob、コミットされていない blob、およびスナップショットを一覧表示し、それらの blob に対するすべてのメタデータとコピー状態を返します。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-102">List all available committed blobs, uncommitted blobs, and snapshots, and return all metadata and copy status for those blobs.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="Copy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails Copy = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Copy" />
      <MemberSignature Language="VB.NET" Value="Copy" />
      <MemberSignature Language="F#" Value="Copy = 8" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Copy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-103">コピーのプロパティを一覧に含めます。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-103">Include copy properties in the listing.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="Metadata" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails Metadata = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Metadata" />
      <MemberSignature Language="VB.NET" Value="Metadata" />
      <MemberSignature Language="F#" Value="Metadata = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Metadata" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-104">リストで、各 blob の blob メタデータの取得が返されます。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-104">Retrieve blob metadata for each blob returned in the listing.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-105">コミットされた blob のみを一覧表示し、blob のメタデータは返されません。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-105">List only committed blobs, and do not return blob metadata.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Snapshots">
      <MemberSignature Language="C#" Value="Snapshots" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails Snapshots = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Snapshots" />
      <MemberSignature Language="VB.NET" Value="Snapshots" />
      <MemberSignature Language="F#" Value="Snapshots = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.Snapshots" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-106">コミットされた blob を一覧表示して、blob のスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-106">List committed blobs and blob snapshots.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UncommittedBlobs">
      <MemberSignature Language="C#" Value="UncommittedBlobs" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails UncommittedBlobs = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.UncommittedBlobs" />
      <MemberSignature Language="VB.NET" Value="UncommittedBlobs" />
      <MemberSignature Language="F#" Value="UncommittedBlobs = 4" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails.UncommittedBlobs" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8ff7-107">コミット済みおよびコミット前の blob を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b8ff7-107">List committed and uncommitted blobs.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>