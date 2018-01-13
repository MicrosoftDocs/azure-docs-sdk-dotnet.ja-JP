<Type Name="MaxSizeCapability" FullName="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability">
  <TypeSignature Language="C#" Value="public class MaxSizeCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MaxSizeCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class MaxSizeCapability" />
  <TypeSignature Language="F#" Value="type MaxSizeCapability = class" />
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
            <span data-ttu-id="f77d4-101">データベースの最大サイズ制限。</span><span class="sxs-lookup"><span data-stu-id="f77d4-101">The maximum size limits for a database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaxSizeCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f77d4-102">MaxSizeCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f77d4-102">Initializes a new instance of the MaxSizeCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaxSizeCapability (long limit = 0, Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; unit = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 limit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; unit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.#ctor(System.Int64,System.Nullable{Microsoft.Azure.Management.Sql.Models.MaxSizeUnits},System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional limit As Long = 0, Optional unit As Nullable(Of MaxSizeUnits) = null, Optional status As Nullable(Of CapabilityStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MaxSizeCapability : int64 * Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; -&gt; Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" Usage="new Microsoft.Azure.Management.Sql.Models.MaxSizeCapability (limit, unit, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="limit"><span data-ttu-id="f77d4-103">データベースの最大サイズ (単位の ' unit' を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="f77d4-103">The maximum size of the database (see 'unit' for the units).</span></span></param>
        <param name="unit"><span data-ttu-id="f77d4-104">制限値で表される単位です。</span><span class="sxs-lookup"><span data-stu-id="f77d4-104">The units that the limit is expressed in.</span></span>
            <span data-ttu-id="f77d4-105">使用可能な値が含まれます: 'メガバイト'、'ギガバイト'、'テラバイト'、'単位からペタバイト単位'</span><span class="sxs-lookup"><span data-stu-id="f77d4-105">Possible values include: 'Megabytes', 'Gigabytes', 'Terabytes', 'Petabytes'</span></span></param>
        <param name="status"><span data-ttu-id="f77d4-106">最大サイズの機能の状態。</span><span class="sxs-lookup"><span data-stu-id="f77d4-106">The status of the maximum size capability.</span></span>
            <span data-ttu-id="f77d4-107">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="f77d4-107">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="f77d4-108">MaxSizeCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f77d4-108">Initializes a new instance of the MaxSizeCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Limit" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f77d4-109">データベースの最大サイズを取得 ('unit' ユニットを参照してください)。</span><span class="sxs-lookup"><span data-stu-id="f77d4-109">Gets the maximum size of the database (see 'unit' for the units).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Status" />
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
            <span data-ttu-id="f77d4-110">最大サイズの機能の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f77d4-110">Gets the status of the maximum size capability.</span></span> <span data-ttu-id="f77d4-111">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="f77d4-111">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As Nullable(Of MaxSizeUnits)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeUnits&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f77d4-112">制限値で表される単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="f77d4-112">Gets the units that the limit is expressed in.</span></span> <span data-ttu-id="f77d4-113">使用可能な値が含まれます: 'メガバイト'、'ギガバイト'、'テラバイト'、'単位からペタバイト単位'</span><span class="sxs-lookup"><span data-stu-id="f77d4-113">Possible values include: 'Megabytes', 'Gigabytes', 'Terabytes', 'Petabytes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>