<Type Name="Error" FullName="Microsoft.Azure.Management.PowerBIEmbedded.Models.Error">
  <TypeSignature Language="C#" Value="public class Error" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Error extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error" />
  <TypeSignature Language="VB.NET" Value="Public Class Error" />
  <TypeSignature Language="F#" Value="type Error = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Error ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Error (string code = null, string message = null, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional target As String = null, Optional details As IList(Of ErrorDetail) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.PowerBIEmbedded.Models.Error : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.Error" Usage="new Microsoft.Azure.Management.PowerBIEmbedded.Models.Error (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt;" />
      </Parameters>
      <Docs>
        <param name="code">To be added.</param>
        <param name="message">To be added.</param>
        <param name="target">To be added.</param>
        <param name="details">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
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
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of ErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt; with get, set" Usage="Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.ErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
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
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.PowerBIEmbedded.Models.Error.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>