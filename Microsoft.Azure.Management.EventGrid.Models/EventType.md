<Type Name="EventType" FullName="Microsoft.Azure.Management.EventGrid.Models.EventType">
  <TypeSignature Language="C#" Value="public class EventType : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventType extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventType" />
  <TypeSignature Language="VB.NET" Value="Public Class EventType&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type EventType = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8170f-101">トピック サブジェクトのイベントの種類</span><span class="sxs-lookup"><span data-stu-id="8170f-101">Event Type for a subject under a topic</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventType.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8170f-102">EventType クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8170f-102">Initializes a new instance of the EventType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventType (string id = null, string name = null, string type = null, string displayName = null, string description = null, string schemaUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string displayName, string description, string schemaUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventType.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional displayName As String = null, Optional description As String = null, Optional schemaUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventType : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventType" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventType (id, name, type, displayName, description, schemaUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="schemaUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8170f-103">リソースの完全修飾識別子</span><span class="sxs-lookup"><span data-stu-id="8170f-103">Fully qualified identifier of the resource</span></span></param>
        <param name="name"><span data-ttu-id="8170f-104">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="8170f-104">Name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="8170f-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="8170f-105">Type of the resource</span></span></param>
        <param name="displayName"><span data-ttu-id="8170f-106">イベントの種類の名前を表示します。</span><span class="sxs-lookup"><span data-stu-id="8170f-106">Display name of the event type.</span></span></param>
        <param name="description"><span data-ttu-id="8170f-107">イベントの種類の説明です。</span><span class="sxs-lookup"><span data-stu-id="8170f-107">Description of the event type.</span></span></param>
        <param name="schemaUrl"><span data-ttu-id="8170f-108">このイベントの種類のスキーマの Url です。</span><span class="sxs-lookup"><span data-stu-id="8170f-108">Url of the schema for this event type.</span></span></param>
        <summary>
            <span data-ttu-id="8170f-109">EventType クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8170f-109">Initializes a new instance of the EventType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
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
            <span data-ttu-id="8170f-110">取得またはイベントの種類の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="8170f-110">Gets or sets description of the event type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8170f-111">取得またはイベントの種類の表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="8170f-111">Gets or sets display name of the event type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaUrl">
      <MemberSignature Language="C#" Value="public string SchemaUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.SchemaUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaUrl As String" />
      <MemberSignature Language="F#" Value="member this.SchemaUrl : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.SchemaUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemaUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8170f-112">取得またはこのイベントの種類のスキーマの url を設定します。</span><span class="sxs-lookup"><span data-stu-id="8170f-112">Gets or sets url of the schema for this event type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>