<Type Name="VaultCertificate" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate">
  <TypeSignature Language="C#" Value="public class VaultCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultCertificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultCertificate" />
  <TypeSignature Language="F#" Value="type VaultCertificate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key Vault に単一の証明書参照を記述し、VM に証明書がある必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VaultCertificate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate (string certificateUrl = null, string certificateStore = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificateUrl, string certificateStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificateUrl As String = null, Optional certificateStore As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate (certificateUrl, certificateStore)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateUrl" Type="System.String" />
        <Parameter Name="certificateStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateUrl">正しく書式設定された証明書を含む Key Vault にシークレットを参照する URL です。</param>
        <param name="certificateStore">Linux で空のままで、証明書を追加する Windows では、LocalMachine 証明書ストア。</param>
        <summary>
            VaultCertificate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateStore">
      <MemberSignature Language="C#" Value="public string CertificateStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.CertificateStore" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateStore As String" />
      <MemberSignature Language="F#" Value="member this.CertificateStore : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.CertificateStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または LocalMachine Windows では、空のままに Linux 上の証明書を追加で証明書ストアを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正しく書式設定された証明書を含む Key Vault にシークレットを参照する URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>