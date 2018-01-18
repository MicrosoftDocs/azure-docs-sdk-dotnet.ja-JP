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
            <span data-ttu-id="811b2-101">Azure SQL Database の Transparent Data Encryption を表します。</span><span class="sxs-lookup"><span data-stu-id="811b2-101">Represents an Azure SQL Database Transparent Data Encryption .</span></span>
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
            <span data-ttu-id="811b2-102">TransparentDataEncryptionInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="811b2-102">Initializes a new instance of the TransparentDataEncryptionInner class.</span></span>
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
        <param name="name"><span data-ttu-id="811b2-103">リソース名</span><span class="sxs-lookup"><span data-stu-id="811b2-103">Resource name</span></span></param>
        <param name="id"><span data-ttu-id="811b2-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="811b2-104">The resource ID.</span></span></param>
        <param name="status"><span data-ttu-id="811b2-105">Azure SQL データベース透過的なデータ暗号化の状態です。</span><span class="sxs-lookup"><span data-stu-id="811b2-105">The status of the Azure SQL Database Transparent Data Encryption.</span></span> <span data-ttu-id="811b2-106">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="811b2-106">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="811b2-107">TransparentDataEncryptionInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="811b2-107">Initializes a new instance of the TransparentDataEncryptionInner class.</span></span>
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
            <span data-ttu-id="811b2-108">取得または Azure SQL データベース透過的なデータ暗号化の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="811b2-108">Gets or sets the status of the Azure SQL Database Transparent Data Encryption.</span></span> <span data-ttu-id="811b2-109">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="811b2-109">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>