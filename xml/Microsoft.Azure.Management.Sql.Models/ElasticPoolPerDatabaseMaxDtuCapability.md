<Type Name="ElasticPoolPerDatabaseMaxDtuCapability" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability">
  <TypeSignature Language="C#" Value="public class ElasticPoolPerDatabaseMaxDtuCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolPerDatabaseMaxDtuCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolPerDatabaseMaxDtuCapability" />
  <TypeSignature Language="F#" Value="type ElasticPoolPerDatabaseMaxDtuCapability = class" />
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
            <span data-ttu-id="96f21-101">データベースごとの最大 DTU 機能です。</span><span class="sxs-lookup"><span data-stu-id="96f21-101">The max per-database DTU capability.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolPerDatabaseMaxDtuCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96f21-102">ElasticPoolPerDatabaseMaxDtuCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96f21-102">Initializes a new instance of the ElasticPoolPerDatabaseMaxDtuCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolPerDatabaseMaxDtuCapability (Nullable&lt;long&gt; limit = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt; supportedPerDatabaseMinDtus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; limit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt; supportedPerDatabaseMinDtus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.#ctor(System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional limit As Nullable(Of Long) = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedPerDatabaseMinDtus As IList(Of ElasticPoolPerDatabaseMinDtuCapability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability : Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability (limit, status, supportedPerDatabaseMinDtus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedPerDatabaseMinDtus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt;" />
      </Parameters>
      <Docs>
        <param name="limit"><span data-ttu-id="96f21-103">データベースあたり最大 Dtu です。</span><span class="sxs-lookup"><span data-stu-id="96f21-103">The maximum DTUs per database.</span></span></param>
        <param name="status"><span data-ttu-id="96f21-104">機能の状態。</span><span class="sxs-lookup"><span data-stu-id="96f21-104">The status of the capability.</span></span> <span data-ttu-id="96f21-105">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="96f21-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedPerDatabaseMinDtus"><span data-ttu-id="96f21-106">サポートされる最小データベース Dtu の一覧。</span><span class="sxs-lookup"><span data-stu-id="96f21-106">The list of supported min database DTUs.</span></span></param>
        <summary>
            <span data-ttu-id="96f21-107">ElasticPoolPerDatabaseMaxDtuCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96f21-107">Initializes a new instance of the ElasticPoolPerDatabaseMaxDtuCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96f21-108">データベースあたり最大 Dtu を取得します。</span><span class="sxs-lookup"><span data-stu-id="96f21-108">Gets the maximum DTUs per database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96f21-109">機能の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="96f21-109">Gets the status of the capability.</span></span> <span data-ttu-id="96f21-110">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="96f21-110">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedPerDatabaseMinDtus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt; SupportedPerDatabaseMinDtus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt; SupportedPerDatabaseMinDtus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.SupportedPerDatabaseMinDtus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedPerDatabaseMinDtus As IList(Of ElasticPoolPerDatabaseMinDtuCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedPerDatabaseMinDtus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability.SupportedPerDatabaseMinDtus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedPerDatabaseMinDtus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMinDtuCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96f21-111">サポートされる最小データベース Dtu の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="96f21-111">Gets the list of supported min database DTUs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>