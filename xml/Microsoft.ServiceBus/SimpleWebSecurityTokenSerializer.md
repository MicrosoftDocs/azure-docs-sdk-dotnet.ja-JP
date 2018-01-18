<Type Name="SimpleWebSecurityTokenSerializer" FullName="Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityTokenSerializer extends System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityTokenSerializer&#xA;Inherits SecurityTokenSerializer" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityTokenSerializer = class&#xA;    inherit SecurityTokenSerializer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Selectors.SecurityTokenSerializer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="67dfd-101">読み取りおよび書き込みを使用するクラスを表します<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />、 <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />、および<see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />オブジェクトを XML として。</span><span class="sxs-lookup"><span data-stu-id="67dfd-101">Represents a class to use to read and to write <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />, <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />, and <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> objects as XML.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="67dfd-102"><see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer (System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.#ctor(System.IdentityModel.Selectors.SecurityTokenSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerSerializer As SecurityTokenSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer -&gt; Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" Usage="new Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer innerSerializer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerSerializer" Type="System.IdentityModel.Selectors.SecurityTokenSerializer" />
      </Parameters>
      <Docs>
        <param name="innerSerializer"><span data-ttu-id="67dfd-103">ために SecurityTokenSerializer をラップします。</span><span class="sxs-lookup"><span data-stu-id="67dfd-103">A SecurityTokenSerializer to wrap.</span></span> <span data-ttu-id="67dfd-104">既定の WCF シリアライザー通常</span><span class="sxs-lookup"><span data-stu-id="67dfd-104">Typically the default WCF serializer</span></span></param>
        <summary>
            <span data-ttu-id="67dfd-105">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="67dfd-105">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierClauseCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="67dfd-106">キー識別句を読み取る <see cref="T:System.Xml.XmlReader" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-106">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier clause.</span></span></param>
        <summary><span data-ttu-id="67dfd-107">このシリアライザ-が読み取ることができるかどうかを判断、 &lt;KeyIdentifier&gt;要素が指定した XML リーダーで参照します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-107">Determines whether this serializer can read the &lt;KeyIdentifier&gt; element referred  by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-108">true が指定された&lt;KeyIdentifier&gt;要素を読み取り、それ以外の場合は false にすることができます。</span><span class="sxs-lookup"><span data-stu-id="67dfd-108">true when the specified &lt;KeyIdentifier&gt; element can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="67dfd-109">キー識別子を読み取る <see cref="T:System.Xml.XmlReader" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-109">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier.</span></span></param>
        <summary><span data-ttu-id="67dfd-110">このシリアライザ-が読み取ることができるかどうかを判断、 &lt;KeyIdentifier&gt;要素が指定した XML リーダーで参照します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-110">Determines whether this serializer can read the &lt;KeyIdentifier&gt; element referred  by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-111">true が指定された&lt;KeyIdentifier&gt;要素を読み取り、それ以外の場合は false にすることができます。</span><span class="sxs-lookup"><span data-stu-id="67dfd-111">true when the specified &lt;KeyIdentifier&gt; element can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadTokenCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadTokenCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanReadTokenCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadTokenCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadTokenCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadTokenCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="67dfd-112">セキュリティ トークンを読み取る <see cref="T:System.Xml.XmlReader" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-112">An <see cref="T:System.Xml.XmlReader" /> to read the security token.</span></span></param>
        <summary><span data-ttu-id="67dfd-113">このシリアライザーが指定された XML リーダーで参照されているセキュリティ トークンを読み取ることができるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-113">Determines whether this serializer can read the security token pointed at by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-114">true のとき、セキュリティ トークンを読み取ることができます。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="67dfd-114">true when the security token can be read; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierClauseCore (System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierClauseCore(class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore(System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierClauseCore (keyIdentifierClause As SecurityKeyIdentifierClause) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierClauseCore : System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore keyIdentifierClause" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="keyIdentifierClause"> <span data-ttu-id="67dfd-115">書き込むキー識別句を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-115">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier clause to write.</span></span></param>
        <summary><span data-ttu-id="67dfd-116">このシリアライザーが指定のキー識別句を書き込むことができるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-116">Determines whether this serializer can write the specified key identifier clause.</span></span></summary>
        <returns><span data-ttu-id="67dfd-117">このシリアライザーが指定したキー識別子句を書き込む場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="67dfd-117">true when this serializer can write the specified key identifier clause; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierCore (System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierCore(class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore(System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierCore (keyIdentifier As SecurityKeyIdentifier) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierCore : System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore keyIdentifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="keyIdentifier"> <span data-ttu-id="67dfd-118">書き込むキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-118">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier to write.</span></span></param>
        <summary><span data-ttu-id="67dfd-119">このシリアライザーが指定のキー ID を書き込むことができるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-119">Determines whether this serializer can write the specified key identifier.</span></span></summary>
        <returns><span data-ttu-id="67dfd-120">このシリアライザーが指定したキー識別子を書き込む場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="67dfd-120">true when this serializer can write the specified key identifier; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteTokenCore (System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteTokenCore(class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.CanWriteTokenCore(System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteTokenCore (token As SecurityToken) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteTokenCore : System.IdentityModel.Tokens.SecurityToken -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteTokenCore token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="token"> <span data-ttu-id="67dfd-121">XML に変換する <see cref="T:System.IdentityModel.Tokens.SecurityToken" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-121">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> to convert to XML.</span></span></param>
        <summary><span data-ttu-id="67dfd-122">このシリアライザーが指定のセキュリティ トークンを XML に書き込むことができるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-122">Determines whether this serializer can write the specified security token to XML.</span></span></summary>
        <returns><span data-ttu-id="67dfd-123">セキュリティ トークンを書き込むことができます。 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="67dfd-123">true when the security token can be written; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultInstance">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer DefaultInstance;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer DefaultInstance" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultInstance As SimpleWebSecurityTokenSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultInstance : Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" Usage="Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="67dfd-124">インスタンスを指定します、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="67dfd-124">Specifies an instance of the<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierClauseCore (reader As XmlReader) As SecurityKeyIdentifierClause" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifierClause" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifierClause</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="67dfd-125">キー識別句を読み取る <see cref="T:System.Xml.XmlReader" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-125">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier clause.</span></span></param>
        <summary><span data-ttu-id="67dfd-126">指定した XML リーダーを使用してキー識別子句を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="67dfd-126">Reads the key identifier clause using the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-127">読み取るキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-127">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier that is read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierCore (reader As XmlReader) As SecurityKeyIdentifier" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifier" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="67dfd-128">キー識別子を読み取る <see cref="T:System.Xml.XmlReader" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-128">An <see cref="T:System.Xml.XmlReader" /> to read the key identifier.</span></span></param>
        <summary><span data-ttu-id="67dfd-129">指定した XML リーダーを使用してキー識別子を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="67dfd-129">Reads the key identifier using the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-130">読み取るキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-130">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier that is read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTokenCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken ReadTokenCore (System.Xml.XmlReader reader, System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken ReadTokenCore(class System.Xml.XmlReader reader, class System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.ReadTokenCore(System.Xml.XmlReader,System.IdentityModel.Selectors.SecurityTokenResolver)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadTokenCore (reader As XmlReader, tokenResolver As SecurityTokenResolver) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.ReadTokenCore : System.Xml.XmlReader * System.IdentityModel.Selectors.SecurityTokenResolver -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="simpleWebSecurityTokenSerializer.ReadTokenCore (reader, tokenResolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
        <Parameter Name="tokenResolver" Type="System.IdentityModel.Selectors.SecurityTokenResolver" />
      </Parameters>
      <Docs>
        <param name="reader"> <span data-ttu-id="67dfd-131"><see cref="T:System.Xml.XmlReader" /> SimpleWebSecurityToken またはセキュリティ トークンを読み取る。</span><span class="sxs-lookup"><span data-stu-id="67dfd-131">An <see cref="T:System.Xml.XmlReader" /> to read the SimpleWebSecurityToken or the security token.</span></span></param>
        <param name="tokenResolver"> <span data-ttu-id="67dfd-132">セキュリティ トークンの種類を指定する <see cref="T:System.IdentityModel.Selectors.SecurityTokenResolver" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-132">A <see cref="T:System.IdentityModel.Selectors.SecurityTokenResolver" /> that determines the security token type.</span></span></param>
        <summary><span data-ttu-id="67dfd-133">読み取り、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />セキュリティ トークンが指定された XML リーダーで参照されているか。</span><span class="sxs-lookup"><span data-stu-id="67dfd-133">Reads the<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> or the security token pointed at by the specified XML reader.</span></span></summary>
        <returns><span data-ttu-id="67dfd-134">A<see cref="T:System.IdentityModel.Tokens.SecurityToken" /> SimpleWebSecurityToken または読み取られたセキュリティ トークンを表すです。</span><span class="sxs-lookup"><span data-stu-id="67dfd-134">A<see cref="T:System.IdentityModel.Tokens.SecurityToken" /> that represents the SimpleWebSecurityToken or the security token that is read.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException"> <span data-ttu-id="67dfd-135">XML 要素のエンコードは、base64Binary ではありません。</span><span class="sxs-lookup"><span data-stu-id="67dfd-135">The encoding of the XML element is not base64Binary.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierClauseCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierClauseCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierClauseCore (writer As XmlWriter, keyIdentifierClause As SecurityKeyIdentifierClause)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierClauseCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore (writer, keyIdentifierClause)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="67dfd-136"><see cref="T:System.Xml.XmlWriter" />キー識別子句を書き込むために使用します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-136">An <see cref="T:System.Xml.XmlWriter" /> used to write the key identifier clause.</span></span></param>
        <param name="keyIdentifierClause"> <span data-ttu-id="67dfd-137">書き込むキー識別句を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-137">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" /> that represents the key identifier clause to write.</span></span></param>
        <summary><span data-ttu-id="67dfd-138">指定された XML ライターを使用して、指定されたキー識別句を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="67dfd-138">Writes the specified key identifier clause using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierCore (writer As XmlWriter, keyIdentifier As SecurityKeyIdentifier)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierCore (writer, keyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="67dfd-139"><see cref="T:System.Xml.XmlWriter" />キー識別子を書き込むために使用します。</span><span class="sxs-lookup"><span data-stu-id="67dfd-139">An <see cref="T:System.Xml.XmlWriter" /> used to write the key identifier.</span></span></param>
        <param name="keyIdentifier"> <span data-ttu-id="67dfd-140">書き込むキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</span><span class="sxs-lookup"><span data-stu-id="67dfd-140">A <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" /> that represents the key identifier to write.</span></span></param>
        <summary><span data-ttu-id="67dfd-141">指定された XML ライターを使用して、指定されたキー識別子を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="67dfd-141">Writes the specified key identifier using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="67dfd-142">バイナリのトークンの内容が null です。</span><span class="sxs-lookup"><span data-stu-id="67dfd-142">The binary token content is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WriteTokenCore">
      <MemberSignature Language="C#" Value="protected override void WriteTokenCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteTokenCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityTokenSerializer.WriteTokenCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteTokenCore (writer As XmlWriter, token As SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.WriteTokenCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityToken -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteTokenCore (writer, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="writer"> <span data-ttu-id="67dfd-143"><see cref="T:System.Xml.XmlWriter" /> SimpleWebSecurityToken またはセキュリティの書き込みに使用されるトークン。</span><span class="sxs-lookup"><span data-stu-id="67dfd-143">An <see cref="T:System.Xml.XmlWriter" /> used to write the SimpleWebSecurityToken or security token.</span></span></param>
        <param name="token"> <span data-ttu-id="67dfd-144">SimpleWebSecurityToken またはセキュリティを記述するトークンします。</span><span class="sxs-lookup"><span data-stu-id="67dfd-144">The SimpleWebSecurityToken or security token to write.</span></span></param>
        <summary><span data-ttu-id="67dfd-145">指定した書き込み<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />または指定した XML ライターを使用してセキュリティ トークン。</span><span class="sxs-lookup"><span data-stu-id="67dfd-145">Writes the specified<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> or security token using the specified XML writer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>