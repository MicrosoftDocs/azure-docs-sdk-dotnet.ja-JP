<Type Name="BaiduTemplateRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription">
  <TypeSignature Language="C#" Value="public class BaiduTemplateRegistrationDescription : Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaiduTemplateRegistrationDescription extends Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class BaiduTemplateRegistrationDescription&#xA;Inherits BaiduRegistrationDescription" />
  <TypeSignature Language="F#" Value="type BaiduTemplateRegistrationDescription = class&#xA;    inherit BaiduRegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="BaiduTemplateRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fbd04-101">Baidu テンプレート登録の説明を表します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-101">Represents a Baidu template registration description.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduTemplateRegistrationDescription (Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription : Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration"><span data-ttu-id="fbd04-102">ソースの登録。</span><span class="sxs-lookup"><span data-stu-id="fbd04-102">The source registration.</span></span></param>
        <summary>
            <span data-ttu-id="fbd04-103"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduTemplateRegistrationDescription (string baiduUserId, string baiduChannelId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduUserId, string baiduChannelId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduUserId As String, baiduChannelId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription : string * string -&gt; Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription (baiduUserId, baiduChannelId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduUserId" Type="System.String" />
        <Parameter Name="baiduChannelId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baiduUserId"><span data-ttu-id="fbd04-104">Baidu ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-104">The baidu user identifier.</span></span></param>
        <param name="baiduChannelId"><span data-ttu-id="fbd04-105">Baidu チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-105">The baidu channel identifier.</span></span></param>
        <summary>
            <span data-ttu-id="fbd04-106"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduTemplateRegistrationDescription (string baiduUserId, string baiduChannelId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduUserId, string baiduChannelId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduUserId As String, baiduChannelId As String, jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription : string * string * string -&gt; Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription (baiduUserId, baiduChannelId, jsonPayload)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduUserId" Type="System.String" />
        <Parameter Name="baiduChannelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baiduUserId"><span data-ttu-id="fbd04-107">Baidu ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-107">The baidu user identifier.</span></span></param>
        <param name="baiduChannelId"><span data-ttu-id="fbd04-108">Baidu チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-108">The baidu channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="fbd04-109">Json ペイロード。</span><span class="sxs-lookup"><span data-stu-id="fbd04-109">The json payload.</span></span></param>
        <summary>
            <span data-ttu-id="fbd04-110"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduTemplateRegistrationDescription (string baiduUserId, string baiduChannelId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduUserId, string baiduChannelId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduUserId As String, baiduChannelId As String, jsonPayload As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription : string * string * string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription (baiduUserId, baiduChannelId, jsonPayload, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduUserId" Type="System.String" />
        <Parameter Name="baiduChannelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="baiduUserId"><span data-ttu-id="fbd04-111">Baidu ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-111">The baidu user identifier.</span></span></param>
        <param name="baiduChannelId"><span data-ttu-id="fbd04-112">Baidu チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="fbd04-112">The baidu channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="fbd04-113">Json ペイロード。</span><span class="sxs-lookup"><span data-stu-id="fbd04-113">The json payload.</span></span></param>
        <param name="tags"><span data-ttu-id="fbd04-114">タグ。</span><span class="sxs-lookup"><span data-stu-id="fbd04-114">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="fbd04-115"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BodyTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.CDataMember BodyTemplate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.CDataMember BodyTemplate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.BodyTemplate" />
      <MemberSignature Language="VB.NET" Value="Public Property BodyTemplate As CDataMember" />
      <MemberSignature Language="F#" Value="member this.BodyTemplate : Microsoft.Azure.NotificationHubs.CDataMember with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.BodyTemplate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="BodyTemplate", Order=3001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.CDataMember</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbd04-116">取得または本文テンプレートを設定します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-116">Gets or sets the body template.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fbd04-117">本文テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="fbd04-117">The body template.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateName">
      <MemberSignature Language="C#" Value="public string TemplateName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TemplateName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.TemplateName" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateName As String" />
      <MemberSignature Language="F#" Value="member this.TemplateName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription.TemplateName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="TemplateName", Order=3002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbd04-118">取得またはテンプレートの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="fbd04-118">Gets or sets the name of the template.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fbd04-119">テンプレートの名前。</span><span class="sxs-lookup"><span data-stu-id="fbd04-119">The name of the template.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>