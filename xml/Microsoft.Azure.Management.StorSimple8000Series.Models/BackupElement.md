<Type Name="BackupElement" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement">
  <TypeSignature Language="C#" Value="public class BackupElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupElement extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupElement" />
  <TypeSignature Language="F#" Value="type BackupElement = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b688-101">バックアップ要素。</span><span class="sxs-lookup"><span data-stu-id="1b688-101">The backup element.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b688-102">BackupElement クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b688-102">Initializes a new instance of the BackupElement class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupElement (string elementId, string elementName, string elementType, long sizeInBytes, string volumeName, string volumeContainerId, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; volumeType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string elementId, string elementName, string elementType, int64 sizeInBytes, string volumeName, string volumeContainerId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; volumeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.#ctor(System.String,System.String,System.String,System.Int64,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (elementId As String, elementName As String, elementType As String, sizeInBytes As Long, volumeName As String, volumeContainerId As String, Optional volumeType As Nullable(Of VolumeType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement : string * string * string * int64 * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement (elementId, elementName, elementType, sizeInBytes, volumeName, volumeContainerId, volumeType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementId" Type="System.String" />
        <Parameter Name="elementName" Type="System.String" />
        <Parameter Name="elementType" Type="System.String" />
        <Parameter Name="sizeInBytes" Type="System.Int64" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="volumeContainerId" Type="System.String" />
        <Parameter Name="volumeType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt;" />
      </Parameters>
      <Docs>
        <param name="elementId"><span data-ttu-id="1b688-103">Backup 要素を一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="1b688-103">The path ID that uniquely identifies the backup element.</span></span></param>
        <param name="elementName"><span data-ttu-id="1b688-104">Backup 要素の名前。</span><span class="sxs-lookup"><span data-stu-id="1b688-104">The name of the backup element.</span></span></param>
        <param name="elementType"><span data-ttu-id="1b688-105">バックアップの要素の階層型。</span><span class="sxs-lookup"><span data-stu-id="1b688-105">The hierarchical type of the backup element.</span></span></param>
        <param name="sizeInBytes"><span data-ttu-id="1b688-106">サイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="1b688-106">The size in bytes.</span></span></param>
        <param name="volumeName"><span data-ttu-id="1b688-107">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="1b688-107">The name of the volume.</span></span></param>
        <param name="volumeContainerId"><span data-ttu-id="1b688-108">ボリューム コンテナーのパス ID。</span><span class="sxs-lookup"><span data-stu-id="1b688-108">The path ID of the volume container.</span></span></param>
        <param name="volumeType"><span data-ttu-id="1b688-109">ボリュームの種類。</span><span class="sxs-lookup"><span data-stu-id="1b688-109">The volume type.</span></span> <span data-ttu-id="1b688-110">使用可能な値が含まれます: '階層型'、'アーカイブ'、'LocallyPinned'</span><span class="sxs-lookup"><span data-stu-id="1b688-110">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span></param>
        <summary>
            <span data-ttu-id="1b688-111">BackupElement クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b688-111">Initializes a new instance of the BackupElement class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementId">
      <MemberSignature Language="C#" Value="public string ElementId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElementId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementId" />
      <MemberSignature Language="VB.NET" Value="Public Property ElementId As String" />
      <MemberSignature Language="F#" Value="member this.ElementId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elementId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-112">取得またはバックアップの要素を一意に識別するパス ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-112">Gets or sets the path ID that uniquely identifies the backup element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementName">
      <MemberSignature Language="C#" Value="public string ElementName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElementName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElementName As String" />
      <MemberSignature Language="F#" Value="member this.ElementName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elementName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-113">取得またはバックアップの要素の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-113">Gets or sets the name of the backup element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementType">
      <MemberSignature Language="C#" Value="public string ElementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementType" />
      <MemberSignature Language="VB.NET" Value="Public Property ElementType As String" />
      <MemberSignature Language="F#" Value="member this.ElementType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.ElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-114">取得またはバックアップの要素の階層の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-114">Gets or sets the hierarchical type of the backup element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-115">取得またはサイズをバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-115">Gets or sets the size in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupElement.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b688-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1b688-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1b688-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1b688-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainerId">
      <MemberSignature Language="C#" Value="public string VolumeContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainerId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeContainerId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeContainerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-118">取得またはボリューム コンテナーのパス ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-118">Gets or sets the path ID of the volume container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeName">
      <MemberSignature Language="C#" Value="public string VolumeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeName" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeName As String" />
      <MemberSignature Language="F#" Value="member this.VolumeName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-119">取得またはボリュームの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-119">Gets or sets the name of the volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; VolumeType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; VolumeType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeType" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeType As Nullable(Of VolumeType)" />
      <MemberSignature Language="F#" Value="member this.VolumeType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement.VolumeType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b688-120">取得またはボリュームの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b688-120">Gets or sets the volume type.</span></span> <span data-ttu-id="1b688-121">使用可能な値が含まれます: '階層型'、'アーカイブ'、'LocallyPinned'</span><span class="sxs-lookup"><span data-stu-id="1b688-121">Possible values include: 'Tiered', 'Archival', 'LocallyPinned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>