<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a5117-101">暗号化の設定。</span><span class="sxs-lookup"><span data-stu-id="a5117-101">The encryption settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5117-102">EncryptionSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5117-102">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings (encryptionStatus, keyRolloverStatus, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptionStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus" />
        <Parameter Name="keyRolloverStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="encryptionStatus"><span data-ttu-id="a5117-103">かどうか暗号化が有効になっているかどうかを示す暗号化の状態。</span><span class="sxs-lookup"><span data-stu-id="a5117-103">The encryption status to indicates if encryption is enabled or not.</span></span> <span data-ttu-id="a5117-104">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="a5117-104">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="keyRolloverStatus"><span data-ttu-id="a5117-105">キーのロール オーバーが必要かどうかを示すキーのロール オーバーの状態。</span><span class="sxs-lookup"><span data-stu-id="a5117-105">The key rollover status to indicates if key rollover is required or not.</span></span> <span data-ttu-id="a5117-106">シークレットの暗号化をアップグレードした場合は、キー ロール オーバーが必要です。</span><span class="sxs-lookup"><span data-stu-id="a5117-106">If secret's encryption has been upgraded, then it requires key rollover.</span></span>
            <span data-ttu-id="a5117-107">使用可能な値が含まれます '必須'、'必要ありません'。</span><span class="sxs-lookup"><span data-stu-id="a5117-107">Possible values include: 'Required', 'NotRequired'</span></span></param>
        <param name="id"><span data-ttu-id="a5117-108">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="a5117-108">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="a5117-109">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="a5117-109">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="a5117-110">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="a5117-110">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="a5117-111">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="a5117-111">The Kind of the object.</span></span> <span data-ttu-id="a5117-112">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="a5117-112">Currently only Series8000 is supported.</span></span> <span data-ttu-id="a5117-113">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="a5117-113">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="a5117-114">EncryptionSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5117-114">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionStatus As EncryptionStatus" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5117-115">取得またはにして、暗号化が有効になっていない、または暗号化の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5117-115">Gets or sets the encryption status to indicates if encryption is enabled or not.</span></span> <span data-ttu-id="a5117-116">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="a5117-116">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyRolloverStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyRolloverStatus As KeyRolloverStatus" />
      <MemberSignature Language="F#" Value="member this.KeyRolloverStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyRolloverStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5117-117">取得またはキーのロール オーバーが必要かどうかを示しますにキー ロール オーバーの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5117-117">Gets or sets the key rollover status to indicates if key rollover is required or not.</span></span> <span data-ttu-id="a5117-118">シークレットの暗号化をアップグレードした場合は、キー ロール オーバーが必要です。</span><span class="sxs-lookup"><span data-stu-id="a5117-118">If secret's encryption has been upgraded, then it requires key rollover.</span></span> <span data-ttu-id="a5117-119">使用可能な値が含まれます '必須'、'必要ありません'。</span><span class="sxs-lookup"><span data-stu-id="a5117-119">Possible values include: 'Required', 'NotRequired'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
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
            <span data-ttu-id="a5117-120">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a5117-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a5117-121">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a5117-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>