<Type Name="ServiceObjectiveInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner">
  <TypeSignature Language="C#" Value="public class ServiceObjectiveInner : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceObjectiveInner extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceObjectiveInner&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type ServiceObjectiveInner = class&#xA;    inherit SqlSubResource" />
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
            <span data-ttu-id="1fd60-101">Azure SQL データベースのサービス目標を表します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-101">Represents an Azure SQL Database Service Objective.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjectiveInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-102">ServiceObjectiveInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-102">Initializes a new instance of the ServiceObjectiveInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjectiveInner (string name = null, string id = null, string serviceObjectiveName = null, Nullable&lt;bool&gt; isDefault = null, Nullable&lt;bool&gt; isSystem = null, string description = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string serviceObjectiveName, valuetype System.Nullable`1&lt;bool&gt; isDefault, valuetype System.Nullable`1&lt;bool&gt; isSystem, string description, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional serviceObjectiveName As String = null, Optional isDefault As Nullable(Of Boolean) = null, Optional isSystem As Nullable(Of Boolean) = null, Optional description As String = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner : string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner (name, id, serviceObjectiveName, isDefault, isSystem, description, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="serviceObjectiveName" Type="System.String" />
        <Parameter Name="isDefault" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isSystem" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="1fd60-103">リソース名</span><span class="sxs-lookup"><span data-stu-id="1fd60-103">Resource name</span></span></param>
        <param name="id"><span data-ttu-id="1fd60-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="1fd60-104">The resource ID.</span></span></param>
        <param name="serviceObjectiveName"><span data-ttu-id="1fd60-105">サービス目標の名前。</span><span class="sxs-lookup"><span data-stu-id="1fd60-105">The name for the service objective.</span></span></param>
        <param name="isDefault"><span data-ttu-id="1fd60-106">サービス レベル目標が既定のサービス目標かどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-106">Gets whether the service level objective is the default service objective.</span></span></param>
        <param name="isSystem"><span data-ttu-id="1fd60-107">サービス レベル目標がシステムのサービス目標かどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-107">Gets whether the service level objective is a system service objective.</span></span></param>
        <param name="description"><span data-ttu-id="1fd60-108">サービス レベル目標の説明です。</span><span class="sxs-lookup"><span data-stu-id="1fd60-108">The description for the service level objective.</span></span></param>
        <param name="enabled"><span data-ttu-id="1fd60-109">サービス レベル目標が有効になっているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-109">Gets whether the service level objective is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="1fd60-110">ServiceObjectiveInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-110">Initializes a new instance of the ServiceObjectiveInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-111">サービス レベル目標の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-111">Gets the description for the service level objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-112">サービス レベル目標が有効になっているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-112">Gets whether the service level objective is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.IsDefault" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefault As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefault : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.IsDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-113">サービス レベル目標が既定のサービス目標かどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-113">Gets whether the service level objective is the default service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSystem">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.IsSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSystem As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSystem : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.IsSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-114">サービス レベル目標がシステムのサービス目標かどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-114">Gets whether the service level objective is a system service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string ServiceObjectiveName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.ServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceObjectiveName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner.ServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1fd60-115">サービス目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1fd60-115">Gets the name for the service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>