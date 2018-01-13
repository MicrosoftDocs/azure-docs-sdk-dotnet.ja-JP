<Type Name="VaultExtendedInfoResource" FullName="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource">
  <TypeSignature Language="C#" Value="public class VaultExtendedInfoResource : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultExtendedInfoResource extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultExtendedInfoResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VaultExtendedInfoResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            コンテナー情報を拡張します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultExtendedInfoResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VaultExtendedInfoResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultExtendedInfoResource (string id = null, string name = null, string type = null, string eTag = null, string integrityKey = null, string encryptionKey = null, string encryptionKeyThumbprint = null, string algorithm = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string integrityKey, string encryptionKey, string encryptionKeyThumbprint, string algorithm) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional integrityKey As String = null, Optional encryptionKey As String = null, Optional encryptionKeyThumbprint As String = null, Optional algorithm As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource (id, name, type, eTag, integrityKey, encryptionKey, encryptionKeyThumbprint, algorithm)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="integrityKey" Type="System.String" />
        <Parameter Name="encryptionKey" Type="System.String" />
        <Parameter Name="encryptionKeyThumbprint" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id は、リソースへの完全なパスを表します。</param>
        <param name="name">リソースに関連付けられているリソースの名前です。</param>
        <param name="type">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</param>
        <param name="eTag">省略可能な ETag です。</param>
        <param name="integrityKey">整合性キー。</param>
        <param name="encryptionKey">暗号化キーです。</param>
        <param name="encryptionKeyThumbprint">暗号化キーのサムプリント。</param>
        <param name="algorithm">アルゴリズムです。</param>
        <summary>
            VaultExtendedInfoResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.algorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアルゴリズムを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKey">
      <MemberSignature Language="C#" Value="public string EncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKey As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKey : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または暗号化キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyThumbprint">
      <MemberSignature Language="C#" Value="public string EncryptionKeyThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKeyThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyThumbprint : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKeyThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKeyThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または暗号化キーのサムプリントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrityKey">
      <MemberSignature Language="C#" Value="public string IntegrityKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IntegrityKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.IntegrityKey" />
      <MemberSignature Language="VB.NET" Value="Public Property IntegrityKey As String" />
      <MemberSignature Language="F#" Value="member this.IntegrityKey : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.IntegrityKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.integrityKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキーの整合性を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>