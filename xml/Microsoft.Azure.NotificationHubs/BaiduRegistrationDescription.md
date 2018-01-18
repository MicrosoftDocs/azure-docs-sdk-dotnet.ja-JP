<Type Name="BaiduRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription">
  <TypeSignature Language="C#" Value="public class BaiduRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaiduRegistrationDescription extends Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class BaiduRegistrationDescription&#xA;Inherits RegistrationDescription" />
  <TypeSignature Language="F#" Value="type BaiduRegistrationDescription = class&#xA;    inherit RegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="BaiduRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="93ac5-101">Baidu 登録の説明を表します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-101">Represents a Baidu registration description.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduRegistrationDescription (Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription : Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration"><span data-ttu-id="93ac5-102">ソースの登録。</span><span class="sxs-lookup"><span data-stu-id="93ac5-102">The source registration.</span></span></param>
        <summary>
            <span data-ttu-id="93ac5-103"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduRegistrationDescription (string pnsHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pnsHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pnsHandle As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription : string -&gt; Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription pnsHandle" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="93ac5-104">PNS が処理されます。</span><span class="sxs-lookup"><span data-stu-id="93ac5-104">The PNS handle.</span></span></param>
        <summary>
            <span data-ttu-id="93ac5-105"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="93ac5-106">BaiduUserId が null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="93ac5-106">Thrown when BaiduUserId is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduRegistrationDescription (string baiduUserId, string baiduChannelId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduUserId, string baiduChannelId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduUserId As String, baiduChannelId As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription : string * string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription (baiduUserId, baiduChannelId, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduUserId" Type="System.String" />
        <Parameter Name="baiduChannelId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="baiduUserId"><span data-ttu-id="93ac5-107">Baidu ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="93ac5-107">The Baidu user identifier.</span></span></param>
        <param name="baiduChannelId"><span data-ttu-id="93ac5-108">Baidu チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="93ac5-108">The Baidu channel identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="93ac5-109">タグ。</span><span class="sxs-lookup"><span data-stu-id="93ac5-109">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="93ac5-110"><see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduChannelId">
      <MemberSignature Language="C#" Value="public string BaiduChannelId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduChannelId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.BaiduChannelId" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduChannelId As String" />
      <MemberSignature Language="F#" Value="member this.BaiduChannelId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.BaiduChannelId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="BaiduChannelId", Order=2002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93ac5-111">取得または Baidu チャネル識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-111">Gets or sets the Baidu channel identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="93ac5-112">Baidu チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="93ac5-112">The Baidu channel identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduUserId">
      <MemberSignature Language="C#" Value="public string BaiduUserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduUserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.BaiduUserId" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduUserId As String" />
      <MemberSignature Language="F#" Value="member this.BaiduUserId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription.BaiduUserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="BaiduUserId", Order=2001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93ac5-113">取得または Baidu ユーザー識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="93ac5-113">Gets or sets the Baidu user identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="93ac5-114">Baidu ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="93ac5-114">The Baidu user identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>