<Type Name="SharedAccessSignatureToken" FullName="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureToken : Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureToken extends Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureToken&#xA;Inherits SimpleWebSecurityToken" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureToken = class&#xA;    inherit SimpleWebSecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3e1ff-101">共有アクセス署名トークンを表します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-101">Represents the shared access signature token.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken : string -&gt; Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" Usage="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken tokenString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="3e1ff-102">トークン文字列。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-102">The token string.</span></span></param>
        <summary><span data-ttu-id="3e1ff-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" />トークン文字列を指定しています。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" /> class with specified token string.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString, DateTime expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken : string * DateTime -&gt; Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" Usage="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken (tokenString, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="3e1ff-104">トークン文字列。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-104">The token string.</span></span></param>
        <param name="expiry"><span data-ttu-id="3e1ff-105">トークンの有効期限。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-105">The token expiry.</span></span></param>
        <summary><span data-ttu-id="3e1ff-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" />指定したトークン文字列と有効期限を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" /> class with specified token string and expiry.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string id, string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken : string * string -&gt; Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" Usage="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken (id, tokenString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3e1ff-107">トークンの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-107">The token identifier.</span></span></param>
        <param name="tokenString"><span data-ttu-id="3e1ff-108">トークン文字列。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-108">The token string.</span></span></param>
        <summary><span data-ttu-id="3e1ff-109">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" />クラスを指定した識別子とトークン文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" /> class with specified identifier and token string.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString, DateTime expiry, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.#ctor(System.String,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken : string * DateTime * string -&gt; Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" Usage="new Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken (tokenString, expiry, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="3e1ff-110">トークン文字列。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-110">The token string.</span></span></param>
        <param name="expiry"><span data-ttu-id="3e1ff-111">トークンの有効期限。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-111">The token expiry.</span></span></param>
        <param name="audience"><span data-ttu-id="3e1ff-112">トークンの対象ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-112">The token audience.</span></span></param>
        <summary><span data-ttu-id="3e1ff-113">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" />したトークン文字列の指定された、有効期限および対象ユーザー。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken" /> class with specified token string, expiry and audience.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AudienceFieldName">
      <MemberSignature Language="C#" Value="protected override string AudienceFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AudienceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.AudienceFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property AudienceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.AudienceFieldName : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.AudienceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-114">想定読者は、フィールド名を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-114">Gets the audience field name.</span></span></summary>
        <value><span data-ttu-id="3e1ff-115">対象のフィールド名。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-115">The audience field name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOnFieldName">
      <MemberSignature Language="C#" Value="protected override string ExpiresOnFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpiresOnFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.ExpiresOnFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property ExpiresOnFieldName As String" />
      <MemberSignature Language="F#" Value="member this.ExpiresOnFieldName : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.ExpiresOnFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-116">フィールド名の有効期限の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-116">Gets the value that expires on field name.</span></span></summary>
        <value><span data-ttu-id="3e1ff-117">この値はフィールド名の有効期限です。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-117">The value that expires on field name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueSeparator">
      <MemberSignature Language="C#" Value="protected override string KeyValueSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValueSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.KeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property KeyValueSeparator As String" />
      <MemberSignature Language="F#" Value="member this.KeyValueSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.KeyValueSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-118">キー値の区切り記号を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-118">Gets the key value separator.</span></span></summary>
        <value><span data-ttu-id="3e1ff-119">キーの値の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-119">The key value separator.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxKeyLength">
      <MemberSignature Language="C#" Value="public const int MaxKeyLength = 256;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxKeyLength = (256)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.MaxKeyLength" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxKeyLength As Integer  = 256" />
      <MemberSignature Language="F#" Value="val mutable MaxKeyLength : int" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.MaxKeyLength" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-120">キーの最大長を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-120">Specifies the maximum length of the key.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxKeyNameLength">
      <MemberSignature Language="C#" Value="public const int MaxKeyNameLength = 256;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxKeyNameLength = (256)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.MaxKeyNameLength" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxKeyNameLength As Integer  = 256" />
      <MemberSignature Language="F#" Value="val mutable MaxKeyNameLength : int" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.MaxKeyNameLength" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-121">キー名の最大長を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-121">Specifies the maximum length of the key name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairSeparator">
      <MemberSignature Language="C#" Value="protected override string PairSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PairSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.PairSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PairSeparator As String" />
      <MemberSignature Language="F#" Value="member this.PairSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.PairSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-122">トークンに関連付けられている組の区切り記号を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-122">Gets the pair separator associated with the token.</span></span></summary>
        <value><span data-ttu-id="3e1ff-123">トークンに関連付けられている組の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-123">The pair separator associated with the token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyValueSeparator">
      <MemberSignature Language="C#" Value="public const string SasKeyValueSeparator;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SasKeyValueSeparator" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SasKeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Const SasKeyValueSeparator As String " />
      <MemberSignature Language="F#" Value="val mutable SasKeyValueSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SasKeyValueSeparator" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-124">共有アクセス署名トークンのキー値の区切り記号を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-124">Specifies the key value separator for shared access signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasPairSeparator">
      <MemberSignature Language="C#" Value="public const string SasPairSeparator;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SasPairSeparator" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SasPairSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Const SasPairSeparator As String " />
      <MemberSignature Language="F#" Value="val mutable SasPairSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SasPairSeparator" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-125">共有アクセス署名トークンのペアの区切り記号を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-125">Specifies the pair separator for shared access signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public const string SharedAccessSignature;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Const SharedAccessSignature As String " />
      <MemberSignature Language="F#" Value="val mutable SharedAccessSignature : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SharedAccessSignature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-126">共有アクセス署名を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-126">Specifies the shared access signature.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Signature">
      <MemberSignature Language="C#" Value="public const string Signature;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Signature" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.Signature" />
      <MemberSignature Language="VB.NET" Value="Public Const Signature As String " />
      <MemberSignature Language="F#" Value="val mutable Signature : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.Signature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-127">署名トークンを指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-127">Specifies the signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedExpiry">
      <MemberSignature Language="C#" Value="public const string SignedExpiry;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedExpiry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedExpiry" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedExpiry As String " />
      <MemberSignature Language="F#" Value="val mutable SignedExpiry : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedExpiry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-128">トークンの署名の有効期限を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-128">Specifies the signed expiry of the token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedKeyName">
      <MemberSignature Language="C#" Value="public const string SignedKeyName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedKeyName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedKeyName As String " />
      <MemberSignature Language="F#" Value="val mutable SignedKeyName : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedKeyName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-129">符号付きのキーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-129">Specifies the signed key name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedResource">
      <MemberSignature Language="C#" Value="public const string SignedResource;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedResource" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedResource" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedResource As String " />
      <MemberSignature Language="F#" Value="val mutable SignedResource : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedResource" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-130">署名対象のリソースを指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-130">Specifies the signed resource.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedResourceFullFieldName">
      <MemberSignature Language="C#" Value="public const string SignedResourceFullFieldName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedResourceFullFieldName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedResourceFullFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedResourceFullFieldName As String " />
      <MemberSignature Language="F#" Value="val mutable SignedResourceFullFieldName : string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureToken.SignedResourceFullFieldName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3e1ff-131">署名対象のリソースのフル フィールド名を指定します。</span><span class="sxs-lookup"><span data-stu-id="3e1ff-131">Specifies the full field name of the signed resource.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>