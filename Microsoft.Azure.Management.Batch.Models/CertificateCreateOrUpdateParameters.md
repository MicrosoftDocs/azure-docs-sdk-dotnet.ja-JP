<Type Name="CertificateCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class CertificateCreateOrUpdateParameters : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCreateOrUpdateParameters extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCreateOrUpdateParameters&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type CertificateCreateOrUpdateParameters = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            証明書に関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters (string data, string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string data, string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (data As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional etag As String = null, Optional thumbprintAlgorithm As String = null, Optional thumbprint As String = null, Optional format As CertificateFormat = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters : string * string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters (data, id, name, type, etag, thumbprintAlgorithm, thumbprint, format, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="data">証明書の base64 でエンコードされた内容。</param>
        <param name="id">リソースの ID。</param>
        <param name="name">リソースの名前。</param>
        <param name="type">リソースの型。</param>
        <param name="etag">同時実行ステートメントの使用、リソースの ETag。</param>
        <param name="thumbprintAlgorithm">証明書のサムプリントのアルゴリズム</param>
        <param name="thumbprint">証明書の拇印</param>
        <param name="format">証明書の Cer または Pfx のいずれかの形式。 省略した場合、既定値は Pfx にします。 使用可能な値が含まれます: 'Pfx'、'Cer'</param>
        <param name="password">証明書の秘密キーにアクセスするパスワードです。</param>
        <summary>
            CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の base64 でエンコードされたコンテンツを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            最大サイズは、10 KB です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の Cer または Pfx のいずれかの形式を設定します。 省略した場合、既定値は Pfx にします。 使用可能な値が含まれます: 'Pfx'、'Cer'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の秘密キーにアクセスするパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            証明書の形式が証明書の形式が cer である場合は省略する必要があります pfx である場合に必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、証明書の拇印
            </summary>
        <value>To be added.</value>
        <remarks>
            これにより、名と拇印が一致する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、証明書のサムプリントのアルゴリズム
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、証明書名の最初の部分と一致する必要があります。
            'SHA1' 現在必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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