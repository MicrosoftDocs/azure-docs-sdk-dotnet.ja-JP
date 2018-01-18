<Type Name="TransparentDataEncryptionActivity" FullName="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryptionActivity : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryptionActivity extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryptionActivity&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionActivity = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="70e40-101">データベースの透過的なデータ暗号化のスキャンを表します。</span><span class="sxs-lookup"><span data-stu-id="70e40-101">Represents a database transparent data encryption Scan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70e40-102">TransparentDataEncryptionActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70e40-102">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity (string id = null, string name = null, string type = null, string location = null, string status = null, Nullable&lt;double&gt; percentComplete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, string status, valuetype System.Nullable`1&lt;float64&gt; percentComplete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional status As String = null, Optional percentComplete As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity : string * string * string * string * string * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity" Usage="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity (id, name, type, location, status, percentComplete)" />
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
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="70e40-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="70e40-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="70e40-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="70e40-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="70e40-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="70e40-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="70e40-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="70e40-106">Resource location.</span></span></param>
        <param name="status"><span data-ttu-id="70e40-107">データベースの状態。</span><span class="sxs-lookup"><span data-stu-id="70e40-107">The status of the database.</span></span> <span data-ttu-id="70e40-108">使用可能な値が含まれます: 'の暗号化'、'復号化'</span><span class="sxs-lookup"><span data-stu-id="70e40-108">Possible values include: 'Encrypting', 'Decrypting'</span></span></param>
        <param name="percentComplete"><span data-ttu-id="70e40-109">データベースの透過的なデータ暗号化のスキャンの完了した割合です。</span><span class="sxs-lookup"><span data-stu-id="70e40-109">The percent complete of the transparent data encryption scan for a database.</span></span></param>
        <summary>
            <span data-ttu-id="70e40-110">TransparentDataEncryptionActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70e40-110">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Location" />
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
            <span data-ttu-id="70e40-111">リソースの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="70e40-111">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="70e40-112">データベースの透過的なデータ暗号化のスキャンの完了した割合を取得します。</span><span class="sxs-lookup"><span data-stu-id="70e40-112">Gets the percent complete of the transparent data encryption scan for a database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Status" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70e40-113">データベースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="70e40-113">Gets the status of the database.</span></span> <span data-ttu-id="70e40-114">使用可能な値が含まれます: 'の暗号化'、'復号化'</span><span class="sxs-lookup"><span data-stu-id="70e40-114">Possible values include: 'Encrypting', 'Decrypting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>