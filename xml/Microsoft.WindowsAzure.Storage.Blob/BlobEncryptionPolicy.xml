<Type Name="BlobEncryptionPolicy" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy">
  <TypeSignature Language="C#" Value="public sealed class BlobEncryptionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobEncryptionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobEncryptionPolicy" />
  <TypeSignature Language="F#" Value="type BlobEncryptionPolicy = class" />
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
            <span data-ttu-id="e06f0-101">エンベロープ暗号化/暗号化解除の Azure blob を実行するための暗号化ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-101">Represents an encryption policy for performing envelope encryption/decryption of Azure blobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobEncryptionPolicy (Microsoft.Azure.KeyVault.Core.IKey key, Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.Core.IKey key, class Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.#ctor(Microsoft.Azure.KeyVault.Core.IKey,Microsoft.Azure.KeyVault.Core.IKeyResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (key As IKey, keyResolver As IKeyResolver)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy : Microsoft.Azure.KeyVault.Core.IKey * Microsoft.Azure.KeyVault.Core.IKeyResolver -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" Usage="new Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy (key, keyResolver)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.Core.IKey" />
        <Parameter Name="keyResolver" Type="Microsoft.Azure.KeyVault.Core.IKeyResolver" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="e06f0-102">型のオブジェクト<see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />ラップ/ラップ解除コンテンツ キーの暗号化中に使用されます。</span><span class="sxs-lookup"><span data-stu-id="e06f0-102">An object of type <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> that is used to wrap/unwrap the content key during encryption.</span></span></param>
        <param name="keyResolver"><span data-ttu-id="e06f0-103">キーの競合回避モジュールを既存の blob を解読するための正しいキーを選択します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-103">The key resolver used to select the correct key for decrypting existing blobs.</span></span></param>
        <summary>
            <span data-ttu-id="e06f0-104">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" />クラスを指定したキーとの競合回避モジュールを使用します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" /> class with the specified key and resolver.</span></span>
            </summary>
        <remarks><span data-ttu-id="e06f0-105">生成されたポリシーは、暗号化に使用するのには、ユーザーが予想される場合に、少なくともキーを提供します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-105">If the generated policy is to be used for encryption, users are expected to provide a key at the minimum.</span></span>
            <span data-ttu-id="e06f0-106">キーがない場合に、暗号化中にスローされる例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-106">The absence of key will cause an exception to be thrown during encryption.</span></span><br />
            <span data-ttu-id="e06f0-107">生成されたポリシーを復号化に使用する場合は、ユーザーは、キーの競合回避モジュールを指定できます。</span><span class="sxs-lookup"><span data-stu-id="e06f0-107">If the generated policy is intended to be used for decryption, users can provide a key resolver.</span></span> <span data-ttu-id="e06f0-108">クライアント ライブラリを行います。</span><span class="sxs-lookup"><span data-stu-id="e06f0-108">The client library will:</span></span><br />
            1. <span data-ttu-id="e06f0-109">指定すると、キーを取得する場合は、キーの競合回避モジュールを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-109">Invoke the key resolver, if specified, to get the key.</span></span><br />
            2. <span data-ttu-id="e06f0-110">キーをクライアント ライブラリに一致するキーが指定された競合回避モジュールが指定されていない場合、キーとキーを使用して対象の ID。</span><span class="sxs-lookup"><span data-stu-id="e06f0-110">If resolver is not specified but a key is specified, the client library will match the key ID against the key and use the key.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As IKey" />
      <MemberSignature Language="F#" Value="member this.Key : Microsoft.Azure.KeyVault.Core.IKey" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e06f0-111">型のオブジェクト<see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />ラップ/ラップ解除コンテンツ キーの暗号化中に使用されます。</span><span class="sxs-lookup"><span data-stu-id="e06f0-111">An object of type <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> that is used to wrap/unwrap the content key during encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyResolver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.KeyResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyResolver As IKeyResolver" />
      <MemberSignature Language="F#" Value="member this.KeyResolver : Microsoft.Azure.KeyVault.Core.IKeyResolver" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.KeyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKeyResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e06f0-112">取得または設定キーの競合回避モジュールを既存の blob を解読するための正しいキーを選択します。</span><span class="sxs-lookup"><span data-stu-id="e06f0-112">Gets or sets the key resolver used to select the correct key for decrypting existing blobs.</span></span>
            </summary>
        <value><span data-ttu-id="e06f0-113">競合回避モジュールを返す、 <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />、特定のキー id です。</span><span class="sxs-lookup"><span data-stu-id="e06f0-113">A resolver that returns an <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />, given a key ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>