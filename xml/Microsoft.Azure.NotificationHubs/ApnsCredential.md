<Type Name="ApnsCredential" FullName="Microsoft.Azure.NotificationHubs.ApnsCredential">
  <TypeSignature Language="C#" Value="public class ApnsCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApnsCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ApnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class ApnsCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type ApnsCredential = class&#xA;    inherit PnsCredential" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ApnsCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="23075-101">Apple Push Notification サービス (APNS) の資格情報を表します。</span><span class="sxs-lookup"><span data-stu-id="23075-101">Represents an Apple Push Notification Service (APNS) credential.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="23075-102"><see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23075-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApnsCredential (byte[] certificateBuffer, string certificateKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] certificateBuffer, string certificateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.#ctor(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificateBuffer As Byte(), certificateKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.ApnsCredential : byte[] * string -&gt; Microsoft.Azure.NotificationHubs.ApnsCredential" Usage="new Microsoft.Azure.NotificationHubs.ApnsCredential (certificateBuffer, certificateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateBuffer" Type="System.Byte[]" />
        <Parameter Name="certificateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateBuffer"><span data-ttu-id="23075-103">証明書のバッファー。</span><span class="sxs-lookup"><span data-stu-id="23075-103">The certificate buffer.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="23075-104">証明書のキー。</span><span class="sxs-lookup"><span data-stu-id="23075-104">The certificated key.</span></span></param>
        <summary><span data-ttu-id="23075-105"><see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23075-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApnsCredential (string certificatePath, string certificateKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificatePath, string certificateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificatePath As String, certificateKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.ApnsCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.ApnsCredential" Usage="new Microsoft.Azure.NotificationHubs.ApnsCredential (certificatePath, certificateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificatePath" Type="System.String" />
        <Parameter Name="certificateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificatePath"><span data-ttu-id="23075-106">証明書のパス。</span><span class="sxs-lookup"><span data-stu-id="23075-106">The certificate path.</span></span></param>
        <param name="certificateKey"><span data-ttu-id="23075-107">証明書のキー。</span><span class="sxs-lookup"><span data-stu-id="23075-107">The certificate key.</span></span></param>
        <summary><span data-ttu-id="23075-108"><see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23075-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ApnsCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCertificate">
      <MemberSignature Language="C#" Value="public string ApnsCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApnsCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ApnsCredential.ApnsCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCertificate As String" />
      <MemberSignature Language="F#" Value="member this.ApnsCertificate : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ApnsCredential.ApnsCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="23075-109">取得または APNS 証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="23075-109">Gets or sets the APNS certificate.</span></span></summary>
        <value><span data-ttu-id="23075-110">APNS 証明書。</span><span class="sxs-lookup"><span data-stu-id="23075-110">The APNS certificate.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateKey">
      <MemberSignature Language="C#" Value="public string CertificateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ApnsCredential.CertificateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateKey As String" />
      <MemberSignature Language="F#" Value="member this.CertificateKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ApnsCredential.CertificateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="23075-111">取得または証明書のキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="23075-111">Gets or sets the certificate key.</span></span></summary>
        <value><span data-ttu-id="23075-112">証明書のキー。</span><span class="sxs-lookup"><span data-stu-id="23075-112">The certificate key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ApnsCredential.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ApnsCredential.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="23075-113">取得または、この資格情報のエンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="23075-113">Gets or sets the endpoint of this credential.</span></span></summary>
        <value><span data-ttu-id="23075-114">この資格情報のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="23075-114">The endpoint of this credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="apnsCredential.Equals other" />
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
        <param name="other"><span data-ttu-id="23075-115">比較する他方のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23075-115">The other object to compare.</span></span></param>
        <summary><span data-ttu-id="23075-116">資格情報が特定のオブジェクトと同じかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="23075-116">Specifies whether the credential is the same as the specific object.</span></span></summary>
        <returns><span data-ttu-id="23075-117">資格情報は、特定のオブジェクトと同じ場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="23075-117">true if the credential is the same as the specific object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="apnsCredential.GetHashCode " />
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
        <summary><span data-ttu-id="23075-118">資格情報のハッシュ コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="23075-118">Retrieves the hash code for the credentials.</span></span></summary>
        <returns><span data-ttu-id="23075-119">資格情報のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="23075-119">The hash code for the credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ApnsCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="apnsCredential.OnValidate allowLocalMockPns" />
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
        <param name="allowLocalMockPns"><span data-ttu-id="23075-120">ローカルのモック PNS; を許可する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="23075-120">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="23075-121">APNS 資格情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="23075-121">Validates the APNS credential.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>