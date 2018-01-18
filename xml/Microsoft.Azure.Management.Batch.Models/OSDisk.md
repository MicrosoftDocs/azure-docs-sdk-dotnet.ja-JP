<Type Name="OSDisk" FullName="Microsoft.Azure.Management.Batch.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
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
            <span data-ttu-id="4ad59-101">仮想マシンのオペレーティング システム ディスクの設定です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-101">Settings for the operating system disk of the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.OSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4ad59-102">OSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4ad59-102">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.OSDisk.#ctor(System.Nullable{Microsoft.Azure.Management.Batch.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional caching As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.OSDisk : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; -&gt; Microsoft.Azure.Management.Batch.Models.OSDisk" Usage="new Microsoft.Azure.Management.Batch.Models.OSDisk caching" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="caching"><span data-ttu-id="4ad59-103">データ ディスクに対して有効にするキャッシュの型。</span><span class="sxs-lookup"><span data-stu-id="4ad59-103">The type of caching to be enabled for the data disks.</span></span> <span data-ttu-id="4ad59-104">なし: ディスクのキャッシュ モードは無効です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-104">none - The caching mode for the disk is not enabled.</span></span>
            <span data-ttu-id="4ad59-105">読み取り専用のディスクのキャッシュ モードは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-105">readOnly - The caching mode for the disk is read only.</span></span> <span data-ttu-id="4ad59-106">readWrite のディスクのキャッシュ モードは読み書きします。</span><span class="sxs-lookup"><span data-stu-id="4ad59-106">readWrite - The caching mode for the disk is read and write.</span></span></param>
        <summary>
            <span data-ttu-id="4ad59-107">OSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4ad59-107">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.OSDisk.Caching" />
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
            <span data-ttu-id="4ad59-108">取得またはデータ ディスクに対して有効にするキャッシュの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="4ad59-108">Gets or sets the type of caching to be enabled for the data disks.</span></span>
            <span data-ttu-id="4ad59-109">なし: ディスクのキャッシュ モードは無効です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-109">none - The caching mode for the disk is not enabled.</span></span> <span data-ttu-id="4ad59-110">読み取り専用のディスクのキャッシュ モードは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-110">readOnly - The caching mode for the disk is read only.</span></span> <span data-ttu-id="4ad59-111">readWrite のディスクのキャッシュ モードは読み書きします。</span><span class="sxs-lookup"><span data-stu-id="4ad59-111">readWrite - The caching mode for the disk is read and write.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4ad59-112">既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="4ad59-112">Default value is none.</span></span> <span data-ttu-id="4ad59-113">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="4ad59-113">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>