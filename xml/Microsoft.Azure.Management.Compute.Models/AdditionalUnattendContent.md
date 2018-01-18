<Type Name="AdditionalUnattendContent" FullName="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent">
  <TypeSignature Language="C#" Value="public class AdditionalUnattendContent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdditionalUnattendContent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent" />
  <TypeSignature Language="VB.NET" Value="Public Class AdditionalUnattendContent" />
  <TypeSignature Language="F#" Value="type AdditionalUnattendContent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a52ad-101">Windows セットアップで使用される、Unattend.xml ファイルに含めることができるその他の XML 形式の情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-101">Specifies additional XML formatted information that can be included in the Unattend.xml file, which is used by Windows Setup.</span></span> <span data-ttu-id="a52ad-102">内容は、名前、コンポーネント名、およびコンテンツが適用されているパスを設定して定義されます。</span><span class="sxs-lookup"><span data-stu-id="a52ad-102">Contents are defined by setting name, component name, and the pass in which the content is applied.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a52ad-103">AdditionalUnattendContent クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-103">Initializes a new instance of the AdditionalUnattendContent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent (Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; passName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; componentName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; settingName = null, string content = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.PassNames&gt; passName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; componentName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.SettingNames&gt; settingName, string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.PassNames},System.Nullable{Microsoft.Azure.Management.Compute.Models.ComponentNames},System.Nullable{Microsoft.Azure.Management.Compute.Models.SettingNames},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional passName As Nullable(Of PassNames) = null, Optional componentName As Nullable(Of ComponentNames) = null, Optional settingName As Nullable(Of SettingNames) = null, Optional content As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent : Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent" Usage="new Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent (passName, componentName, settingName, content)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="passName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt;" />
        <Parameter Name="componentName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt;" />
        <Parameter Name="settingName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt;" />
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="passName"><span data-ttu-id="a52ad-104">パスの名前。</span><span class="sxs-lookup"><span data-stu-id="a52ad-104">The pass name.</span></span> <span data-ttu-id="a52ad-105">現時点では、可能な値は、OobeSystem です。</span><span class="sxs-lookup"><span data-stu-id="a52ad-105">Currently, the only allowable value is OobeSystem.</span></span> <span data-ttu-id="a52ad-106">使用可能な値が含まれます: 'OobeSystem'</span><span class="sxs-lookup"><span data-stu-id="a52ad-106">Possible values include: 'OobeSystem'</span></span></param>
        <param name="componentName"><span data-ttu-id="a52ad-107">コンポーネントの名前。</span><span class="sxs-lookup"><span data-stu-id="a52ad-107">The component name.</span></span> <span data-ttu-id="a52ad-108">現時点では、可能な値は、Microsoft Windows シェル セットアップです。</span><span class="sxs-lookup"><span data-stu-id="a52ad-108">Currently, the only allowable value is Microsoft-Windows-Shell-Setup.</span></span> <span data-ttu-id="a52ad-109">使用可能な値が含まれます: ' Microsoft の Windows のシェルのセットアップ '</span><span class="sxs-lookup"><span data-stu-id="a52ad-109">Possible values include: 'Microsoft-Windows-Shell-Setup'</span></span></param>
        <param name="settingName"><span data-ttu-id="a52ad-110">設定の名前を指定するコンテンツが適用されます。</span><span class="sxs-lookup"><span data-stu-id="a52ad-110">Specifies the name of the setting to which the content applies.</span></span> <span data-ttu-id="a52ad-111">指定できる値は: FirstLogonCommands と AutoLogon。</span><span class="sxs-lookup"><span data-stu-id="a52ad-111">Possible values are: FirstLogonCommands and AutoLogon.</span></span> <span data-ttu-id="a52ad-112">使用可能な値が含まれます '自動'、'FirstLogonCommands'。</span><span class="sxs-lookup"><span data-stu-id="a52ad-112">Possible values include: 'AutoLogon', 'FirstLogonCommands'</span></span></param>
        <param name="content"><span data-ttu-id="a52ad-113">指定されたパスおよびコンポーネントの unattend.xml ファイルに追加される XML 形式のコンテンツを指定します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-113">Specifies the XML formatted content that is added to the unattend.xml file for the specified path and component.</span></span> <span data-ttu-id="a52ad-114">XML では、4 KB 未満である必要があり、設定または挿入している機能のルート要素を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="a52ad-114">The XML must be less than 4KB and must include the root element for the setting or feature that is being inserted.</span></span></param>
        <summary>
            <span data-ttu-id="a52ad-115">AdditionalUnattendContent クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-115">Initializes a new instance of the AdditionalUnattendContent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComponentName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; ComponentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; ComponentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.ComponentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComponentName As Nullable(Of ComponentNames)" />
      <MemberSignature Language="F#" Value="member this.ComponentName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.ComponentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="componentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ComponentNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a52ad-116">取得またはコンポーネントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-116">Gets or sets the component name.</span></span> <span data-ttu-id="a52ad-117">現時点では、可能な値は、Microsoft Windows シェル セットアップです。</span><span class="sxs-lookup"><span data-stu-id="a52ad-117">Currently, the only allowable value is Microsoft-Windows-Shell-Setup.</span></span> <span data-ttu-id="a52ad-118">使用可能な値が含まれます: ' Microsoft の Windows のシェルのセットアップ '</span><span class="sxs-lookup"><span data-stu-id="a52ad-118">Possible values include: 'Microsoft-Windows-Shell-Setup'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public string Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As String" />
      <MemberSignature Language="F#" Value="member this.Content : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a52ad-119">取得または設定は、指定されたパスおよびコンポーネントの unattend.xml ファイルに追加される XML 形式のコンテンツを指定します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-119">Gets or sets specifies the XML formatted content that is added to the unattend.xml file for the specified path and component.</span></span> <span data-ttu-id="a52ad-120">XML では、4 KB 未満である必要があり、設定または挿入している機能のルート要素を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="a52ad-120">The XML must be less than 4KB and must include the root element for the setting or feature that is being inserted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; PassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.PassNames&gt; PassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.PassName" />
      <MemberSignature Language="VB.NET" Value="Public Property PassName As Nullable(Of PassNames)" />
      <MemberSignature Language="F#" Value="member this.PassName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.PassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.PassNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a52ad-121">取得またはパスの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a52ad-121">Gets or sets the pass name.</span></span> <span data-ttu-id="a52ad-122">現時点では、可能な値は、OobeSystem です。</span><span class="sxs-lookup"><span data-stu-id="a52ad-122">Currently, the only allowable value is OobeSystem.</span></span> <span data-ttu-id="a52ad-123">使用可能な値が含まれます: 'OobeSystem'</span><span class="sxs-lookup"><span data-stu-id="a52ad-123">Possible values include: 'OobeSystem'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SettingName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; SettingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.SettingNames&gt; SettingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.SettingName" />
      <MemberSignature Language="VB.NET" Value="Public Property SettingName As Nullable(Of SettingNames)" />
      <MemberSignature Language="F#" Value="member this.SettingName : Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AdditionalUnattendContent.SettingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="settingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.SettingNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a52ad-124">取得または設定が、設定の名前を指定するコンテンツが適用されます。</span><span class="sxs-lookup"><span data-stu-id="a52ad-124">Gets or sets specifies the name of the setting to which the content applies.</span></span> <span data-ttu-id="a52ad-125">指定できる値は: FirstLogonCommands と AutoLogon。</span><span class="sxs-lookup"><span data-stu-id="a52ad-125">Possible values are: FirstLogonCommands and AutoLogon.</span></span>
            <span data-ttu-id="a52ad-126">使用可能な値が含まれます '自動'、'FirstLogonCommands'。</span><span class="sxs-lookup"><span data-stu-id="a52ad-126">Possible values include: 'AutoLogon', 'FirstLogonCommands'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>