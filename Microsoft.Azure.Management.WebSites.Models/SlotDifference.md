<Type Name="SlotDifference" FullName="Microsoft.Azure.Management.WebSites.Models.SlotDifference">
  <TypeSignature Language="C#" Value="public class SlotDifference : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SlotDifference extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SlotDifference" />
  <TypeSignature Language="VB.NET" Value="Public Class SlotDifference&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SlotDifference = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="74281-101">アプリの 2 つのデプロイ スロット間での設定の相違。</span><span class="sxs-lookup"><span data-stu-id="74281-101">A setting difference between two deployment slots of an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotDifference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotDifference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="74281-102">SlotDifference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74281-102">Initializes a new instance of the SlotDifference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotDifference (string id = null, string name = null, string kind = null, string type = null, string slotDifferenceType = null, string settingType = null, string diffRule = null, string settingName = null, string valueInCurrentSlot = null, string valueInTargetSlot = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string slotDifferenceType, string settingType, string diffRule, string settingName, string valueInCurrentSlot, string valueInTargetSlot, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotDifference.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional slotDifferenceType As String = null, Optional settingType As String = null, Optional diffRule As String = null, Optional settingName As String = null, Optional valueInCurrentSlot As String = null, Optional valueInTargetSlot As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SlotDifference : string * string * string * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.SlotDifference" Usage="new Microsoft.Azure.Management.WebSites.Models.SlotDifference (id, name, kind, type, slotDifferenceType, settingType, diffRule, settingName, valueInCurrentSlot, valueInTargetSlot, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="slotDifferenceType" Type="System.String" />
        <Parameter Name="settingType" Type="System.String" />
        <Parameter Name="diffRule" Type="System.String" />
        <Parameter Name="settingName" Type="System.String" />
        <Parameter Name="valueInCurrentSlot" Type="System.String" />
        <Parameter Name="valueInTargetSlot" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="74281-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="74281-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="74281-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="74281-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="74281-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="74281-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="74281-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="74281-106">Resource type.</span></span></param>
        <param name="slotDifferenceType"><span data-ttu-id="74281-107">相違点の種類: 情報、警告またはエラー。</span><span class="sxs-lookup"><span data-stu-id="74281-107">Type of the difference: Information, Warning or Error.</span></span></param>
        <param name="settingType"><span data-ttu-id="74281-108">設定の種類: 一般に、AppSetting または ConnectionString。</span><span class="sxs-lookup"><span data-stu-id="74281-108">The type of the setting: General, AppSetting or ConnectionString.</span></span></param>
        <param name="diffRule"><span data-ttu-id="74281-109">スロット スワップの間に設定の違いを処理する方法について説明するルール。</span><span class="sxs-lookup"><span data-stu-id="74281-109">Rule that describes how to process the setting difference during a slot swap.</span></span></param>
        <param name="settingName"><span data-ttu-id="74281-110">設定の名前。</span><span class="sxs-lookup"><span data-stu-id="74281-110">Name of the setting.</span></span></param>
        <param name="valueInCurrentSlot"><span data-ttu-id="74281-111">現在のスロットの設定の値です。</span><span class="sxs-lookup"><span data-stu-id="74281-111">Value of the setting in the current slot.</span></span></param>
        <param name="valueInTargetSlot"><span data-ttu-id="74281-112">ターゲット スロットの設定の値。</span><span class="sxs-lookup"><span data-stu-id="74281-112">Value of the setting in the target slot.</span></span></param>
        <param name="description"><span data-ttu-id="74281-113">設定の違いの説明です。</span><span class="sxs-lookup"><span data-stu-id="74281-113">Description of the setting difference.</span></span></param>
        <summary>
            <span data-ttu-id="74281-114">SlotDifference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74281-114">Initializes a new instance of the SlotDifference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-115">設定の違いの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="74281-115">Gets description of the setting difference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiffRule">
      <MemberSignature Language="C#" Value="public string DiffRule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DiffRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.DiffRule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiffRule As String" />
      <MemberSignature Language="F#" Value="member this.DiffRule : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.DiffRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diffRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-116">スロット スワップの間に設定の違いを処理する方法について説明するルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="74281-116">Gets rule that describes how to process the setting difference during a slot swap.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SettingName">
      <MemberSignature Language="C#" Value="public string SettingName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SettingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.SettingName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SettingName As String" />
      <MemberSignature Language="F#" Value="member this.SettingName : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.SettingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-117">設定の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="74281-117">Gets name of the setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SettingType">
      <MemberSignature Language="C#" Value="public string SettingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SettingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.SettingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SettingType As String" />
      <MemberSignature Language="F#" Value="member this.SettingType : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.SettingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settingType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-118">設定の種類を取得します。 一般に、AppSetting または ConnectionString。</span><span class="sxs-lookup"><span data-stu-id="74281-118">Gets the type of the setting: General, AppSetting or ConnectionString.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotDifferenceType">
      <MemberSignature Language="C#" Value="public string SlotDifferenceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SlotDifferenceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.SlotDifferenceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotDifferenceType As String" />
      <MemberSignature Language="F#" Value="member this.SlotDifferenceType : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.SlotDifferenceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-119">差の型を取得します。 情報、警告またはエラー。</span><span class="sxs-lookup"><span data-stu-id="74281-119">Gets type of the difference: Information, Warning or Error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueInCurrentSlot">
      <MemberSignature Language="C#" Value="public string ValueInCurrentSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValueInCurrentSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.ValueInCurrentSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueInCurrentSlot As String" />
      <MemberSignature Language="F#" Value="member this.ValueInCurrentSlot : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.ValueInCurrentSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.valueInCurrentSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-120">現在のスロットで、設定の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="74281-120">Gets value of the setting in the current slot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueInTargetSlot">
      <MemberSignature Language="C#" Value="public string ValueInTargetSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValueInTargetSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotDifference.ValueInTargetSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueInTargetSlot As String" />
      <MemberSignature Language="F#" Value="member this.ValueInTargetSlot : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotDifference.ValueInTargetSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.valueInTargetSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74281-121">ターゲット スロットの設定の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="74281-121">Gets value of the setting in the target slot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>