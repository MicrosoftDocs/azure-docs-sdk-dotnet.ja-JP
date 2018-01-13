<Type Name="CertificateGetHeaders" FullName="Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders">
  <TypeSignature Language="C#" Value="public class CertificateGetHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateGetHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateGetHeaders" />
  <TypeSignature Language="F#" Value="type CertificateGetHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            取得操作のヘッダーを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateGetHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificateGetHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateGetHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders : string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag">ETag HTTP 応答ヘッダー。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 具体的には、If-match または [なし]-If-match ヘッダーのいずれかに ETag を渡すことができます。</param>
        <summary>
            CertificateGetHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ETag HTTP 応答ヘッダーを設定します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 具体的には、If-match または [なし]-If-match ヘッダーのいずれかに ETag を渡すことができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>