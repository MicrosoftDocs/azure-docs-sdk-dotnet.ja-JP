<Type Name="AvailableProviderOperation" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation">
  <TypeSignature Language="C#" Value="public class AvailableProviderOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProviderOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProviderOperation" />
  <TypeSignature Language="F#" Value="type AvailableProviderOperation = class" />
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
            <span data-ttu-id="6ea1d-101">使用可能なプロバイダーの操作を表します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-101">Represents available provider operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6ea1d-102">AvailableProviderOperation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-102">Initializes a new instance of the AvailableProviderOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperation (string name = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay display = null, string origin = null, object properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay display, string origin, object properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As AvailableProviderOperationDisplay = null, Optional origin As String = null, Optional properties As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay * string * obj -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation (name, display, origin, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="properties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6ea1d-103">特定のオブジェクトで実行される操作の名前。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-103">The name of the operation being performed on a particular object.</span></span> <span data-ttu-id="6ea1d-104">名の形式:"{resourceProviderNamespace}/{resourceType}/{読み取り | 書き込み | を削除 | アクション}"。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-104">Name format: "{resourceProviderNamespace}/{resourceType}/{read|write|delete|action}".</span></span>
            <span data-ttu-id="6ea1d-105">例:</span><span class="sxs-lookup"><span data-stu-id="6ea1d-105">Eg.</span></span> <span data-ttu-id="6ea1d-106">Microsoft.StorSimple/managers/devices/volumeContainers/read、Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action</span><span class="sxs-lookup"><span data-stu-id="6ea1d-106">Microsoft.StorSimple/managers/devices/volumeContainers/read, Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action</span></span></param>
        <param name="display"><span data-ttu-id="6ea1d-107">この特定の操作/アクションのローカライズされた表示情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-107">Contains the localized display information for this particular operation/action.</span></span></param>
        <param name="origin"><span data-ttu-id="6ea1d-108">操作の目的の実行子RBAC UX およびエクスペリエンスは、監査ログで、操作の表示を制御します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-108">The intended executor of the operation; governs the display of the operation in the RBAC UX and the audit logs UX.</span></span> <span data-ttu-id="6ea1d-109">既定値は「ユーザー、システム」</span><span class="sxs-lookup"><span data-stu-id="6ea1d-109">Default value is "user,system"</span></span></param>
        <param name="properties"><span data-ttu-id="6ea1d-110">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-110">Reserved for future use.</span></span></param>
        <summary>
            <span data-ttu-id="6ea1d-111">AvailableProviderOperation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-111">Initializes a new instance of the AvailableProviderOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As AvailableProviderOperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ea1d-112">取得または設定には、この特定の操作/アクションのローカライズされた表示情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-112">Gets or sets contains the localized display information for this particular operation/action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ea1d-113">取得または特定のオブジェクトで実行される操作の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-113">Gets or sets the name of the operation being performed on a particular object.</span></span> <span data-ttu-id="6ea1d-114">名の形式:"{resourceProviderNamespace}/{resourceType}/{読み取り | 書き込み | を削除 | アクション}"。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-114">Name format: "{resourceProviderNamespace}/{resourceType}/{read|write|delete|action}".</span></span>
            <span data-ttu-id="6ea1d-115">例:</span><span class="sxs-lookup"><span data-stu-id="6ea1d-115">Eg.</span></span> <span data-ttu-id="6ea1d-116">Microsoft.StorSimple/managers/devices/volumeContainers/read、Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action</span><span class="sxs-lookup"><span data-stu-id="6ea1d-116">Microsoft.StorSimple/managers/devices/volumeContainers/read, Microsoft.StorSimple/managers/devices/alerts/clearAlerts/action</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ea1d-117">取得または設定操作の目的の実行子RBAC UX およびエクスペリエンスは、監査ログで、操作の表示を制御します。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-117">Gets or sets the intended executor of the operation; governs the display of the operation in the RBAC UX and the audit logs UX.</span></span>
            <span data-ttu-id="6ea1d-118">既定値は「ユーザー、システム」</span><span class="sxs-lookup"><span data-stu-id="6ea1d-118">Default value is "user,system"</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ea1d-119">取得または設定将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="6ea1d-119">Gets or sets reserved for future use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>