<Type Name="KeyVaultProperties" FullName="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties">
  <TypeSignature Language="C#" Value="public class KeyVaultProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultProperties" />
  <TypeSignature Language="F#" Value="type KeyVaultProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            資格情報コンテナーのプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            KeyVaultProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultProperties (string keyName = null, string keyVersion = null, string keyVaultUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string keyVersion, string keyVaultUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyName As String = null, Optional keyVersion As String = null, Optional keyVaultUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.KeyVaultProperties : string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.KeyVaultProperties" Usage="new Microsoft.Azure.Management.Storage.Models.KeyVaultProperties (keyName, keyVersion, keyVaultUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyVaultUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">KeyVault キーの名前。</param>
        <param name="keyVersion">KeyVault キーのバージョン。</param>
        <param name="keyVaultUri">KeyVault の Uri。</param>
        <summary>
            KeyVaultProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または KeyVault キーの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultUri">
      <MemberSignature Language="C#" Value="public string KeyVaultUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyVaultUri" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultUri As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultUri : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyVaultUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyvaulturi")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または KeyVault の Uri を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVersion">
      <MemberSignature Language="C#" Value="public string KeyVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVersion As String" />
      <MemberSignature Language="F#" Value="member this.KeyVersion : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties.KeyVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyversion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または KeyVault キーのバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>