<Type Name="LocationCapabilities" FullName="Microsoft.Azure.Management.Sql.Models.LocationCapabilities">
  <TypeSignature Language="C#" Value="public class LocationCapabilities" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocationCapabilities extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.LocationCapabilities" />
  <TypeSignature Language="VB.NET" Value="Public Class LocationCapabilities" />
  <TypeSignature Language="F#" Value="type LocationCapabilities = class" />
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
            <span data-ttu-id="fe596-101">場所のための機能です。</span><span class="sxs-lookup"><span data-stu-id="fe596-101">The capabilities for a location.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationCapabilities ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.LocationCapabilities.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe596-102">LocationCapabilities クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe596-102">Initializes a new instance of the LocationCapabilities class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationCapabilities (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt; supportedServerVersions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt; supportedServerVersions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.LocationCapabilities.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServerVersionCapability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedServerVersions As IList(Of ServerVersionCapability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.LocationCapabilities : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.LocationCapabilities" Usage="new Microsoft.Azure.Management.Sql.Models.LocationCapabilities (name, status, supportedServerVersions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedServerVersions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fe596-103">場所の名前。</span><span class="sxs-lookup"><span data-stu-id="fe596-103">The location name.</span></span></param>
        <param name="status"><span data-ttu-id="fe596-104">Azure SQL データベースの状態、場所をします。</span><span class="sxs-lookup"><span data-stu-id="fe596-104">Azure SQL Database's status for the location.</span></span>
            <span data-ttu-id="fe596-105">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="fe596-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedServerVersions"><span data-ttu-id="fe596-106">サポートされているサーバーのバージョンの一覧。</span><span class="sxs-lookup"><span data-stu-id="fe596-106">The list of supported server versions.</span></span></param>
        <summary>
            <span data-ttu-id="fe596-107">LocationCapabilities クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe596-107">Initializes a new instance of the LocationCapabilities class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.LocationCapabilities.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.LocationCapabilities.Name" />
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
            <span data-ttu-id="fe596-108">場所の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="fe596-108">Gets the location name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.LocationCapabilities.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.LocationCapabilities.Status" />
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
            <span data-ttu-id="fe596-109">場所の azure SQL データベースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="fe596-109">Gets azure SQL Database's status for the location.</span></span> <span data-ttu-id="fe596-110">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="fe596-110">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedServerVersions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt; SupportedServerVersions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt; SupportedServerVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.LocationCapabilities.SupportedServerVersions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedServerVersions As IList(Of ServerVersionCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedServerVersions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.LocationCapabilities.SupportedServerVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedServerVersions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServerVersionCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe596-111">サポートされているサーバーのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fe596-111">Gets the list of supported server versions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>