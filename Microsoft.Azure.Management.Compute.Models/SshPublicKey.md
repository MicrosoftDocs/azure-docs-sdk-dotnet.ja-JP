<Type Name="SshPublicKey" FullName="Microsoft.Azure.Management.Compute.Models.SshPublicKey">
  <TypeSignature Language="C#" Value="public class SshPublicKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SshPublicKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.SshPublicKey" />
  <TypeSignature Language="VB.NET" Value="Public Class SshPublicKey" />
  <TypeSignature Language="F#" Value="type SshPublicKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            公開キーが配置されている Linux VM 上の SSH 証明書の公開キーとパスに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.SshPublicKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SshPublicKey クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey (string path = null, string keyData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path, string keyData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.SshPublicKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional path As String = null, Optional keyData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.SshPublicKey : string * string -&gt; Microsoft.Azure.Management.Compute.Models.SshPublicKey" Usage="new Microsoft.Azure.Management.Compute.Models.SshPublicKey (path, keyData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="keyData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Ssh 公開キーの保存場所に作成された VM 上の完全なパスを指定します。 ファイルが既に存在する場合は、ファイルに指定したキーが追加されます。 例:/home/user/.ssh/authorized_keys</param>
        <param name="keyData">SSH 公開キー証明書の認証に、VM と ssh を使用します。 キーは、少なくとも 2048 ビットで、ssh rsa 形式になる必要があります。 &lt;ブラジル&gt;&lt;br&gt;を作成する ssh キーを参照してください。 [Linux、Mac 上で、Azure Linux vm の作成の SSH キー](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。</param>
        <summary>
            SshPublicKey クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyData">
      <MemberSignature Language="C#" Value="public string KeyData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.SshPublicKey.KeyData" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyData As String" />
      <MemberSignature Language="F#" Value="member this.KeyData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.SshPublicKey.KeyData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SSH 公開キー証明書認証に使用される、VM と ssh を設定します。 キーは、少なくとも 2048 ビットで、ssh rsa 形式になる必要があります。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;作成する ssh キーを参照してください。 [Linux、Mac 上で、Azure Linux vm の作成の SSH キー](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.SshPublicKey.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.SshPublicKey.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ssh 公開キーの保存場所に作成された VM 上の完全パスを指定します。 ファイルが既に存在する場合は、ファイルに指定したキーが追加されます。 例:/home/user/.ssh/authorized_keys
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>