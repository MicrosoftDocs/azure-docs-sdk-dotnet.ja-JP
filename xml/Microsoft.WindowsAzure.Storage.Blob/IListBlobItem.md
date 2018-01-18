<Type Name="IListBlobItem" FullName="Microsoft.WindowsAzure.Storage.Blob.IListBlobItem">
  <TypeSignature Language="C#" Value="public interface IListBlobItem" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="VB.NET" Value="Public Interface IListBlobItem" />
  <TypeSignature Language="F#" Value="type IListBlobItem = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3b863-101">Blob の一覧作成操作によって返される項目を表します。</span><span class="sxs-lookup"><span data-stu-id="3b863-101">Represents an item that may be returned by a blob listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Container" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Container As CloudBlobContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b863-102">Blob 項目のコンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="3b863-102">Gets the blob item's container.</span></span>
            </summary>
        <value><span data-ttu-id="3b863-103"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3b863-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b863-104">Blob を取得する項目の親仮想ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="3b863-104">Gets the blob item's parent virtual directory.</span></span>
            </summary>
        <value><span data-ttu-id="3b863-105"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3b863-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b863-106">プライマリとセカンダリの両方の場所の blob 項目の Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="3b863-106">Gets the blob item's URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="3b863-107">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.StorageUri" />blob 項目の Uri は、プライマリとセカンダリの両方の場所を格納します。</span><span class="sxs-lookup"><span data-stu-id="3b863-107">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.StorageUri" /> containing the blob item's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b863-108">プライマリの場所の blob 項目への URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="3b863-108">Gets the URI to the blob item, at the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="3b863-109"><see cref="T:System.Uri" /> Blob 項目の。</span><span class="sxs-lookup"><span data-stu-id="3b863-109">The <see cref="T:System.Uri" /> for the blob item.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>