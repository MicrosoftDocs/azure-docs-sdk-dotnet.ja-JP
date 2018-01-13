<Type Name="CertificateOperation" FullName="Microsoft.Azure.KeyVault.Models.CertificateOperation">
  <TypeSignature Language="C#" Value="public class CertificateOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperation" />
  <TypeSignature Language="F#" Value="type CertificateOperation = class" />
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
            非同期要求が発生した場合は、証明書の操作が返されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificateOperation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperation (string id = null, Microsoft.Azure.KeyVault.Models.IssuerParameters issuerParameters = null, byte[] csr = null, Nullable&lt;bool&gt; cancellationRequested = null, string status = null, string statusDetails = null, Microsoft.Azure.KeyVault.Models.Error error = null, string target = null, string requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.KeyVault.Models.IssuerParameters issuerParameters, unsigned int8[] csr, valuetype System.Nullable`1&lt;bool&gt; cancellationRequested, string status, string statusDetails, class Microsoft.Azure.KeyVault.Models.Error error, string target, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperation.#ctor(System.String,Microsoft.Azure.KeyVault.Models.IssuerParameters,System.Byte[],System.Nullable{System.Boolean},System.String,System.String,Microsoft.Azure.KeyVault.Models.Error,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateOperation : string * Microsoft.Azure.KeyVault.Models.IssuerParameters * byte[] * Nullable&lt;bool&gt; * string * string * Microsoft.Azure.KeyVault.Models.Error * string * string -&gt; Microsoft.Azure.KeyVault.Models.CertificateOperation" Usage="new Microsoft.Azure.KeyVault.Models.CertificateOperation (id, issuerParameters, csr, cancellationRequested, status, statusDetails, error, target, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="issuerParameters" Type="Microsoft.Azure.KeyVault.Models.IssuerParameters" />
        <Parameter Name="csr" Type="System.Byte[]" />
        <Parameter Name="cancellationRequested" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.KeyVault.Models.Error" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">証明書の id です。</param>
        <param name="issuerParameters">パラメーターが X509 の発行者の証明書のコンポーネントです。</param>
        <param name="csr">証明書署名要求 (CSR) 証明書の操作で使用されています。</param>
        <param name="cancellationRequested">証明書の操作のキャンセルが要求されたかどうかを示します。</param>
        <param name="status">証明書の操作の状態です。</param>
        <param name="statusDetails">証明書の操作の詳細なステータス。</param>
        <param name="error">エラーが発生、証明書の操作中に存在する場合。</param>
        <param name="target">証明書の操作の結果を格納する場所です。</param>
        <param name="requestId">証明書の操作の識別子。</param>
        <summary>
            CertificateOperation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancellationRequested">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CancellationRequested { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CancellationRequested" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.CancellationRequested" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationRequested As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CancellationRequested : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.CancellationRequested" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cancellation_requested")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、証明書の操作のキャンセルが要求されたかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOperationIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.CertificateOperationIdentifier CertificateOperationIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.CertificateOperationIdentifier CertificateOperationIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.CertificateOperationIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateOperationIdentifier As CertificateOperationIdentifier" />
      <MemberSignature Language="F#" Value="member this.CertificateOperationIdentifier : Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.CertificateOperationIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.CertificateOperationIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の操作の識別子
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public byte[] Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As Byte()" />
      <MemberSignature Language="F#" Value="member this.Csr : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の署名証明書の操作で使用されている要求 (CSR) を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.Error Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.Error Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Error" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.KeyVault.Models.Error with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の操作中に存在する場合に、エラーが発生しましたを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.IssuerParameters IssuerParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.IssuerParameters IssuerParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.IssuerParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerParameters As IssuerParameters" />
      <MemberSignature Language="F#" Value="member this.IssuerParameters : Microsoft.Azure.KeyVault.Models.IssuerParameters with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.IssuerParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.IssuerParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のパラメーター、発行者の X509 証明書のコンポーネントです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request_id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の操作の識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の操作の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の操作の詳細なステータスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperation.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperation.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の操作の結果を格納する場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>