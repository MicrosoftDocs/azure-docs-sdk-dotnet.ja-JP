<Type Name="KeyImportParameters" FullName="Microsoft.Azure.KeyVault.Models.KeyImportParameters">
  <TypeSignature Language="C#" Value="public class KeyImportParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyImportParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyImportParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyImportParameters" />
  <TypeSignature Language="F#" Value="type KeyImportParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            キーのインポートのパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyImportParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyImportParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            KeyImportParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyImportParameters (Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyImportParameters.#ctor(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyImportParameters : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.KeyImportParameters" Usage="new Microsoft.Azure.KeyVault.Models.KeyImportParameters (key, hsm, keyAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="key">Json web key</param>
        <param name="hsm">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。</param>
        <param name="keyAttributes">キー管理の属性です。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ。</param>
        <summary>
            KeyImportParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hsm">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Hsm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Hsm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyImportParameters.Hsm" />
      <MemberSignature Language="VB.NET" Value="Public Property Hsm As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Hsm : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyImportParameters.Hsm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Hsm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.WebKey.JsonWebKey Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.WebKey.JsonWebKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyImportParameters.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As JsonWebKey" />
      <MemberSignature Language="F#" Value="member this.Key : Microsoft.Azure.KeyVault.WebKey.JsonWebKey with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyImportParameters.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の Json web key
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.KeyAttributes KeyAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.KeyAttributes KeyAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyImportParameters.KeyAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyAttributes As KeyAttributes" />
      <MemberSignature Language="F#" Value="member this.KeyAttributes : Microsoft.Azure.KeyVault.Models.KeyAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyImportParameters.KeyAttributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.KeyAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキー管理の属性を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyImportParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyImportParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキー/値ペアの形式でアプリケーション固有のメタデータを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyImportParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyImportParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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