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
      <para>暗号化ユーティリティを表します。</para>
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
          <para>新しいインスタンスを作成<see cref="T:System.Fabric.Security.EncryptionUtility" />クラスです。</para>
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
          <para>暗号化されたテキストの暗号化を解除します。</para>
        </param>
        <summary>
          <para>EncryptText メソッドによって暗号化されたテキスト文字列を復号化<see cref="T:System.Fabric.Security.EncryptionUtility" />、暗号化解除証明書のストアの場所が LocalMachine であると見なされます。</para>
        </summary>
        <returns>
          <para>復号化されたテキストとして<see cref="T:System.Security.SecureString" />です。</para>
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
          <para>暗号化されたテキストの暗号化を解除します。</para>
        </param>
        <param name="storeLocation">
          <para>証明書ストアの暗号化解除証明書を取得する場所です。</para>
        </param>
        <summary>
          <para>EncryptText メソッドによって暗号化されたテキスト文字列を復号化<see cref="T:System.Fabric.Security.EncryptionUtility" />です。</para>
        </summary>
        <returns>
          <para>復号化されたテキストとして<see cref="T:System.Security.SecureString" />です。</para>
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
          <para>暗号化を解除する文字列値。</para>
        </param>
        <summary>
          <para>EncryptValue を呼び出すことによって暗号化された文字列値を復号化します。 このメソッドは廃止されました。EncryptText メソッドは、代わりに使用する必要があります。</para>
        </summary>
        <returns>
          <para>復号化された値。</para>
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
          <para>暗号化するテキスト文字列。</para>
        </param>
        <param name="thumbprint">
          <para>暗号化証明書の拇印です。</para>
        </param>
        <param name="storeName">
          <para>証明書を取得する暗号化からの証明書ストアの名前。</para>
        </param>
        <summary>
          <para>インストールされている X509 をテキスト文字列を暗号化証明書。 証明書ストアの場所は LocalMachine と暗号化アルゴリズムは AES256 CBC です。</para>
        </summary>
        <returns>
          <para>暗号化されたテキストとして<see cref="T:System.String" />です。</para>
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
          <para>暗号化テキストです。</para>
        </param>
        <param name="thumbprint">
          <para>暗号化証明書の拇印です。</para>
        </param>
        <param name="storeName">
          <para>証明書を取得する暗号化からの証明書ストアの名前。</para>
        </param>
        <param name="storeLocation">
          <para>証明書ストアの暗号化証明書を取得する場所です。</para>
        </param>
        <param name="algorithmOid">
          <para>暗号化アルゴリズム オブジェクト識別子 (OID)。</para>
        </param>
        <summary>
          <para>インストールされている X509 をテキスト文字列を暗号化証明書。</para>
        </summary>
        <returns>
          <para>暗号化されたテキストとして<see cref="T:System.String" />です。</para>
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
          <para>暗号化テキストです。</para>
        </param>
        <param name="certFileName">
          <para>暗号化証明書ファイルのパス。</para>
        </param>
        <param name="algorithmOid">
          <para>暗号化アルゴリズム オブジェクト識別子 (OID)。</para>
        </param>
        <summary>
          <para>X509 をテキスト文字列を暗号化するファイルの証明書。</para>
        </summary>
        <returns>
          <para>暗号化されたテキストとして<see cref="T:System.String" />です。</para>
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
          <para>テキストの暗号化に使用される証明書の拇印です。</para>
        </param>
        <param name="storeLocation">
          <para>証明書の StoreName します。 既定値は"My"ストア。</para>
        </param>
        <param name="textToEncrypt">
          <para>テキスト値を暗号化する必要があります。</para>
        </param>
        <summary>
          <para>指定された証明書を使用して文字列値を暗号化します。 このメソッドは廃止されました。EncryptText メソッドは、代わりに使用する必要があります。</para>
        </summary>
        <returns>
          <para>暗号化されたテキストとして<see cref="T:System.String" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>