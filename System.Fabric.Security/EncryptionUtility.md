<Type Name="EncryptionUtility" FullName="System.Fabric.Security.EncryptionUtility">
  <TypeSignature Language="C#" Value="public sealed class EncryptionUtility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EncryptionUtility extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Security.EncryptionUtility" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EncryptionUtility" />
  <TypeSignature Language="F#" Value="type EncryptionUtility = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="722eb-101">暗号化ユーティリティを表します。</span><span class="sxs-lookup"><span data-stu-id="722eb-101">Represents the encryption utility.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionUtility ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="722eb-102">新しいインスタンスを作成<see cref="T:System.Fabric.Security.EncryptionUtility" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="722eb-102">Instantiates a new <see cref="T:System.Fabric.Security.EncryptionUtility" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptText (textToDecrypt As String) As SecureString" />
      <MemberSignature Language="F#" Value="static member DecryptText : string -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="722eb-103">暗号化されたテキストの暗号化を解除します。</span><span class="sxs-lookup"><span data-stu-id="722eb-103">The encrypted text to decrypt.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-104">EncryptText メソッドによって暗号化されたテキスト文字列を復号化<see cref="T:System.Fabric.Security.EncryptionUtility" />、暗号化解除証明書のストアの場所が LocalMachine であると見なされます。</span><span class="sxs-lookup"><span data-stu-id="722eb-104">Decrypt a text string encrypted by EncryptText methods of <see cref="T:System.Fabric.Security.EncryptionUtility" />, it is assumed that the store location of decryption certificate is LocalMachine.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-105">復号化されたテキストとして<see cref="T:System.Security.SecureString" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-105">The decrypted text as <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String,System.Security.Cryptography.X509Certificates.StoreLocation)" />
      <MemberSignature Language="F#" Value="static member DecryptText : string * System.Security.Cryptography.X509Certificates.StoreLocation -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText (textToDecrypt, storeLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="722eb-106">暗号化されたテキストの暗号化を解除します。</span><span class="sxs-lookup"><span data-stu-id="722eb-106">The encrypted text to decrypt.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="722eb-107">証明書ストアの暗号化解除証明書を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="722eb-107">The certificate store location to retrieve decryption certificate.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-108">EncryptText メソッドによって暗号化されたテキスト文字列を復号化<see cref="T:System.Fabric.Security.EncryptionUtility" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-108">Decrypt a text string encrypted by EncryptText methods of <see cref="T:System.Fabric.Security.EncryptionUtility" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-109">復号化されたテキストとして<see cref="T:System.Security.SecureString" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-109">The decrypted text as <see cref="T:System.Security.SecureString" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public static string DecryptValue (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string DecryptValue(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptValue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptValue (textToDecrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member DecryptValue : string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.DecryptValue textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated DecryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para><span data-ttu-id="722eb-110">暗号化を解除する文字列値。</span><span class="sxs-lookup"><span data-stu-id="722eb-110">The string value to decrypt.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-111">EncryptValue を呼び出すことによって暗号化された文字列値を復号化します。</span><span class="sxs-lookup"><span data-stu-id="722eb-111">Decrypts string values that were encrypted by calling EncryptValue.</span></span> <span data-ttu-id="722eb-112">このメソッドは廃止されました。EncryptText メソッドは、代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="722eb-112">This method is deprecated; EncryptText method should be used instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-113">復号化された値。</span><span class="sxs-lookup"><span data-stu-id="722eb-113">The decrypted value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptText (textToEncrypt As String, thumbprint As String, storeName As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="722eb-114">暗号化するテキスト文字列。</span><span class="sxs-lookup"><span data-stu-id="722eb-114">The text string to encrypt.</span></span></para>
        </param>
        <param name="thumbprint">
          <para><span data-ttu-id="722eb-115">暗号化証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="722eb-115">The thumbprint of encryption certificate.</span></span></para>
        </param>
        <param name="storeName">
          <para><span data-ttu-id="722eb-116">証明書を取得する暗号化からの証明書ストアの名前。</span><span class="sxs-lookup"><span data-stu-id="722eb-116">The name of certificate store, from which encryption certificate is retrieved.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-117">インストールされている X509 をテキスト文字列を暗号化証明書。</span><span class="sxs-lookup"><span data-stu-id="722eb-117">Encrypt text string with an installed X509 certificate.</span></span> <span data-ttu-id="722eb-118">証明書ストアの場所は LocalMachine と暗号化アルゴリズムは AES256 CBC です。</span><span class="sxs-lookup"><span data-stu-id="722eb-118">Certificate store location is LocalMachine and the encryption algorithm is AES256 CBC.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-119">暗号化されたテキストとして<see cref="T:System.String" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-119">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String,System.Security.Cryptography.X509Certificates.StoreLocation,System.String)" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string * System.Security.Cryptography.X509Certificates.StoreLocation * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName, storeLocation, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="722eb-120">暗号化テキストです。</span><span class="sxs-lookup"><span data-stu-id="722eb-120">The text to encrypt.</span></span></para>
        </param>
        <param name="thumbprint">
          <para><span data-ttu-id="722eb-121">暗号化証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="722eb-121">The thumbprint of encryption certificate.</span></span></para>
        </param>
        <param name="storeName">
          <para><span data-ttu-id="722eb-122">証明書を取得する暗号化からの証明書ストアの名前。</span><span class="sxs-lookup"><span data-stu-id="722eb-122">The name of certificate store, from which encryption certificate is retrieved.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="722eb-123">証明書ストアの暗号化証明書を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="722eb-123">The certificate store location to retrieve encryption certificate.</span></span></para>
        </param>
        <param name="algorithmOid">
          <para><span data-ttu-id="722eb-124">暗号化アルゴリズム オブジェクト識別子 (OID)。</span><span class="sxs-lookup"><span data-stu-id="722eb-124">The encryption algorithm object identifier (OID).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-125">インストールされている X509 をテキスト文字列を暗号化証明書。</span><span class="sxs-lookup"><span data-stu-id="722eb-125">Encrypt text string with an installed X509 certificate.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-126">暗号化されたテキストとして<see cref="T:System.String" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-126">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptTextByCertFile">
      <MemberSignature Language="C#" Value="public static string EncryptTextByCertFile (string textToEncrypt, string certFileName, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptTextByCertFile(string textToEncrypt, string certFileName, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptTextByCertFile (textToEncrypt As String, certFileName As String, algorithmOid As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptTextByCertFile : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile (textToEncrypt, certFileName, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="certFileName" Type="System.String" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para><span data-ttu-id="722eb-127">暗号化テキストです。</span><span class="sxs-lookup"><span data-stu-id="722eb-127">The text to encrypt.</span></span></para>
        </param>
        <param name="certFileName">
          <para><span data-ttu-id="722eb-128">暗号化証明書ファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="722eb-128">The encryption certificate file path.</span></span></para>
        </param>
        <param name="algorithmOid">
          <para><span data-ttu-id="722eb-129">暗号化アルゴリズム オブジェクト識別子 (OID)。</span><span class="sxs-lookup"><span data-stu-id="722eb-129">The encryption algorithm object identifier (OID).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-130">X509 をテキスト文字列を暗号化するファイルの証明書。</span><span class="sxs-lookup"><span data-stu-id="722eb-130">Encrypt text string with an X509 certificate in a file.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-131">暗号化されたテキストとして<see cref="T:System.String" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-131">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptValue">
      <MemberSignature Language="C#" Value="public static string EncryptValue (string thumbprint, string storeLocation, string textToEncrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptValue(string thumbprint, string storeLocation, string textToEncrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptValue(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptValue (thumbprint As String, storeLocation As String, textToEncrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptValue : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptValue (thumbprint, storeLocation, textToEncrypt)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated by EncryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.String" />
        <Parameter Name="textToEncrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint">
          <para><span data-ttu-id="722eb-132">テキストの暗号化に使用される証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="722eb-132">The thumbprint of certificate used to encrypt text.</span></span></para>
        </param>
        <param name="storeLocation">
          <para><span data-ttu-id="722eb-133">証明書の StoreName します。</span><span class="sxs-lookup"><span data-stu-id="722eb-133">The StoreName for the certificate.</span></span> <span data-ttu-id="722eb-134">既定値は"My"ストア。</span><span class="sxs-lookup"><span data-stu-id="722eb-134">Defaults to "My" store.</span></span></para>
        </param>
        <param name="textToEncrypt">
          <para><span data-ttu-id="722eb-135">テキスト値を暗号化する必要があります。</span><span class="sxs-lookup"><span data-stu-id="722eb-135">The text value that needs to be encrypted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="722eb-136">指定された証明書を使用して文字列値を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="722eb-136">Encrypts string value using specified certificate.</span></span> <span data-ttu-id="722eb-137">このメソッドは廃止されました。EncryptText メソッドは、代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="722eb-137">This method is deprecated; EncryptText method should be used instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="722eb-138">暗号化されたテキストとして<see cref="T:System.String" />です。</span><span class="sxs-lookup"><span data-stu-id="722eb-138">The encrypted text as <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>