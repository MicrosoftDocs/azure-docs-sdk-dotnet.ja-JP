<Type Name="DataDisk" FullName="Microsoft.Azure.Batch.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class&#xA;    interface ITransportObjectProvider&lt;DataDisk&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fc473-101">プール内の計算ノードに関連付けられているデータ ディスクで使用される設定です。</span><span class="sxs-lookup"><span data-stu-id="fc473-101">Settings which will be used by the data disks associated to compute nodes in the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, int diskSizeGB, Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt; caching = null, Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, int32 diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CachingType&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.StorageAccountType&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.DataDisk.#ctor(System.Int32,System.Int32,System.Nullable{Microsoft.Azure.Batch.Common.CachingType},System.Nullable{Microsoft.Azure.Batch.Common.StorageAccountType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, diskSizeGB As Integer, Optional caching As Nullable(Of CachingType) = null, Optional storageAccountType As Nullable(Of StorageAccountType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.DataDisk : int * int * Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt; -&gt; Microsoft.Azure.Batch.DataDisk" Usage="new Microsoft.Azure.Batch.DataDisk (lun, diskSizeGB, caching, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="diskSizeGB" Type="System.Int32" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="fc473-102">論理ユニットの数です。</span><span class="sxs-lookup"><span data-stu-id="fc473-102">The logical unit number.</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="fc473-103">ギガバイト単位で初期のディスク サイズ。</span><span class="sxs-lookup"><span data-stu-id="fc473-103">The initial disk size in gigabytes.</span></span></param>
        <param name="caching"><span data-ttu-id="fc473-104">OS ディスクを有効にするキャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="fc473-104">The type of caching to enable for the OS disk.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="fc473-105">データ ディスクとして使用するストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="fc473-105">The storage account type to be used for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="fc473-106"><see cref="T:Microsoft.Azure.Batch.DataDisk" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc473-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.DataDisk" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt; Caching { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt;" Usage="Microsoft.Azure.Batch.DataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc473-107">OS ディスクを有効にするキャッシュの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="fc473-107">Gets the type of caching to enable for the OS disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc473-108">省略した場合、既定値は<see cref="F:Microsoft.Azure.Batch.Common.CachingType.None" />します。</span><span class="sxs-lookup"><span data-stu-id="fc473-108">If omitted, the default is <see cref="F:Microsoft.Azure.Batch.Common.CachingType.None" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public int DiskSizeGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskSizeGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : int" Usage="Microsoft.Azure.Batch.DataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc473-109">最初のディスク サイズをギガバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="fc473-109">Gets the initial disk size in gigabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int" Usage="Microsoft.Azure.Batch.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc473-110">論理ユニット番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="fc473-110">Gets the logical unit number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc473-111">Lun を使用して、各データ ディスクを一意に識別します。</span><span class="sxs-lookup"><span data-stu-id="fc473-111">The lun is used to uniquely identify each data disk.</span></span> <span data-ttu-id="fc473-112">複数のディスクをアタッチするには、それぞれが個別の lun を持ちます。</span><span class="sxs-lookup"><span data-stu-id="fc473-112">If attaching multiple disks, each should have a distinct lun.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt; StorageAccountType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.StorageAccountType&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.DataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountType As Nullable(Of StorageAccountType)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt;" Usage="Microsoft.Azure.Batch.DataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.StorageAccountType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc473-113">データ ディスクを使用するストレージ アカウントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="fc473-113">Gets the storage account type to be used for the data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc473-114">省略した場合、既定値は<see cref="F:Microsoft.Azure.Batch.Common.StorageAccountType.StandardLrs" />します。</span><span class="sxs-lookup"><span data-stu-id="fc473-114">If omitted, the default is <see cref="F:Microsoft.Azure.Batch.Common.StorageAccountType.StandardLrs" />.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>