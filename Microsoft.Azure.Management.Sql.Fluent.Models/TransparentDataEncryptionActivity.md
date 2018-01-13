<Type Name="TransparentDataEncryptionActivity" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryptionActivity : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryptionActivity extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryptionActivity&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionActivity = class&#xA;    inherit SqlSubResource" />
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
            Azure SQL データベース透過的なデータ暗号化のスキャンを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TransparentDataEncryptionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity (string name = null, string id = null, string status = null, Nullable&lt;double&gt; percentComplete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string status, valuetype System.Nullable`1&lt;float64&gt; percentComplete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.#ctor(System.String,System.String,System.String,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional status As String = null, Optional percentComplete As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity : string * string * string * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity (name, id, status, percentComplete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="name">リソース名</param>
        <param name="id">リソース id です。</param>
        <param name="status">Azure SQL データベースの状態です。 使用可能な値が含まれます: 'の暗号化'、'復号化'</param>
        <param name="percentComplete">Azure SQL データベースの透過的なデータ暗号化のスキャンの完了した割合です。</param>
        <summary>
            TransparentDataEncryptionActivity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースの透過的なデータ暗号化のスキャンの完全な割合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.Status" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースの状態を取得します。 使用可能な値が含まれます: 'の暗号化'、'復号化'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>