<Type Name="EventModel" FullName="Microsoft.Azure.Management.ContainerInstance.Models.EventModel">
  <TypeSignature Language="C#" Value="public class EventModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventModel extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.EventModel" />
  <TypeSignature Language="VB.NET" Value="Public Class EventModel" />
  <TypeSignature Language="F#" Value="type EventModel = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="74fcb-101">コンテナーのグループまたはコンテナー インスタンス イベント。</span><span class="sxs-lookup"><span data-stu-id="74fcb-101">A container group or container instance event.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventModel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="74fcb-102">EventModel クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-102">Initializes a new instance of the EventModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventModel (Nullable&lt;int&gt; count = null, Nullable&lt;DateTime&gt; firstTimestamp = null, Nullable&lt;DateTime&gt; lastTimestamp = null, string name = null, string message = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; count, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; firstTimestamp, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastTimestamp, string name, string message, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.#ctor(System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Integer) = null, Optional firstTimestamp As Nullable(Of DateTime) = null, Optional lastTimestamp As Nullable(Of DateTime) = null, Optional name As String = null, Optional message As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.EventModel : Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.EventModel" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.EventModel (count, firstTimestamp, lastTimestamp, name, message, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="firstTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="74fcb-103">イベントの数。</span><span class="sxs-lookup"><span data-stu-id="74fcb-103">The count of the event.</span></span></param>
        <param name="firstTimestamp"><span data-ttu-id="74fcb-104">最も早い日付時刻は、イベントを記録します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-104">The date-time of the earliest logged event.</span></span></param>
        <param name="lastTimestamp"><span data-ttu-id="74fcb-105">最新のログに記録されたイベントの日付時刻。</span><span class="sxs-lookup"><span data-stu-id="74fcb-105">The date-time of the latest logged event.</span></span></param>
        <param name="name"><span data-ttu-id="74fcb-106">イベントの名前です。</span><span class="sxs-lookup"><span data-stu-id="74fcb-106">The event name.</span></span></param>
        <param name="message"><span data-ttu-id="74fcb-107">イベント メッセージ。</span><span class="sxs-lookup"><span data-stu-id="74fcb-107">The event message.</span></span></param>
        <param name="type"><span data-ttu-id="74fcb-108">イベントの種類。</span><span class="sxs-lookup"><span data-stu-id="74fcb-108">The event type.</span></span></param>
        <summary>
            <span data-ttu-id="74fcb-109">EventModel クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-109">Initializes a new instance of the EventModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74fcb-110">取得またはイベントの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-110">Gets or sets the count of the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FirstTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FirstTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.FirstTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property FirstTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FirstTimestamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.FirstTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="firstTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74fcb-111">取得または最も古いログに記録されたイベントの日付/時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-111">Gets or sets the date-time of the earliest logged event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.LastTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property LastTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastTimestamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.LastTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74fcb-112">取得または最新のログに記録されたイベントの日付/時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-112">Gets or sets the date-time of the latest logged event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74fcb-113">取得またはイベント メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-113">Gets or sets the event message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="74fcb-114">取得またはイベントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-114">Gets or sets the event name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.EventModel.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="74fcb-115">取得またはイベントの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="74fcb-115">Gets or sets the event type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>