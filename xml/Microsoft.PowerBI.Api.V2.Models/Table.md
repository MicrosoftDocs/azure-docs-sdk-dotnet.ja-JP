<Type Name="Table" FullName="Microsoft.PowerBI.Api.V2.Models.Table">
  <TypeSignature Language="C#" Value="public class Table" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Table extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.Models.Table" />
  <TypeSignature Language="VB.NET" Value="Public Class Table" />
  <TypeSignature Language="F#" Value="type Table = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Table ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Models.Table.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Table (string name, System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt; columns, System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt; rows = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.PowerBI.Api.V2.Models.Column&gt; columns, class System.Collections.Generic.IList`1&lt;class Microsoft.PowerBI.Api.V2.Models.Row&gt; rows) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Models.Table.#ctor(System.String,System.Collections.Generic.IList{Microsoft.PowerBI.Api.V2.Models.Column},System.Collections.Generic.IList{Microsoft.PowerBI.Api.V2.Models.Row})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, columns As IList(Of Column), Optional rows As IList(Of Row) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.PowerBI.Api.V2.Models.Table : string * System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt; * System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt; -&gt; Microsoft.PowerBI.Api.V2.Models.Table" Usage="new Microsoft.PowerBI.Api.V2.Models.Table (name, columns, rows)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt;" />
        <Parameter Name="rows" Type="System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="columns">To be added.</param>
        <param name="rows">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt; Columns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.PowerBI.Api.V2.Models.Column&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.PowerBI.Api.V2.Models.Table.Columns" />
      <MemberSignature Language="VB.NET" Value="Public Property Columns As IList(Of Column)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt; with get, set" Usage="Microsoft.PowerBI.Api.V2.Models.Table.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Column&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.PowerBI.Api.V2.Models.Table.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.PowerBI.Api.V2.Models.Table.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
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
    <Member MemberName="Rows">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt; Rows { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.PowerBI.Api.V2.Models.Row&gt; Rows" />
      <MemberSignature Language="DocId" Value="P:Microsoft.PowerBI.Api.V2.Models.Table.Rows" />
      <MemberSignature Language="VB.NET" Value="Public Property Rows As IList(Of Row)" />
      <MemberSignature Language="F#" Value="member this.Rows : System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt; with get, set" Usage="Microsoft.PowerBI.Api.V2.Models.Table.Rows" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rows")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.PowerBI.Api.V2.Models.Row&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Models.Table.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="table.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>