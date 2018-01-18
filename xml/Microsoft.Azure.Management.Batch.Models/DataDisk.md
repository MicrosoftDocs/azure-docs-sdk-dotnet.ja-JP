<Type Name="DataDisk" FullName="Microsoft.Azure.Management.Batch.Models.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71f0b-101">プール内のコンピューティング ノードに関連付けられているデータ ディスクで使用されるデータ ディスクの設定。</span><span class="sxs-lookup"><span data-stu-id="71f0b-101">Data Disk settings which will be used by the data disks associated to Compute Nodes in the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71f0b-102">DataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-102">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, int diskSizeGB, Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, int32 diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.#ctor(System.Int32,System.Int32,System.Nullable{Microsoft.Azure.Management.Batch.Models.CachingType},System.Nullable{Microsoft.Azure.Management.Batch.Models.StorageAccountType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, diskSizeGB As Integer, Optional caching As Nullable(Of CachingType) = null, Optional storageAccountType As Nullable(Of StorageAccountType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.DataDisk : int * int * Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; -&gt; Microsoft.Azure.Management.Batch.Models.DataDisk" Usage="new Microsoft.Azure.Management.Batch.Models.DataDisk (lun, diskSizeGB, caching, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="diskSizeGB" Type="System.Int32" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="71f0b-103">論理ユニットの数です。</span><span class="sxs-lookup"><span data-stu-id="71f0b-103">The logical unit number.</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="71f0b-104">最初のディスク サイズ GB 新しいデータ ディスクを作成するときにします。</span><span class="sxs-lookup"><span data-stu-id="71f0b-104">The initial disk size in GB when creating new data disk.</span></span></param>
        <param name="caching"><span data-ttu-id="71f0b-105">データ ディスクに対して有効にするキャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="71f0b-105">The type of caching to be enabled for the data disks.</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="71f0b-106">データ ディスクとして使用するストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="71f0b-106">The storage account type to be used for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="71f0b-107">DataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-107">Initializes a new instance of the DataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="71f0b-108">取得またはデータ ディスクに対して有効にするキャッシュの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-108">Gets or sets the type of caching to be enabled for the data disks.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="71f0b-109">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="71f0b-109">Values are:</span></span>
            
             <span data-ttu-id="71f0b-110">なし: ディスクのキャッシュ モードは無効です。</span><span class="sxs-lookup"><span data-stu-id="71f0b-110">none - The caching mode for the disk is not enabled.</span></span>
             <span data-ttu-id="71f0b-111">読み取り専用のディスクのキャッシュ モードは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="71f0b-111">readOnly - The caching mode for the disk is read only.</span></span>
             <span data-ttu-id="71f0b-112">readWrite のディスクのキャッシュ モードは読み書きします。</span><span class="sxs-lookup"><span data-stu-id="71f0b-112">readWrite - The caching mode for the disk is read and write.</span></span>
            
             <span data-ttu-id="71f0b-113">キャッシュの既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="71f0b-113">The default value for caching is none.</span></span> <span data-ttu-id="71f0b-114">キャッシュのオプションに関する情報を参照してください: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/です。</span><span class="sxs-lookup"><span data-stu-id="71f0b-114">For information about the caching options see: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span></span>
             <span data-ttu-id="71f0b-115">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="71f0b-115">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public int DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="71f0b-116">取得または新しいデータ ディスクを作成するときに、最初のディスク サイズを GB に設定します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-116">Gets or sets the initial disk size in GB when creating new data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="71f0b-117">取得または論理ユニット番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-117">Gets or sets the logical unit number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="71f0b-118">Lun を使用して、各データ ディスクを一意に識別します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-118">The lun is used to uniquely identify each data disk.</span></span> <span data-ttu-id="71f0b-119">複数のディスクをアタッチするには、それぞれが個別の lun を持ちます。</span><span class="sxs-lookup"><span data-stu-id="71f0b-119">If attaching multiple disks, each should have a distinct lun.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountType)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="71f0b-120">取得またはデータ ディスクを使用するストレージ アカウントの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-120">Gets or sets the storage account type to be used for the data disk.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="71f0b-121">省略した場合、既定値は"Standard_LRS"にします。</span><span class="sxs-lookup"><span data-stu-id="71f0b-121">If omitted, the default is "Standard_LRS".</span></span> <span data-ttu-id="71f0b-122">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="71f0b-122">Values are:</span></span>
            
             <span data-ttu-id="71f0b-123">Standard_LRS - データ ディスクは、標準のローカル冗長ストレージを使用してください。</span><span class="sxs-lookup"><span data-stu-id="71f0b-123">Standard_LRS - The data disk should use standard locally redundant storage.</span></span>
             <span data-ttu-id="71f0b-124">Premium_LRS - データ ディスクは、premium ローカル冗長ストレージを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="71f0b-124">Premium_LRS - The data disk should use premium locally redundant storage.</span></span> <span data-ttu-id="71f0b-125">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="71f0b-125">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71f0b-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="71f0b-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="71f0b-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71f0b-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>