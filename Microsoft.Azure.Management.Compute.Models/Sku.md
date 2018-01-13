<Type Name="Sku" FullName="Microsoft.Azure.Management.Compute.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セットの sku をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (string name = null, string tier = null, Nullable&lt;long&gt; capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, valuetype System.Nullable`1&lt;int64&gt; capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Sku.#ctor(System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional capacity As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Sku : string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Compute.Models.Sku" Usage="new Microsoft.Azure.Management.Compute.Models.Sku (name, tier, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Sku の名前です。</param>
        <param name="tier">スケール セット内の仮想マシンの層を指定します。&lt;ブラジル/&gt;&lt;ブラジル/&gt;使用可能な値:&lt;ブラジル/&gt;&lt;ブラジル/&gt; **標準**&lt;ブラジル/&gt;&lt;ブラジル/&gt; **基本**</param>
        <param name="capacity">スケール セット内の仮想マシンの数を指定します。</param>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Sku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Sku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、スケール セット内の仮想マシンの数を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
        <summary>
            取得または sku の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、スケール セット内の仮想マシンの層を指定します。&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;使用可能な値:&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;**標準**&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;**基本**
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>