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
            エンベロープ暗号化/暗号化解除の Azure blob を実行するための暗号化ポリシーを表します。
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
        <param name="key">型のオブジェクト<see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />ラップ/ラップ解除コンテンツ キーの暗号化中に使用されます。</param>
        <param name="keyResolver">キーの競合回避モジュールを既存の blob を解読するための正しいキーを選択します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" />クラスを指定したキーとの競合回避モジュールを使用します。
            </summary>
        <remarks>生成されたポリシーは、暗号化に使用するのには、ユーザーが予想される場合に、少なくともキーを提供します。
            キーがない場合に、暗号化中にスローされる例外が発生します。<br />
            生成されたポリシーを復号化に使用する場合は、ユーザーは、キーの競合回避モジュールを指定できます。 クライアント ライブラリを行います。<br />
            1. 指定すると、キーを取得する場合は、キーの競合回避モジュールを呼び出します。<br />
            2. キーをクライアント ライブラリに一致するキーが指定された競合回避モジュールが指定されていない場合、キーとキーを使用して対象の ID。</remarks>
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
            型のオブジェクト<see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />ラップ/ラップ解除コンテンツ キーの暗号化中に使用されます。
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
            取得または設定キーの競合回避モジュールを既存の blob を解読するための正しいキーを選択します。
            </summary>
        <value>競合回避モジュールを返す、 <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />、特定のキー id です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>