<Type Name="EditionCapability" FullName="Microsoft.Azure.Management.Sql.Models.EditionCapability">
  <TypeSignature Language="C#" Value="public class EditionCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EditionCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.EditionCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class EditionCapability" />
  <TypeSignature Language="F#" Value="type EditionCapability = class" />
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
            <span data-ttu-id="60cfd-101">データベース エディションの機能です。</span><span class="sxs-lookup"><span data-stu-id="60cfd-101">The database edition capabilities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EditionCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.EditionCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60cfd-102">EditionCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-102">Initializes a new instance of the EditionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EditionCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt; supportedServiceLevelObjectives = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt; supportedServiceLevelObjectives, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.EditionCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedServiceLevelObjectives As IList(Of ServiceObjectiveCapability) = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.EditionCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.EditionCapability" Usage="new Microsoft.Azure.Management.Sql.Models.EditionCapability (name, status, supportedServiceLevelObjectives, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedServiceLevelObjectives" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt;" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="60cfd-103">エディション名。</span><span class="sxs-lookup"><span data-stu-id="60cfd-103">The edition name.</span></span></param>
        <param name="status"><span data-ttu-id="60cfd-104">エディションの状態です。</span><span class="sxs-lookup"><span data-stu-id="60cfd-104">The status of the edition.</span></span> <span data-ttu-id="60cfd-105">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="60cfd-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedServiceLevelObjectives"><span data-ttu-id="60cfd-106">エディションのサポートされているサービス目標の一覧。</span><span class="sxs-lookup"><span data-stu-id="60cfd-106">The list of supported service objectives for the edition.</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="60cfd-107">かどうかエディションのゾーンの冗長性がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="60cfd-107">Whether or not zone redundancy is supported for the edition.</span></span></param>
        <summary>
            <span data-ttu-id="60cfd-108">EditionCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-108">Initializes a new instance of the EditionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.EditionCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.EditionCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60cfd-109">エディション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-109">Gets the edition name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.EditionCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.EditionCapability.Status" />
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
            <span data-ttu-id="60cfd-110">エディションのステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-110">Gets the status of the edition.</span></span> <span data-ttu-id="60cfd-111">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="60cfd-111">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedServiceLevelObjectives">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt; SupportedServiceLevelObjectives { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt; SupportedServiceLevelObjectives" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.EditionCapability.SupportedServiceLevelObjectives" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedServiceLevelObjectives As IList(Of ServiceObjectiveCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedServiceLevelObjectives : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.EditionCapability.SupportedServiceLevelObjectives" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedServiceLevelObjectives")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60cfd-112">エディションのサポートされているサービス目標の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-112">Gets the list of supported service objectives for the edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.EditionCapability.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.EditionCapability.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60cfd-113">エディションのゾーンの冗長性がサポートされているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="60cfd-113">Gets whether or not zone redundancy is supported for the edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>