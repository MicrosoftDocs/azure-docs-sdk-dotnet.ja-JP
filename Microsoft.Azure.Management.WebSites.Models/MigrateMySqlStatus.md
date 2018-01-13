<Type Name="MigrateMySqlStatus" FullName="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus">
  <TypeSignature Language="C#" Value="public class MigrateMySqlStatus : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrateMySqlStatus extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrateMySqlStatus&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MigrateMySqlStatus = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="84235-101">MySQL の移行の状態です。</span><span class="sxs-lookup"><span data-stu-id="84235-101">MySQL migration status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrateMySqlStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="84235-102">MigrateMySqlStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="84235-102">Initializes a new instance of the MigrateMySqlStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrateMySqlStatus (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; migrationOperationStatus = null, string operationId = null, Nullable&lt;bool&gt; localMySqlEnabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; migrationOperationStatus, string operationId, valuetype System.Nullable`1&lt;bool&gt; localMySqlEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.OperationStatus},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional migrationOperationStatus As Nullable(Of OperationStatus) = null, Optional operationId As String = null, Optional localMySqlEnabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus" Usage="new Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus (id, name, kind, type, migrationOperationStatus, operationId, localMySqlEnabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="migrationOperationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt;" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="localMySqlEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="84235-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="84235-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="84235-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="84235-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="84235-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="84235-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="84235-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="84235-106">Resource type.</span></span></param>
        <param name="migrationOperationStatus"><span data-ttu-id="84235-107">移行タスクの状態です。</span><span class="sxs-lookup"><span data-stu-id="84235-107">Status of the migration task.</span></span> <span data-ttu-id="84235-108">使用可能な値が含まれます: '処理中'、'失敗'、'成功'、'TimedOut'、'作成済み</span><span class="sxs-lookup"><span data-stu-id="84235-108">Possible values include: 'InProgress', 'Failed', 'Succeeded', 'TimedOut', 'Created'</span></span></param>
        <param name="operationId"><span data-ttu-id="84235-109">移行タスクの操作 ID。</span><span class="sxs-lookup"><span data-stu-id="84235-109">Operation ID for the migration task.</span></span></param>
        <param name="localMySqlEnabled"><span data-ttu-id="84235-110">MySql を有効になっているアプリに web アプリがある場合は true。</span><span class="sxs-lookup"><span data-stu-id="84235-110">True if the web app has in app MySql enabled</span></span></param>
        <summary>
            <span data-ttu-id="84235-111">MigrateMySqlStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="84235-111">Initializes a new instance of the MigrateMySqlStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMySqlEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LocalMySqlEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LocalMySqlEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.LocalMySqlEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalMySqlEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LocalMySqlEnabled : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.LocalMySqlEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localMySqlEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84235-112">MySql が有効になっているアプリに web アプリがある場合は true します。</span><span class="sxs-lookup"><span data-stu-id="84235-112">Gets true if the web app has in app MySql enabled</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationOperationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; MigrationOperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; MigrationOperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.MigrationOperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MigrationOperationStatus As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.MigrationOperationStatus : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.MigrationOperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.migrationOperationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84235-113">移行タスクの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="84235-113">Gets status of the migration task.</span></span> <span data-ttu-id="84235-114">使用可能な値が含まれます: '処理中'、'失敗'、'成功'、'TimedOut'、'作成済み</span><span class="sxs-lookup"><span data-stu-id="84235-114">Possible values include: 'InProgress', 'Failed', 'Succeeded', 'TimedOut', 'Created'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlStatus.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84235-115">移行タスクの操作 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="84235-115">Gets operation ID for the migration task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>