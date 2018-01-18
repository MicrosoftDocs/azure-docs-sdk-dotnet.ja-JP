<Type Name="SimpleWebSecurityToken" FullName="Microsoft.ServiceBus.SimpleWebSecurityToken">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityToken : System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityToken extends System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityToken&#xA;Inherits SecurityToken" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityToken = class&#xA;    inherit SecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Tokens.SecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="64546-101">Simple Web Token をラップするセキュリティ トークンです。</span><span class="sxs-lookup"><span data-stu-id="64546-101">A security token that wraps a Simple Web Token.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken tokenString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="64546-102">Simple Web Token を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="64546-102">A string that represents the Simple Web Token.</span></span></param>
        <summary><span data-ttu-id="64546-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />指定された Simple Web Token を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="64546-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> class with the specified Simple Web Token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * DateTime -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (tokenString, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="64546-104">Simple Web Token を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="64546-104">A string that represents the Simple Web Token.</span></span></param>
        <param name="expiry"><span data-ttu-id="64546-105">単純な web トークンの有効期限日です。</span><span class="sxs-lookup"><span data-stu-id="64546-105">The expiry date of the simple web token.</span></span></param>
        <summary><span data-ttu-id="64546-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />指定 Simple Web Token や有効期限の日付を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="64546-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> class with the specified Simple Web Token and expiry date.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string id, string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (id, tokenString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="64546-107">単純な Web トークンの一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="64546-107">A unique identifier for the Simple Web Token.</span></span></param>
        <param name="tokenString"><span data-ttu-id="64546-108">Simple Web Token を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="64546-108">A string that represents the Simple Web Token.</span></span></param>
        <summary><span data-ttu-id="64546-109">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />トークン ID および Simple Web Token に指定したクラスです。</span><span class="sxs-lookup"><span data-stu-id="64546-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> class with the specified token ID and Simple Web Token.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NullReferenceException"><span data-ttu-id="64546-110"><paramref name="id" />パラメーターまたは<paramref name="tokenString" />パラメーターが null です。</span><span class="sxs-lookup"><span data-stu-id="64546-110">The <paramref name="id" /> parameter or <paramref name="tokenString" /> parameter is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * DateTime * string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (tokenString, expiry, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="64546-111">Simple Web Token を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="64546-111">A string that represents the Simple Web Token.</span></span></param>
        <param name="expiry"><span data-ttu-id="64546-112">単純な web トークンの有効期限日です。</span><span class="sxs-lookup"><span data-stu-id="64546-112">The expiry date of the simple web token.</span></span></param>
        <param name="audience"><span data-ttu-id="64546-113">単純な web トークンの対象ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="64546-113">The audience for the simple web token.</span></span></param>
        <summary><span data-ttu-id="64546-114"><see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="64546-114">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-115">単純な web トークンの対象ユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-115">Gets the audience for the simple web token.</span></span></summary>
        <value><span data-ttu-id="64546-116">単純な web トークンの対象ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="64546-116">The audience for the simple web token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AudienceFieldName">
      <MemberSignature Language="C#" Value="protected virtual string AudienceFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AudienceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property AudienceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.AudienceFieldName : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-117">想定読者は、フィールド名を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-117">Gets the audience field name.</span></span></summary>
        <value><span data-ttu-id="64546-118">対象のフィールド名。</span><span class="sxs-lookup"><span data-stu-id="64546-118">The audience field name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTime ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-119">セキュリティ トークンの有効期限が切れる日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-119">Gets the date and time the security token will expire.</span></span></summary>
        <value><span data-ttu-id="64546-120">日付と時間、セキュリティ トークンの有効期限が切れます。</span><span class="sxs-lookup"><span data-stu-id="64546-120">The date and time the security token will expire.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOnFieldName">
      <MemberSignature Language="C#" Value="protected virtual string ExpiresOnFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpiresOnFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property ExpiresOnFieldName As String" />
      <MemberSignature Language="F#" Value="member this.ExpiresOnFieldName : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-121">トークンの有効期限に関連付けられているフィールド名を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-121">Gets the field name associated with the token expiration.</span></span></summary>
        <value><span data-ttu-id="64546-122">トークンの有効期限に関連付けられているフィールド名です。</span><span class="sxs-lookup"><span data-stu-id="64546-122">The field name associated with the token expiration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-123">Simple Web Token に関連付けられている ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-123">Gets the ID associated with the Simple Web Token.</span></span></summary>
        <value><span data-ttu-id="64546-124">Simple Web Token に関連付けられている ID です。</span><span class="sxs-lookup"><span data-stu-id="64546-124">The ID associated with the Simple Web Token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueSeparator">
      <MemberSignature Language="C#" Value="protected virtual string KeyValueSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValueSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property KeyValueSeparator As String" />
      <MemberSignature Language="F#" Value="member this.KeyValueSeparator : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-125">トークンに関連付けられているキーの値の区切り記号を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-125">Gets the key value separator associated with the token.</span></span></summary>
        <value><span data-ttu-id="64546-126">トークンに関連付けられているキーの値の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="64546-126">The key value separator associated with the token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairSeparator">
      <MemberSignature Language="C#" Value="protected virtual string PairSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PairSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.PairSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property PairSeparator As String" />
      <MemberSignature Language="F#" Value="member this.PairSeparator : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.PairSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-127">トークンに関連付けられている組の区切り記号を取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-127">Gets the pair separator associated with the token.</span></span></summary>
        <value><span data-ttu-id="64546-128">トークンに関連付けられている組の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="64546-128">The pair separator associated with the token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityKeys">
      <MemberSignature Language="C#" Value="public override System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.SecurityKeys" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property SecurityKeys As ReadOnlyCollection(Of SecurityKey)" />
      <MemberSignature Language="F#" Value="member this.SecurityKeys : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.SecurityKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-129">セキュリティ トークンに関連付けられた暗号化キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-129">Gets the cryptographic keys associated with the security token.</span></span></summary>
        <value><span data-ttu-id="64546-130">A<see cref="T:System.Collections.ObjectModel.ReadOnlyCollection`1" />型の<see cref="T:System.IdentityModel.Tokens.SecurityKey" />Simple Web Token に関連付けられているキーのセットを格納しています。</span><span class="sxs-lookup"><span data-stu-id="64546-130">A <see cref="T:System.Collections.ObjectModel.ReadOnlyCollection`1" /> of type <see cref="T:System.IdentityModel.Tokens.SecurityKey" /> that contains the set of keys associated with the Simple Web Token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Token" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-131">単純な Web トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="64546-131">Gets the Simple Web Token.</span></span></summary>
        <value><span data-ttu-id="64546-132">単純な Web トークンです。</span><span class="sxs-lookup"><span data-stu-id="64546-132">The Simple Web Token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidFrom">
      <MemberSignature Language="C#" Value="public override DateTime ValidFrom { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ValidFrom" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidFrom As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidFrom : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ValidFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-133">実装されていません。</span><span class="sxs-lookup"><span data-stu-id="64546-133">Not implemented.</span></span> </summary>
        <value><span data-ttu-id="64546-134"><see cref="T:System.NotImplementedException" /> をスローします。</span><span class="sxs-lookup"><span data-stu-id="64546-134">Throws a <see cref="T:System.NotImplementedException" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidTo">
      <MemberSignature Language="C#" Value="public override DateTime ValidTo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ValidTo" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidTo As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidTo : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ValidTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="64546-135">実装されていません。</span><span class="sxs-lookup"><span data-stu-id="64546-135">Not implemented.</span></span></summary>
        <value><span data-ttu-id="64546-136"><see cref="T:System.NotImplementedException" /> をスローします。</span><span class="sxs-lookup"><span data-stu-id="64546-136">Throws a <see cref="T:System.NotImplementedException" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>