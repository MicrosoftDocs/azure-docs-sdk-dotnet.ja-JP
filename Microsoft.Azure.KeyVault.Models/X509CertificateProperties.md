<Type Name="X509CertificateProperties" FullName="Microsoft.Azure.KeyVault.Models.X509CertificateProperties">
  <TypeSignature Language="C#" Value="public class X509CertificateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit X509CertificateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.X509CertificateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class X509CertificateProperties" />
  <TypeSignature Language="F#" Value="type X509CertificateProperties = class" />
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
            プロパティの X509 証明書のコンポーネントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509CertificateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            X509CertificateProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509CertificateProperties (string subject = null, System.Collections.Generic.IList&lt;string&gt; ekus = null, Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames subjectAlternativeNames = null, System.Collections.Generic.IList&lt;string&gt; keyUsage = null, Nullable&lt;int&gt; validityInMonths = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subject, class System.Collections.Generic.IList`1&lt;string&gt; ekus, class Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames subjectAlternativeNames, class System.Collections.Generic.IList`1&lt;string&gt; keyUsage, valuetype System.Nullable`1&lt;int32&gt; validityInMonths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.#ctor(System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames,System.Collections.Generic.IList{System.String},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.X509CertificateProperties : string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.KeyVault.Models.X509CertificateProperties" Usage="new Microsoft.Azure.KeyVault.Models.X509CertificateProperties (subject, ekus, subjectAlternativeNames, keyUsage, validityInMonths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="ekus" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="subjectAlternativeNames" Type="Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames" />
        <Parameter Name="keyUsage" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="validityInMonths" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="subject">サブジェクト名。 有効な X509 識別名をする必要があります。</param>
        <param name="ekus">拡張キー使用法。</param>
        <param name="subjectAlternativeNames">サブジェクト代替名です。</param>
        <param name="keyUsage">キー使用法の一覧です。</param>
        <param name="validityInMonths">か月以内に有効では、証明期間です。</param>
        <summary>
            X509CertificateProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ekus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Ekus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Ekus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Ekus" />
      <MemberSignature Language="VB.NET" Value="Public Property Ekus As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Ekus : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Ekus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ekus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または拡張キー使用法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeyUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeyUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.KeyUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUsage As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeyUsage : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.KeyUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key_usage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキー使用法の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subject">
      <MemberSignature Language="C#" Value="public string Subject { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Subject" />
      <MemberSignature Language="VB.NET" Value="Public Property Subject As String" />
      <MemberSignature Language="F#" Value="member this.Subject : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Subject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subject")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブジェクト名を設定します。 有効な X509 識別名をする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectAlternativeNames">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames SubjectAlternativeNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames SubjectAlternativeNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.SubjectAlternativeNames" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectAlternativeNames As SubjectAlternativeNames" />
      <MemberSignature Language="F#" Value="member this.SubjectAlternativeNames : Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.SubjectAlternativeNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sans")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.SubjectAlternativeNames</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブジェクトの別名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="x509CertificateProperties.Validate " />
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
    <Member MemberName="ValidityInMonths">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ValidityInMonths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ValidityInMonths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.X509CertificateProperties.ValidityInMonths" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidityInMonths As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ValidityInMonths : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.X509CertificateProperties.ValidityInMonths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validity_months")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはか月以内に有効では、証明期間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>