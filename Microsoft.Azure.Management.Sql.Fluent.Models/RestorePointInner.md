<Type Name="RestorePointInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner">
  <TypeSignature Language="C#" Value="public class RestorePointInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestorePointInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RestorePointInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RestorePointInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b3650-101">Azure SQL データベースを表すポイントを復元します。</span><span class="sxs-lookup"><span data-stu-id="b3650-101">Represents an Azure SQL Database restore point.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestorePointInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3650-102">RestorePointInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3650-102">Initializes a new instance of the RestorePointInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestorePointInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt; restorePointType = null, Nullable&lt;DateTime&gt; restorePointCreationDate = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt; restorePointType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; restorePointCreationDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional restorePointType As Nullable(Of RestorePointTypes) = null, Optional restorePointCreationDate As Nullable(Of DateTime) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner (location, id, name, type, tags, restorePointType, restorePointCreationDate, earliestRestoreDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="restorePointType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt;" />
        <Parameter Name="restorePointCreationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="restorePointType"><span data-ttu-id="b3650-103">Azure SQL データベースの復元ポイントの復元ポイントの種類。</span><span class="sxs-lookup"><span data-stu-id="b3650-103">The restore point type of the Azure SQL database restore point.</span></span> <span data-ttu-id="b3650-104">使用可能な値が含まれます: 'DISCRETE'、'CONTINUOUS'</span><span class="sxs-lookup"><span data-stu-id="b3650-104">Possible values include: 'DISCRETE', 'CONTINUOUS'</span></span></param>
        <param name="restorePointCreationDate"><span data-ttu-id="b3650-105">ポイントの作成時刻 (ISO8601 形式) を復元します。</span><span class="sxs-lookup"><span data-stu-id="b3650-105">Restore point creation time (ISO8601 format).</span></span> <span data-ttu-id="b3650-106">ときに設定されます restorePointType CONTINUOUS を = です。</span><span class="sxs-lookup"><span data-stu-id="b3650-106">Populated when restorePointType = CONTINUOUS.</span></span>
            <span data-ttu-id="b3650-107">その他の場合は NULL が返されます。</span><span class="sxs-lookup"><span data-stu-id="b3650-107">Null otherwise.</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="b3650-108">最も早い時刻 (ISO8601 形式) を復元します。</span><span class="sxs-lookup"><span data-stu-id="b3650-108">Earliest restore time (ISO8601 format).</span></span> <span data-ttu-id="b3650-109">ときに設定されます restorePointType 不連続値を = です。</span><span class="sxs-lookup"><span data-stu-id="b3650-109">Populated when restorePointType = DISCRETE.</span></span> <span data-ttu-id="b3650-110">その他の場合は NULL が返されます。</span><span class="sxs-lookup"><span data-stu-id="b3650-110">Null otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="b3650-111">RestorePointInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3650-111">Initializes a new instance of the RestorePointInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.earliestRestoreDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3650-112">取得は最も早い時刻 (ISO8601 形式) を復元します。</span><span class="sxs-lookup"><span data-stu-id="b3650-112">Gets earliest restore time (ISO8601 format).</span></span> <span data-ttu-id="b3650-113">ときに設定されます restorePointType 不連続値を = です。</span><span class="sxs-lookup"><span data-stu-id="b3650-113">Populated when restorePointType = DISCRETE.</span></span> <span data-ttu-id="b3650-114">その他の場合は NULL が返されます。</span><span class="sxs-lookup"><span data-stu-id="b3650-114">Null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointCreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestorePointCreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestorePointCreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.RestorePointCreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePointCreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestorePointCreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.RestorePointCreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restorePointCreationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3650-115">取得復元ポイント作成時刻 (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="b3650-115">Gets restore point creation time (ISO8601 format).</span></span> <span data-ttu-id="b3650-116">ときに設定されます restorePointType CONTINUOUS を = です。</span><span class="sxs-lookup"><span data-stu-id="b3650-116">Populated when restorePointType = CONTINUOUS.</span></span> <span data-ttu-id="b3650-117">その他の場合は NULL が返されます。</span><span class="sxs-lookup"><span data-stu-id="b3650-117">Null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt; RestorePointType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt; RestorePointType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.RestorePointType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePointType As Nullable(Of RestorePointTypes)" />
      <MemberSignature Language="F#" Value="member this.RestorePointType : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner.RestorePointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restorePointType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3650-118">Azure SQL データベースの復元ポイントの復元ポイントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3650-118">Gets the restore point type of the Azure SQL database restore point.</span></span> <span data-ttu-id="b3650-119">使用可能な値が含まれます: 'DISCRETE'、'CONTINUOUS'</span><span class="sxs-lookup"><span data-stu-id="b3650-119">Possible values include: 'DISCRETE', 'CONTINUOUS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>