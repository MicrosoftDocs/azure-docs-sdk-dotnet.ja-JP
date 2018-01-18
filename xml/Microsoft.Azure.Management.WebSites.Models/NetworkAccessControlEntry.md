<Type Name="NetworkAccessControlEntry" FullName="Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry">
  <TypeSignature Language="C#" Value="public class NetworkAccessControlEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkAccessControlEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkAccessControlEntry" />
  <TypeSignature Language="F#" Value="type NetworkAccessControlEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f81f-101">ネットワーク アクセス制御エントリです。</span><span class="sxs-lookup"><span data-stu-id="8f81f-101">Network access control entry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkAccessControlEntry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f81f-102">NetworkAccessControlEntry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-102">Initializes a new instance of the NetworkAccessControlEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkAccessControlEntry (Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; action = null, string description = null, Nullable&lt;int&gt; order = null, string remoteSubnet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; action, string description, valuetype System.Nullable`1&lt;int32&gt; order, string remoteSubnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.#ctor(System.Nullable{Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction},System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional action As Nullable(Of AccessControlEntryAction) = null, Optional description As String = null, Optional order As Nullable(Of Integer) = null, Optional remoteSubnet As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry" Usage="new Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry (action, description, order, remoteSubnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="order" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="remoteSubnet" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="action"><span data-ttu-id="8f81f-103">アクション オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="8f81f-103">Action object.</span></span> <span data-ttu-id="8f81f-104">使用可能な値が含まれます: '許可'、'拒否'</span><span class="sxs-lookup"><span data-stu-id="8f81f-104">Possible values include: 'Permit', 'Deny'</span></span></param>
        <param name="description"><span data-ttu-id="8f81f-105">説明。</span><span class="sxs-lookup"><span data-stu-id="8f81f-105">Description.</span></span></param>
        <param name="order"><span data-ttu-id="8f81f-106">優先順位の順序です。</span><span class="sxs-lookup"><span data-stu-id="8f81f-106">Order of precedence.</span></span></param>
        <param name="remoteSubnet"><span data-ttu-id="8f81f-107">リモート サブネットです。</span><span class="sxs-lookup"><span data-stu-id="8f81f-107">Remote subnet.</span></span></param>
        <summary>
            <span data-ttu-id="8f81f-108">NetworkAccessControlEntry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-108">Initializes a new instance of the NetworkAccessControlEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As Nullable(Of AccessControlEntryAction)" />
      <MemberSignature Language="F#" Value="member this.Action : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AccessControlEntryAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f81f-109">取得またはアクション オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-109">Gets or sets action object.</span></span> <span data-ttu-id="8f81f-110">使用可能な値が含まれます: '許可'、'拒否'</span><span class="sxs-lookup"><span data-stu-id="8f81f-110">Possible values include: 'Permit', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f81f-111">説明取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-111">Gets or sets description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Order">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Order { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Order" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Order" />
      <MemberSignature Language="VB.NET" Value="Public Property Order As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Order : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.Order" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="order")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f81f-112">取得またはの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-112">Gets or sets order of precedence.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteSubnet">
      <MemberSignature Language="C#" Value="public string RemoteSubnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteSubnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.RemoteSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteSubnet As String" />
      <MemberSignature Language="F#" Value="member this.RemoteSubnet : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry.RemoteSubnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteSubnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f81f-113">取得またはリモートのサブネットを設定します。</span><span class="sxs-lookup"><span data-stu-id="8f81f-113">Gets or sets remote subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>