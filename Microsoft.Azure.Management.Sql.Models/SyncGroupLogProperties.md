<Type Name="SyncGroupLogProperties" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties">
  <TypeSignature Language="C#" Value="public class SyncGroupLogProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupLogProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupLogProperties" />
  <TypeSignature Language="F#" Value="type SyncGroupLogProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9deee-101">Azure SQL データベースの同期グループ ログのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="9deee-101">Properties of an Azure SQL Database sync group log.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupLogProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9deee-102">SyncGroupLogProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9deee-102">Initializes a new instance of the SyncGroupLogProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupLogProperties (Nullable&lt;DateTime&gt; timestamp = null, string type = null, string source = null, string details = null, Nullable&lt;Guid&gt; tracingId = null, string operationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string type, string source, string details, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tracingId, string operationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.#ctor(System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timestamp As Nullable(Of DateTime) = null, Optional type As String = null, Optional source As String = null, Optional details As String = null, Optional tracingId As Nullable(Of Guid) = null, Optional operationStatus As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties : Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties (timestamp, type, source, details, tracingId, operationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="tracingId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="operationStatus" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timestamp"><span data-ttu-id="9deee-103">同期グループ ログのタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="9deee-103">Timestamp of the sync group log.</span></span></param>
        <param name="type"><span data-ttu-id="9deee-104">同期グループ ログの種類です。</span><span class="sxs-lookup"><span data-stu-id="9deee-104">Type of the sync group log.</span></span> <span data-ttu-id="9deee-105">使用可能な値が含まれます: 'すべて'、'Error'、'警告'、'成功'</span><span class="sxs-lookup"><span data-stu-id="9deee-105">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span></param>
        <param name="source"><span data-ttu-id="9deee-106">同期グループ ログのソースです。</span><span class="sxs-lookup"><span data-stu-id="9deee-106">Source of the sync group log.</span></span></param>
        <param name="details"><span data-ttu-id="9deee-107">同期グループ ログの詳細です。</span><span class="sxs-lookup"><span data-stu-id="9deee-107">Details of the sync group log.</span></span></param>
        <param name="tracingId"><span data-ttu-id="9deee-108">同期グループ ログの TracingId します。</span><span class="sxs-lookup"><span data-stu-id="9deee-108">TracingId of the sync group log.</span></span></param>
        <param name="operationStatus"><span data-ttu-id="9deee-109">同期グループ ログの OperationStatus します。</span><span class="sxs-lookup"><span data-stu-id="9deee-109">OperationStatus of the sync group log.</span></span></param>
        <summary>
            <span data-ttu-id="9deee-110">SyncGroupLogProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9deee-110">Initializes a new instance of the SyncGroupLogProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-111">同期グループ ログの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-111">Gets details of the sync group log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public string OperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationStatus As String" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.OperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-112">同期グループ ログの operationStatus を取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-112">Gets operationStatus of the sync group log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-113">同期グループ ログのソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-113">Gets source of the sync group log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-114">同期グループ ログのタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-114">Gets timestamp of the sync group log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TracingId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TracingId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TracingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.TracingId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TracingId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TracingId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.TracingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tracingId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-115">TracingId の同期グループ ログを取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-115">Gets tracingId of the sync group log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9deee-116">同期グループ ログの型を取得します。</span><span class="sxs-lookup"><span data-stu-id="9deee-116">Gets type of the sync group log.</span></span> <span data-ttu-id="9deee-117">使用可能な値が含まれます: 'すべて'、'Error'、'警告'、'成功'</span><span class="sxs-lookup"><span data-stu-id="9deee-117">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>