<Type Name="PublicCertificateInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner">
  <TypeSignature Language="C#" Value="public class PublicCertificateInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicCertificateInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicCertificateInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PublicCertificateInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicCertificateInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicCertificateInner (string id = null, string name = null, string kind = null, string type = null, string blob = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; publicCertificateLocation = null, string thumbprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string blob, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; publicCertificateLocation, string thumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional blob As String = null, Optional publicCertificateLocation As Nullable(Of PublicCertificateLocation) = null, Optional thumbprint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner (id, name, kind, type, blob, publicCertificateLocation, thumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="blob" Type="System.String" />
        <Parameter Name="publicCertificateLocation" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt;" />
        <Parameter Name="thumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="blob">To be added.</param>
        <param name="publicCertificateLocation">To be added.</param>
        <param name="thumbprint">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blob">
      <MemberSignature Language="C#" Value="public string Blob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Blob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.Blob" />
      <MemberSignature Language="VB.NET" Value="Public Property Blob As String" />
      <MemberSignature Language="F#" Value="member this.Blob : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.Blob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicCertificateLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; PublicCertificateLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; PublicCertificateLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.PublicCertificateLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicCertificateLocation As Nullable(Of PublicCertificateLocation)" />
      <MemberSignature Language="F#" Value="member this.PublicCertificateLocation : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.PublicCertificateLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicCertificateLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.PublicCertificateInner.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>