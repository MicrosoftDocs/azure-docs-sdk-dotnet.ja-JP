<Type Name="CustomDomain" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain">
  <TypeSignature Language="C#" Value="public class CustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDomain extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDomain" />
  <TypeSignature Language="F#" Value="type CustomDomain = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このストレージ アカウントに割り当てられているカスタム ドメイン。 これは、更新プログラムを使用して設定できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CustomDomain クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomain (string name, Nullable&lt;bool&gt; useSubDomain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional useSubDomain As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain (name, useSubDomain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">取得またはストレージ アカウントに割り当てられているカスタム ドメイン名を設定します。 名前は、CNAME ソースです。</param>
        <param name="useSubDomain">間接 CName 検証が有効になっているかどうかを示します。 既定値は false です。 更新プログラムにのみ設定する必要があります。</param>
        <summary>
            CustomDomain クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得またはストレージ アカウントに割り当てられているカスタム ドメイン名を設定します。 名前は、CNAME ソースです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSubDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseSubDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseSubDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.UseSubDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSubDomain As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseSubDomain : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.UseSubDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useSubDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、間接 CName 検証が有効になっているかどうかを示します。 既定値は false です。 更新プログラムにのみ設定する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="customDomain.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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