<Type Name="BackupFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter">
  <TypeSignature Language="C#" Value="public class BackupFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupFilter" />
  <TypeSignature Language="F#" Value="type BackupFilter = class" />
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
            <span data-ttu-id="23e10-101">バックアップに使用する OData フィルター。</span><span class="sxs-lookup"><span data-stu-id="23e10-101">The OData filters to be used for backups.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23e10-102">BackupFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23e10-102">Initializes a new instance of the BackupFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupFilter (string backupPolicyId = null, string volumeId = null, Nullable&lt;DateTime&gt; createdTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupPolicyId, string volumeId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupPolicyId As String = null, Optional volumeId As String = null, Optional createdTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter (backupPolicyId, volumeId, createdTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupPolicyId" Type="System.String" />
        <Parameter Name="volumeId" Type="System.String" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="backupPolicyId"><span data-ttu-id="23e10-103">フィルター選択するのには、バックアップの backupPolicyId を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-103">Specifies the backupPolicyId of the backups to be filtered.</span></span> <span data-ttu-id="23e10-104">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23e10-104">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="volumeId"><span data-ttu-id="23e10-105">フィルター選択するのには、バックアップの volumeId を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-105">Specifies the volumeId of the backups to be filtered.</span></span> <span data-ttu-id="23e10-106">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23e10-106">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="createdTime"><span data-ttu-id="23e10-107">フィルター選択するのには、バックアップの作成時刻を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-107">Specifies the creation time of the backups to be filtered.</span></span> <span data-ttu-id="23e10-108">のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。</span><span class="sxs-lookup"><span data-stu-id="23e10-108">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="23e10-109">BackupFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23e10-109">Initializes a new instance of the BackupFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23e10-110">取得または設定は、フィルター選択するのには、バックアップの backupPolicyId を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-110">Gets or sets specifies the backupPolicyId of the backups to be filtered.</span></span> <span data-ttu-id="23e10-111">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23e10-111">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23e10-112">取得または設定は、フィルター選択するのには、バックアップの作成時刻を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-112">Gets or sets specifies the creation time of the backups to be filtered.</span></span> <span data-ttu-id="23e10-113">のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。</span><span class="sxs-lookup"><span data-stu-id="23e10-113">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeId">
      <MemberSignature Language="C#" Value="public string VolumeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter.VolumeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23e10-114">取得または設定は、フィルター選択するのには、バックアップの volumeId を指定します。</span><span class="sxs-lookup"><span data-stu-id="23e10-114">Gets or sets specifies the volumeId of the backups to be filtered.</span></span>
            <span data-ttu-id="23e10-115">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23e10-115">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>