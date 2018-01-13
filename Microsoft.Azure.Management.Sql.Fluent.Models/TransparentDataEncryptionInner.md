<Type Name="TransparentDataEncryptionInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryptionInner : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryptionInner extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryptionInner&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionInner = class&#xA;    inherit SqlSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure SQL Database の Transparent Data Encryption を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TransparentDataEncryptionInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionInner (string name = null, string id = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional status As Nullable(Of TransparentDataEncryptionStates) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner : string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner (name, id, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;" />
      </Parameters>
      <Docs>
        <param name="name">リソース名</param>
        <param name="id">リソース id です。</param>
        <param name="status">Azure SQL データベース透過的なデータ暗号化の状態です。 使用可能な値が含まれます: 'Enabled'、'Disabled'</param>
        <summary>
            TransparentDataEncryptionInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of TransparentDataEncryptionStates)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure SQL データベース透過的なデータ暗号化の状態を設定します。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>