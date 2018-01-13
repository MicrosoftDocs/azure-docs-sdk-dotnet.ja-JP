<Type Name="ImageOSDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk">
  <TypeSignature Language="C#" Value="public class ImageOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageOSDisk" />
  <TypeSignature Language="F#" Value="type ImageOSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b490d-101">オペレーティング システム ディスクをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="b490d-101">Describes an Operating System disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b490d-102">ImageOSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b490d-102">Initializes a new instance of the ImageOSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk (Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource snapshot = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource managedDisk = null, string blobUri = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource snapshot, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource managedDisk, string blobUri, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osType As OperatingSystemTypes, osState As OperatingSystemStateTypes, Optional snapshot As SubResource = null, Optional managedDisk As SubResource = null, Optional blobUri As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk (osType, osState, snapshot, managedDisk, blobUri, caching, diskSizeGB, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="osType">To be added.</param>
        <param name="osState">To be added.</param>
        <param name="snapshot">To be added.</param>
        <param name="managedDisk">To be added.</param>
        <param name="blobUri">To be added.</param>
        <param name="caching">To be added.</param>
        <param name="diskSizeGB">To be added.</param>
        <param name="storageAccountType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.BlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-103">取得またはバーチャル ハード_ディスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-103">Gets or sets the Virtual Hard Disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-104">取得またはキャッシュの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-104">Gets or sets the caching type.</span></span> <span data-ttu-id="b490d-105">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="b490d-105">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-106">取得または空のデータ ディスクの場合は、GB、最初の管理対象ディスク サイズと既存の OS とデータ ディスクの新しいサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-106">Gets or sets the initial managed disk size in GB for blank data disks, and the new desired size for existing OS and Data disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As SubResource" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-107">取得または、managedDisk を設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-107">Gets or sets the managedDisk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes OsState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes OsState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.OsState" />
      <MemberSignature Language="VB.NET" Value="Public Property OsState As OperatingSystemStateTypes" />
      <MemberSignature Language="F#" Value="member this.OsState : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.OsState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-108">取得または OS の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-108">Gets or sets the OS State.</span></span> <span data-ttu-id="b490d-109">使用可能な値が含まれます: '汎用'、'特殊化'</span><span class="sxs-lookup"><span data-stu-id="b490d-109">Possible values include: 'Generalized', 'Specialized'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OsType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-110">取得またはオペレーティング システムの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-110">Gets or sets the Operating System type.</span></span> <span data-ttu-id="b490d-111">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="b490d-111">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Snapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Snapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property Snapshot As SubResource" />
      <MemberSignature Language="F#" Value="member this.Snapshot : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.Snapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="snapshot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b490d-112">取得またはスナップショットを設定します。</span><span class="sxs-lookup"><span data-stu-id="b490d-112">Gets or sets the snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageOSDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b490d-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b490d-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b490d-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b490d-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>