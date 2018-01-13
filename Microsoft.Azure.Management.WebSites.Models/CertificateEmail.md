<Type Name="CertificateEmail" FullName="Microsoft.Azure.Management.WebSites.Models.CertificateEmail">
  <TypeSignature Language="C#" Value="public class CertificateEmail : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateEmail extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CertificateEmail" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateEmail&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type CertificateEmail = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            SSL 証明書の電子メール アドレス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateEmail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificateEmail クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateEmail (string id = null, string name = null, string kind = null, string type = null, string emailId = null, Nullable&lt;DateTime&gt; timeStamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string emailId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeStamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional emailId As String = null, Optional timeStamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CertificateEmail : string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CertificateEmail" Usage="new Microsoft.Azure.Management.WebSites.Models.CertificateEmail (id, name, kind, type, emailId, timeStamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="emailId" Type="System.String" />
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="emailId">電子メール id です。</param>
        <param name="timeStamp">時刻のタイムスタンプ。</param>
        <summary>
            CertificateEmail クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailId">
      <MemberSignature Language="C#" Value="public string EmailId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.EmailId" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailId As String" />
      <MemberSignature Language="F#" Value="member this.EmailId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateEmail.EmailId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または電子メール id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateEmail.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタイムスタンプを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>