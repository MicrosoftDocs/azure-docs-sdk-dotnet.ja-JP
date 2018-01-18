<Type Name="TransparentDataEncryption" FullName="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryption : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryption extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryption&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryption = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="45dc3-101">データベースの透過的なデータの暗号化構成を表します。</span><span class="sxs-lookup"><span data-stu-id="45dc3-101">Represents a database transparent data encryption configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45dc3-102">TransparentDataEncryption クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45dc3-102">Initializes a new instance of the TransparentDataEncryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryption (string id = null, string name = null, string type = null, string location = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional status As Nullable(Of TransparentDataEncryptionStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" Usage="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption (id, name, type, location, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="45dc3-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="45dc3-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="45dc3-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="45dc3-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="45dc3-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="45dc3-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="45dc3-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="45dc3-106">Resource location.</span></span></param>
        <param name="status"><span data-ttu-id="45dc3-107">データベースの透過的なデータ暗号化の状態です。</span><span class="sxs-lookup"><span data-stu-id="45dc3-107">The status of the database transparent data encryption.</span></span> <span data-ttu-id="45dc3-108">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="45dc3-108">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="45dc3-109">TransparentDataEncryption クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45dc3-109">Initializes a new instance of the TransparentDataEncryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45dc3-110">リソースの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="45dc3-110">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of TransparentDataEncryptionStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45dc3-111">取得またはデータベースの透過的なデータ暗号化の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="45dc3-111">Gets or sets the status of the database transparent data encryption.</span></span> <span data-ttu-id="45dc3-112">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="45dc3-112">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>