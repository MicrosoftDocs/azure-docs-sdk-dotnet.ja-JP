<Type Name="Vault" FullName="Microsoft.Azure.Management.RecoveryServices.Models.Vault">
  <TypeSignature Language="C#" Value="public class Vault : Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Vault extends Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.Vault" />
  <TypeSignature Language="VB.NET" Value="Public Class Vault&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type Vault = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リソースについては、リソース プロバイダーによって返されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            コンテナー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Vault (string location, string id = null, string name = null, string type = null, string eTag = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties properties = null, Microsoft.Azure.Management.RecoveryServices.Models.Sku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, string eTag, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties properties, class Microsoft.Azure.Management.RecoveryServices.Models.Sku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties,Microsoft.Azure.Management.RecoveryServices.Models.Sku)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.Vault : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties * Microsoft.Azure.Management.RecoveryServices.Models.Sku -&gt; Microsoft.Azure.Management.RecoveryServices.Models.Vault" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.Vault (location, id, name, type, eTag, tags, properties, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.RecoveryServices.Models.Sku" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所。</param>
        <param name="id">リソース Id は、リソースへの完全なパスを表します。</param>
        <param name="name">リソースに関連付けられているリソースの名前です。</param>
        <param name="type">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</param>
        <param name="eTag">省略可能な ETag です。</param>
        <param name="tags">リソース タグ。</param>
        <param name="properties">To be added.</param>
        <param name="sku">To be added.</param>
        <summary>
            コンテナー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As VaultProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.Vault.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.VaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.RecoveryServices.Models.Sku with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.Vault.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.Vault.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="vault.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>