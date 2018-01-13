<Type Name="CidrIpAddress" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress">
  <TypeSignature Language="C#" Value="public class CidrIpAddress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CidrIpAddress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress" />
  <TypeSignature Language="VB.NET" Value="Public Class CidrIpAddress" />
  <TypeSignature Language="F#" Value="type CidrIpAddress = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            CIDR Ip アドレス
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CidrIpAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CidrIpAddress クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CidrIpAddress (string baseIpAddress = null, Nullable&lt;int&gt; prefixLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baseIpAddress, valuetype System.Nullable`1&lt;int32&gt; prefixLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional baseIpAddress As String = null, Optional prefixLength As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress (baseIpAddress, prefixLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseIpAddress" Type="System.String" />
        <Parameter Name="prefixLength" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="baseIpAddress">自体 Ip アドレス。</param>
        <param name="prefixLength">Ip アドレスのプレフィックスの長さ。</param>
        <summary>
            CidrIpAddress クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseIpAddress">
      <MemberSignature Language="C#" Value="public string BaseIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.BaseIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.BaseIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.BaseIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="baseIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自体 ip アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefixLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PrefixLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PrefixLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.PrefixLength" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefixLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PrefixLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CidrIpAddress.PrefixLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="prefixLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ip アドレスのプレフィックスの長さを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>