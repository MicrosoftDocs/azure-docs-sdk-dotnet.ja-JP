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
            Microsoft Azure ストレージ アカウントへのアクセスの認証に使用される資格情報のセットを表します。
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
            <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> クラスの新しいインスタンスを初期化します。
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
        <param name="sasToken">共有アクセス署名トークンを表す文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />クラスに、指定した共有アクセス署名トークンです。
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
        <param name="accountName">ストレージ アカウントの名前を表す文字列。</param>
        <param name="keyValue">アカウント アクセス キーを表すバイトの配列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名とキーの値を持つクラス。
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
        <param name="accountName">ストレージ アカウントの名前を表す文字列。</param>
        <param name="keyValue">Base64 でエンコードされたアカウント アクセス キーを表す文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名とキーの値を持つクラス。
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
        <param name="accountName">ストレージ アカウントの名前を表す文字列。</param>
        <param name="keyValue">アカウント アクセス キーを表すバイトの配列。</param>
        <param name="keyName">キーの名前を表す文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名、キーの値とキーの名前を持つクラス。
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
        <param name="accountName">ストレージ アカウントの名前を表す文字列。</param>
        <param name="keyValue">Base64 でエンコードされたアカウント アクセス キーを表す文字列。</param>
        <param name="keyName">キーの名前を表す文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />指定されたアカウント名、キーの値とキーの名前を持つクラス。
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
            資格情報に関連付けられているアカウント名を取得します。
            </summary>
        <value>アカウント名。</value>
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
        <param name="other"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />これと比較するオブジェクト。</param>
        <summary>
            かどうかが他の判断<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />オブジェクトが、SAS トークン、アカウント名、キー名、およびキーの値を比較することによってこの 1 と等しい。
            </summary>
        <returns>
          <c>true</c>場合、2 つ<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />オブジェクトが等しい。 それ以外の場合、 <c>false</c>です。</returns>
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
            アカウント アクセス キーの値を Base64 でエンコードされた文字列にエクスポートします。
            </summary>
        <returns>アカウント アクセス キー。</returns>
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
            資格情報のアカウント キーを返します。
            </summary>
        <returns>キーを含むバイト配列。</returns>
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
            資格情報が匿名アクセスするかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>資格情報が匿名アクセスの場合それ以外の場合、 <c>false</c>です。</value>
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
            トークンの共有アクセス署名は、資格情報であるかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合は、資格情報が共有アクセス署名トークンです。 それ以外の場合、 <c>false</c>です。</value>
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
            資格情報が、共有キーであるかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>資格情報が共有する場合、それ以外のキー <c>false</c>です。</value>
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
            資格情報に関連付けられたキー名を取得します。
            </summary>
        <value>キー名。</value>
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
            共有アクセス署名トークンの値を取得<c>sig</c>パラメーター。
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
            資格情報に関連付けられている共有アクセス署名トークンを取得します。
            </summary>
        <value>共有アクセス署名トークンです。</value>
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
        <param name="resourceUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />リソース URI を変換することを表すオブジェクト。</param>
        <summary>
            共有アクセス署名 URI の場合、共有アクセス トークンを追加することによって、リソース URI に変換します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />リソース URI と共有アクセス トークンを含む、シグネチャを表すオブジェクト。</returns>
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
        <param name="resourceUri">A<see cref="T:System.Uri" />リソース URI を変換することを表すオブジェクト。</param>
        <summary>
            共有アクセス署名 URI の場合、共有アクセス トークンを追加することによって、リソース URI に変換します。
            </summary>
        <returns>A<see cref="T:System.Uri" />リソース URI と共有アクセス トークンを含む、シグネチャを表すオブジェクト。</returns>
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
        <param name="keyValue">キーの値を更新する、バイト配列として。</param>
        <summary>
            資格情報のキー値を更新します。
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
        <param name="keyValue">キーの値を更新する、Base64 でエンコードされた文字列として。</param>
        <summary>
            資格情報のキー値を更新します。
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
        <param name="keyValue">キーの値を更新する、バイト配列として。</param>
        <param name="keyName">更新するキーの名前。</param>
        <summary>
            キーの値とキー名、資格情報を更新します。
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
        <param name="keyValue">キーの値を更新する、Base64 でエンコードされた文字列として。</param>
        <param name="keyName">更新するキーの名前。</param>
        <summary>
            キーの値とキー名、資格情報を更新します。
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
        <param name="sasToken">SAS を指定する文字列はトークンを更新する値です。</param>
        <summary>
            共有アクセス署名で作成したストレージ資格情報の共有アクセス署名 (SAS) トークン値を更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>