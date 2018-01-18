<Type Name="GcmCredential" FullName="Microsoft.Azure.NotificationHubs.GcmCredential">
  <TypeSignature Language="C#" Value="public class GcmCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GcmCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.GcmCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class GcmCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type GcmCredential = class&#xA;    inherit PnsCredential" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="GcmCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="39eae-101">Google Cloud Messaging 資格情報を表します。</span><span class="sxs-lookup"><span data-stu-id="39eae-101">Represents the Google Cloud Messaging credential.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="39eae-102"><see cref="T:Microsoft.Azure.NotificationHubs.GcmCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="39eae-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmCredential (string googleApiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string googleApiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmCredential.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (googleApiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmCredential : string -&gt; Microsoft.Azure.NotificationHubs.GcmCredential" Usage="new Microsoft.Azure.NotificationHubs.GcmCredential googleApiKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="googleApiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="googleApiKey"><span data-ttu-id="39eae-103">Google API キー。</span><span class="sxs-lookup"><span data-stu-id="39eae-103">The Google API key.</span></span></param>
        <summary><span data-ttu-id="39eae-104"><see cref="T:Microsoft.Azure.NotificationHubs.GcmCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="39eae-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="gcmCredential.Equals other" />
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
        <param name="other"><span data-ttu-id="39eae-105">比較する他方のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="39eae-105">The other object to compare.</span></span></param>
        <summary><span data-ttu-id="39eae-106">資格情報が特定のオブジェクトと等しいかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="39eae-106">Specifies whether the credential is equal with the specific object.</span></span></summary>
        <returns><span data-ttu-id="39eae-107">資格情報が、特定のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="39eae-107">true if the credential is equal with the specific object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmEndpoint">
      <MemberSignature Language="C#" Value="public string GcmEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GcmEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.GcmCredential.GcmEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.GcmEndpoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.GcmCredential.GcmEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39eae-108">取得または GCM エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="39eae-108">Gets or sets the GCM endpoint.</span></span></summary>
        <value><span data-ttu-id="39eae-109">GCM エンドポイントです。</span><span class="sxs-lookup"><span data-stu-id="39eae-109">The GCM endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="gcmCredential.GetHashCode " />
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
        <summary><span data-ttu-id="39eae-110">資格情報のハッシュ コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="39eae-110">Retrieves the hash code for the credentials.</span></span></summary>
        <returns><span data-ttu-id="39eae-111">資格情報のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="39eae-111">The hash code for the credentials.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleApiKey">
      <MemberSignature Language="C#" Value="public string GoogleApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.GcmCredential.GoogleApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleApiKey As String" />
      <MemberSignature Language="F#" Value="member this.GoogleApiKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.GcmCredential.GoogleApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39eae-112">取得または Google API キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="39eae-112">Gets or sets the Google API key.</span></span></summary>
        <value><span data-ttu-id="39eae-113">Google API キー。</span><span class="sxs-lookup"><span data-stu-id="39eae-113">The Google API key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="gcmCredential.OnValidate allowLocalMockPns" />
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
        <param name="allowLocalMockPns"><span data-ttu-id="39eae-114">ローカルのモック PNS; を許可する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="39eae-114">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="39eae-115">指定された資格情報を検証するには、呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="39eae-115">Called to validate the given credential.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>