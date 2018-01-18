<Type Name="WnsCredential" FullName="Microsoft.Azure.NotificationHubs.WnsCredential">
  <TypeSignature Language="C#" Value="public class WnsCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WnsCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class WnsCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type WnsCredential = class&#xA;    inherit PnsCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.PnsCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="WnsCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="65996-101">WNS 資格情報を表します。</span><span class="sxs-lookup"><span data-stu-id="65996-101">Represents a WNS credential.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="65996-102"><see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="65996-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential (string packageSid, string secretKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageSid, string secretKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (packageSid As String, secretKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WnsCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.WnsCredential" Usage="new Microsoft.Azure.NotificationHubs.WnsCredential (packageSid, secretKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageSid" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageSid"><span data-ttu-id="65996-103">パッケージの id。</span><span class="sxs-lookup"><span data-stu-id="65996-103">The package ID.</span></span></param>
        <param name="secretKey"><span data-ttu-id="65996-104">共有キー。</span><span class="sxs-lookup"><span data-stu-id="65996-104">The secret key.</span></span></param>
        <summary><span data-ttu-id="65996-105"><see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="65996-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="wnsCredential.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="65996-106">比較する他方のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="65996-106">The other object to compare.</span></span></param>
        <summary><span data-ttu-id="65996-107">かどうかこのインスタンスの os、指定したオブジェクトと同じかを指定します。</span><span class="sxs-lookup"><span data-stu-id="65996-107">Specifies whether this instance os the same as the specified object.</span></span></summary>
        <returns><span data-ttu-id="65996-108"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="65996-108">Returns <see cref="T:System.Boolean" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="wnsCredential.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="65996-109">資格情報のハッシュ コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="65996-109">Retrieves the hash code for the credentials.</span></span></summary>
        <returns><span data-ttu-id="65996-110">資格情報のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="65996-110">The hash code for the credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="wnsCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns"><span data-ttu-id="65996-111">ローカルのモック PNS; を許可する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="65996-111">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="65996-112">資格情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="65996-112">Validates the credential.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageSid">
      <MemberSignature Language="C#" Value="public string PackageSid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageSid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.PackageSid" />
      <MemberSignature Language="VB.NET" Value="Public Property PackageSid As String" />
      <MemberSignature Language="F#" Value="member this.PackageSid : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.PackageSid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="65996-113">取得または、この資格情報のパッケージ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="65996-113">Gets or sets the package ID for this credential.</span></span></summary>
        <value><span data-ttu-id="65996-114">この資格情報のパッケージ ID。</span><span class="sxs-lookup"><span data-stu-id="65996-114">The package ID for this credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public string SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As String" />
      <MemberSignature Language="F#" Value="member this.SecretKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="65996-115">取得または秘密キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="65996-115">Gets or sets the secret key.</span></span></summary>
        <value><span data-ttu-id="65996-116">共有キー。</span><span class="sxs-lookup"><span data-stu-id="65996-116">The secret key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsLiveEndpoint">
      <MemberSignature Language="C#" Value="public string WindowsLiveEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsLiveEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.WindowsLiveEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsLiveEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.WindowsLiveEndpoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.WindowsLiveEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="65996-117">取得または Windows Live エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="65996-117">Gets or sets the Windows Live endpoint.</span></span></summary>
        <value><span data-ttu-id="65996-118">Windows Live のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="65996-118">The Windows Live endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>