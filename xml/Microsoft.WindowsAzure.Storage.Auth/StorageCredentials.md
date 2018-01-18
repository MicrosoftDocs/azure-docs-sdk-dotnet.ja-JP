<Type Name="StorageCredentials" FullName="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials">
  <TypeSignature Language="C#" Value="public sealed class StorageCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageCredentials" />
  <TypeSignature Language="F#" Value="type StorageCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04fd1-101">Microsoft Azure ストレージ アカウントへのアクセスの認証に使用される資格情報のセットを表します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-101">Represents a set of credentials used to authenticate access to a Microsoft Azure storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-102"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials sasToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken"><span data-ttu-id="04fd1-103">共有アクセス署名トークンを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-103">A string representing the shared access signature token.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-104">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />クラスに、指定した共有アクセス署名トークンです。</span><span class="sxs-lookup"><span data-stu-id="04fd1-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified shared access signature token.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="04fd1-105">ストレージ アカウントの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-105">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="04fd1-106">アカウント アクセス キーを表すバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-106">An array of bytes that represent the account access key.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-107">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名とキーの値を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="04fd1-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name and key value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="04fd1-108">ストレージ アカウントの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-108">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="04fd1-109">Base64 でエンコードされたアカウント アクセス キーを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-109">A string that represents the Base64-encoded account access key.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-110">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名とキーの値を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="04fd1-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name and key value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="04fd1-111">ストレージ アカウントの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-111">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="04fd1-112">アカウント アクセス キーを表すバイトの配列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-112">An array of bytes that represent the account access key.</span></span></param>
        <param name="keyName"><span data-ttu-id="04fd1-113">キーの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-113">A string that represents the name of the key.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-114">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名、キーの値とキーの名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="04fd1-114">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name, key value, and key name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="04fd1-115">ストレージ アカウントの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-115">A string that represents the name of the storage account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="04fd1-116">Base64 でエンコードされたアカウント アクセス キーを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-116">A string that represents the Base64-encoded account access key.</span></span></param>
        <param name="keyName"><span data-ttu-id="04fd1-117">キーの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-117">A string that represents the name of the key.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-118">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名、キーの値とキーの名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="04fd1-118">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> class with the specified account name, key value, and key name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-119">資格情報に関連付けられているアカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-119">Gets the associated account name for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="04fd1-120">アカウント名。</span><span class="sxs-lookup"><span data-stu-id="04fd1-120">The account name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.Equals(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageCredentials) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; bool" Usage="storageCredentials.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="04fd1-121"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />これと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="04fd1-121">The <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object to compare to this one.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-122">かどうかが他の判断<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />オブジェクトが、SAS トークン、アカウント名、キー名、およびキーの値を比較することによってこの 1 と等しい。</span><span class="sxs-lookup"><span data-stu-id="04fd1-122">Determines whether an other <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object is equal to this one by comparing their SAS tokens, account names, key names, and key values.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="04fd1-123"><c>true</c>場合、2 つ<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />オブジェクトが等しい。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="04fd1-123"><c>true</c> if the two <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> objects are equal; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportBase64EncodedKey">
      <MemberSignature Language="C#" Value="public string ExportBase64EncodedKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ExportBase64EncodedKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportBase64EncodedKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportBase64EncodedKey () As String" />
      <MemberSignature Language="F#" Value="member this.ExportBase64EncodedKey : unit -&gt; string" Usage="storageCredentials.ExportBase64EncodedKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-124">アカウント アクセス キーの値を Base64 でエンコードされた文字列にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="04fd1-124">Exports the value of the account access key to a Base64-encoded string.</span></span>
            </summary>
        <returns><span data-ttu-id="04fd1-125">アカウント アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="04fd1-125">The account access key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportKey">
      <MemberSignature Language="C#" Value="public byte[] ExportKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ExportKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportKey () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ExportKey : unit -&gt; byte[]" Usage="storageCredentials.ExportKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-126">資格情報のアカウント キーを返します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-126">Returns the account key for the credentials.</span></span>
            </summary>
        <returns><span data-ttu-id="04fd1-127">キーを含むバイト配列。</span><span class="sxs-lookup"><span data-stu-id="04fd1-127">An array of bytes that contains the key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymous">
      <MemberSignature Language="C#" Value="public bool IsAnonymous { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymous" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAnonymous As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymous : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-128">資格情報が匿名アクセスするかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-128">Gets a value indicating whether the credentials are for anonymous access.</span></span>
            </summary>
        <value>
          <span data-ttu-id="04fd1-129"><c>true</c>資格情報が匿名アクセスの場合それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="04fd1-129"><c>true</c> if the credentials are for anonymous access; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSAS">
      <MemberSignature Language="C#" Value="public bool IsSAS { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSAS" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSAS As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSAS : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-130">トークンの共有アクセス署名は、資格情報であるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-130">Gets a value indicating whether the credentials are a shared access signature token.</span></span>
            </summary>
        <value>
          <span data-ttu-id="04fd1-131"><c>true</c>場合は、資格情報が共有アクセス署名トークンです。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="04fd1-131"><c>true</c> if the credentials are a shared access signature token; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSharedKey">
      <MemberSignature Language="C#" Value="public bool IsSharedKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSharedKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSharedKey : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-132">資格情報が、共有キーであるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-132">Gets a value indicating whether the credentials are a shared key.</span></span>
            </summary>
        <value>
          <span data-ttu-id="04fd1-133"><c>true</c>資格情報が共有する場合、それ以外のキー <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="04fd1-133"><c>true</c> if the credentials are a shared key; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-134">資格情報に関連付けられたキー名を取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-134">Gets the associated key name for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="04fd1-135">キー名。</span><span class="sxs-lookup"><span data-stu-id="04fd1-135">The key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASSignature">
      <MemberSignature Language="C#" Value="public string SASSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASSignature As String" />
      <MemberSignature Language="F#" Value="member this.SASSignature : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-136">共有アクセス署名トークンの値を取得<c>sig</c>パラメーター。</span><span class="sxs-lookup"><span data-stu-id="04fd1-136">Gets the value of the shared access signature token's <c>sig</c> parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASToken">
      <MemberSignature Language="C#" Value="public string SASToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASToken As String" />
      <MemberSignature Language="F#" Value="member this.SASToken : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04fd1-137">資格情報に関連付けられている共有アクセス署名トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-137">Gets the associated shared access signature token for the credentials.</span></span>
            </summary>
        <value><span data-ttu-id="04fd1-138">共有アクセス署名トークンです。</span><span class="sxs-lookup"><span data-stu-id="04fd1-138">The shared access signature token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri TransformUri (Microsoft.WindowsAzure.Storage.StorageUri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.StorageUri TransformUri(class Microsoft.WindowsAzure.Storage.StorageUri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As StorageUri) As StorageUri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="resourceUri"><span data-ttu-id="04fd1-139">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />リソース URI を変換することを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="04fd1-139">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object that represents the resource URI to be transformed.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-140">共有アクセス署名 URI の場合、共有アクセス トークンを追加することによって、リソース URI に変換します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-140">Transforms a resource URI into a shared access signature URI, by appending a shared access token.</span></span>
            </summary>
        <returns><span data-ttu-id="04fd1-141">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />リソース URI と共有アクセス トークンを含む、シグネチャを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="04fd1-141">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object that represents the signature, including the resource URI and the shared access token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Uri TransformUri (Uri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri TransformUri(class System.Uri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Uri -&gt; Uri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="resourceUri"><span data-ttu-id="04fd1-142">A<see cref="T:System.Uri" />リソース URI を変換することを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="04fd1-142">A <see cref="T:System.Uri" /> object that represents the resource URI to be transformed.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-143">共有アクセス署名 URI の場合、共有アクセス トークンを追加することによって、リソース URI に変換します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-143">Transforms a resource URI into a shared access signature URI, by appending a shared access token.</span></span>
            </summary>
        <returns><span data-ttu-id="04fd1-144">A<see cref="T:System.Uri" />リソース URI と共有アクセス トークンを含む、シグネチャを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="04fd1-144">A <see cref="T:System.Uri" /> object that represents the signature, including the resource URI and the shared access token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte())" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="04fd1-145">キーの値を更新する、バイト配列として。</span><span class="sxs-lookup"><span data-stu-id="04fd1-145">The key value, as an array of bytes, to update.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-146">資格情報のキー値を更新します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-146">Updates the key value for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="04fd1-147">キーの値を更新する、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="04fd1-147">The key value, as a Base64-encoded string, to update.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-148">資格情報のキー値を更新します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-148">Updates the key value for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="04fd1-149">キーの値を更新する、バイト配列として。</span><span class="sxs-lookup"><span data-stu-id="04fd1-149">The key value, as an array of bytes, to update.</span></span></param>
        <param name="keyName"><span data-ttu-id="04fd1-150">更新するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="04fd1-150">The key name to update.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-151">キーの値とキー名、資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-151">Updates the key value and key name for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue"><span data-ttu-id="04fd1-152">キーの値を更新する、Base64 でエンコードされた文字列として。</span><span class="sxs-lookup"><span data-stu-id="04fd1-152">The key value, as a Base64-encoded string, to update.</span></span></param>
        <param name="keyName"><span data-ttu-id="04fd1-153">更新するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="04fd1-153">The key name to update.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-154">キーの値とキー名、資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-154">Updates the key value and key name for the credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSASToken">
      <MemberSignature Language="C#" Value="public void UpdateSASToken (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSASToken(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateSASToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSASToken (sasToken As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateSASToken : string -&gt; unit" Usage="storageCredentials.UpdateSASToken sasToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken"><span data-ttu-id="04fd1-155">SAS を指定する文字列はトークンを更新する値です。</span><span class="sxs-lookup"><span data-stu-id="04fd1-155">A string that specifies the SAS token value to update.</span></span></param>
        <summary>
            <span data-ttu-id="04fd1-156">共有アクセス署名で作成したストレージ資格情報の共有アクセス署名 (SAS) トークン値を更新します。</span><span class="sxs-lookup"><span data-stu-id="04fd1-156">Updates the shared access signature (SAS) token value for storage credentials created with a shared access signature.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>