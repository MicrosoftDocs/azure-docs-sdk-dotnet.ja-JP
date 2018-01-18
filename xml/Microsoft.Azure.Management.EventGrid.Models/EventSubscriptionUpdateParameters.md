<Type Name="EventSubscriptionUpdateParameters" FullName="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters">
  <TypeSignature Language="C#" Value="public class EventSubscriptionUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventSubscriptionUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class EventSubscriptionUpdateParameters" />
  <TypeSignature Language="F#" Value="type EventSubscriptionUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd7cd-101">イベント サブスクリプションのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-101">Properties of the Event Subscription update</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.#ctor" />
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
            <span data-ttu-id="dd7cd-102">EventSubscriptionUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-102">Initializes a new instance of the EventSubscriptionUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionUpdateParameters (Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination = null, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter = null, System.Collections.Generic.IList&lt;string&gt; labels = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter, class System.Collections.Generic.IList`1&lt;string&gt; labels) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.#ctor(Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional destination As EventSubscriptionDestination = null, Optional filter As EventSubscriptionFilter = null, Optional labels As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters (destination, filter, labels)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="destination" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
        <Parameter Name="filter" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" />
        <Parameter Name="labels" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="destination"><span data-ttu-id="dd7cd-103">イベントがイベント サブスクリプションの配信にある転送先について説明します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-103">Information about the destination where events have to be delivered for the event subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="dd7cd-104">イベント サブスクリプションのフィルターに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-104">Information about the filter for the event subscription.</span></span></param>
        <param name="labels"><span data-ttu-id="dd7cd-105">ユーザーの一覧には、ラベルが定義されています。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-105">List of user defined labels.</span></span></param>
        <summary>
            <span data-ttu-id="dd7cd-106">EventSubscriptionUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-106">Initializes a new instance of the EventSubscriptionUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As EventSubscriptionDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd7cd-107">取得またはイベントがイベント サブスクリプションの配信にある転送先に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-107">Gets or sets information about the destination where events have to be delivered for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As EventSubscriptionFilter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd7cd-108">取得またはイベント サブスクリプションのフィルターに関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-108">Gets or sets information about the filter for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Labels">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Labels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Labels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Labels" />
      <MemberSignature Language="VB.NET" Value="Public Property Labels As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Labels : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters.Labels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="labels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd7cd-109">取得またはユーザー定義のラベルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="dd7cd-109">Gets or sets list of user defined labels.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>