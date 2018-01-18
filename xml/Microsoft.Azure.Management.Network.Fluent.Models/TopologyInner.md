<Type Name="TopologyInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner">
  <TypeSignature Language="C#" Value="public class TopologyInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopologyInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TopologyInner" />
  <TypeSignature Language="F#" Value="type TopologyInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="66093-101">指定されたリソース グループのトポロジです。</span><span class="sxs-lookup"><span data-stu-id="66093-101">Topology of the specified resource group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66093-102">TopologyInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66093-102">Initializes a new instance of the TopologyInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyInner (string id = null, Nullable&lt;DateTime&gt; createdDateTime = null, Nullable&lt;DateTime&gt; lastModified = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; resources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; resources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional createdDateTime As Nullable(Of DateTime) = null, Optional lastModified As Nullable(Of DateTime) = null, Optional resources As IList(Of TopologyResource) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner (id, createdDateTime, lastModified, resources)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="createdDateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="66093-103">操作 id を表す GUID。</span><span class="sxs-lookup"><span data-stu-id="66093-103">GUID representing the operation id.</span></span></param>
        <param name="createdDateTime"><span data-ttu-id="66093-104">トポロジは、リソース グループの最初に作成されたときの日時。</span><span class="sxs-lookup"><span data-stu-id="66093-104">The datetime when the topology was initially created for the resource group.</span></span></param>
        <param name="lastModified"><span data-ttu-id="66093-105">トポロジが最後に変更された日時。</span><span class="sxs-lookup"><span data-stu-id="66093-105">The datetime when the topology was last modified.</span></span></param>
        <param name="resources">To be added.</param>
        <summary>
            <span data-ttu-id="66093-106">TopologyInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66093-106">Initializes a new instance of the TopologyInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedDateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedDateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.CreatedDateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedDateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedDateTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.CreatedDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdDateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66093-107">トポロジは、リソース グループの最初に作成されたときに、日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="66093-107">Gets the datetime when the topology was initially created for the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66093-108">操作 id を表す GUID を取得します。</span><span class="sxs-lookup"><span data-stu-id="66093-108">Gets GUID representing the operation id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66093-109">トポロジが最後に変更されたときに、日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="66093-109">Gets the datetime when the topology was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of TopologyResource)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>