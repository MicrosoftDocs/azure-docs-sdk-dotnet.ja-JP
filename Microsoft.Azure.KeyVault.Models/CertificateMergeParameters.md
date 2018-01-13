<Type Name="CertificateMergeParameters" FullName="Microsoft.Azure.KeyVault.Models.CertificateMergeParameters">
  <TypeSignature Language="C#" Value="public class CertificateMergeParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateMergeParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateMergeParameters" />
  <TypeSignature Language="F#" Value="type CertificateMergeParameters = class" />
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
            証明書のマージ パラメーター
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateMergeParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificateMergeParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateMergeParameters (System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.#ctor(System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateMergeParameters : System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.CertificateMergeParameters" Usage="new Microsoft.Azure.KeyVault.Models.CertificateMergeParameters (x509Certificates, certificateAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="x509Certificates">証明書または証明書チェーンをマージします。</param>
        <param name="certificateAttributes">(省略可能) の証明書の属性。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ。</param>
        <summary>
            CertificateMergeParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificateAttributes CertificateAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.CertificateAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateAttributes As CertificateAttributes" />
      <MemberSignature Language="F#" Value="member this.CertificateAttributes : Microsoft.Azure.KeyVault.Models.CertificateAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.CertificateAttributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificateAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (省略可能) 証明書の属性を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.Tags" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateMergeParameters.Validate " />
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
    <Member MemberName="X509Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;byte[]&gt; X509Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; X509Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.X509Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property X509Certificates As IList(Of Byte())" />
      <MemberSignature Language="F#" Value="member this.X509Certificates : System.Collections.Generic.IList&lt;byte[]&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateMergeParameters.X509Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="x5c")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定証明書、証明書チェーンをマージします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>