<Type Name="DataDisk" FullName="Microsoft.Azure.Batch.Protocol.Models.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class" />
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
            <span data-ttu-id="5bfba-101">プール内の計算ノードに関連付けられているデータ ディスクで使用される設定です。</span><span class="sxs-lookup"><span data-stu-id="5bfba-101">Settings which will be used by the data disks associated to compute nodes in the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-102">DataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-102">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, int diskSizeGB, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, int32 diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.#ctor(System.Int32,System.Int32,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CachingType},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.StorageAccountType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, diskSizeGB As Integer, Optional caching As Nullable(Of CachingType) = null, Optional storageAccountType As Nullable(Of StorageAccountType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.DataDisk : int * int * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.DataDisk" Usage="new Microsoft.Azure.Batch.Protocol.Models.DataDisk (lun, diskSizeGB, caching, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="diskSizeGB" Type="System.Int32" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="5bfba-103">論理ユニットの数です。</span><span class="sxs-lookup"><span data-stu-id="5bfba-103">The logical unit number.</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="5bfba-104">ギガバイト単位で初期のディスク サイズ。</span><span class="sxs-lookup"><span data-stu-id="5bfba-104">The initial disk size in gigabytes.</span></span></param>
        <param name="caching"><span data-ttu-id="5bfba-105">データ ディスクに対して有効にするキャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="5bfba-105">The type of caching to be enabled for the data disks.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="5bfba-106">データ ディスクとして使用するストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="5bfba-106">The storage account type to be used for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="5bfba-107">DataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-107">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-108">取得またはデータ ディスクに対して有効にするキャッシュの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-108">Gets or sets the type of caching to be enabled for the data disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5bfba-109">キャッシュの既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="5bfba-109">The default value for caching is none.</span></span> <span data-ttu-id="5bfba-110">キャッシュのオプションに関する情報を参照してください: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/です。</span><span class="sxs-lookup"><span data-stu-id="5bfba-110">For information about the caching options see: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span></span>
            <span data-ttu-id="5bfba-111">使用可能な値が含まれます 'none'、'readOnly'、'readWrite'。</span><span class="sxs-lookup"><span data-stu-id="5bfba-111">Possible values include: 'none', 'readOnly', 'readWrite'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public int DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-112">取得またはギガバイト単位で初期のディスクのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-112">Gets or sets the initial disk size in gigabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-113">取得または論理ユニット番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-113">Gets or sets the logical unit number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5bfba-114">Lun を使用して、各データ ディスクを一意に識別します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-114">The lun is used to uniquely identify each data disk.</span></span> <span data-ttu-id="5bfba-115">複数のディスクをアタッチするには、それぞれが個別の lun を持ちます。</span><span class="sxs-lookup"><span data-stu-id="5bfba-115">If attaching multiple disks, each should have a distinct lun.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.DataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountType)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.DataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.StorageAccountType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-116">取得またはデータ ディスクを使用するストレージ アカウントの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-116">Gets or sets the storage account type to be used for the data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5bfba-117">省略した場合、既定値は"standard_lrs"にします。</span><span class="sxs-lookup"><span data-stu-id="5bfba-117">If omitted, the default is "standard_lrs".</span></span> <span data-ttu-id="5bfba-118">使用可能な値が含まれます: 'StandardLRS'、'PremiumLRS'</span><span class="sxs-lookup"><span data-stu-id="5bfba-118">Possible values include: 'StandardLRS', 'PremiumLRS'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.DataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bfba-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5bfba-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5bfba-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5bfba-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>