<Type Name="EventSubscriptionFilter" FullName="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter">
  <TypeSignature Language="C#" Value="public class EventSubscriptionFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventSubscriptionFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class EventSubscriptionFilter" />
  <TypeSignature Language="F#" Value="type EventSubscriptionFilter = class" />
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
            <span data-ttu-id="bc29d-101">イベント サブスクリプションのフィルター</span><span class="sxs-lookup"><span data-stu-id="bc29d-101">Filter for the Event Subscription</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.#ctor" />
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
            <span data-ttu-id="bc29d-102">EventSubscriptionFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-102">Initializes a new instance of the EventSubscriptionFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscriptionFilter (string subjectBeginsWith = null, string subjectEndsWith = null, System.Collections.Generic.IList&lt;string&gt; includedEventTypes = null, Nullable&lt;bool&gt; isSubjectCaseSensitive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subjectBeginsWith, string subjectEndsWith, class System.Collections.Generic.IList`1&lt;string&gt; includedEventTypes, valuetype System.Nullable`1&lt;bool&gt; isSubjectCaseSensitive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subjectBeginsWith As String = null, Optional subjectEndsWith As String = null, Optional includedEventTypes As IList(Of String) = null, Optional isSubjectCaseSensitive As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter : string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter (subjectBeginsWith, subjectEndsWith, includedEventTypes, isSubjectCaseSensitive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subjectBeginsWith" Type="System.String" />
        <Parameter Name="subjectEndsWith" Type="System.String" />
        <Parameter Name="includedEventTypes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isSubjectCaseSensitive" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="subjectBeginsWith"><span data-ttu-id="bc29d-103">リソースのパス プレフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する省略可能な文字列。</span><span class="sxs-lookup"><span data-stu-id="bc29d-103">An optional string to filter events for an event subscription based on a resource path prefix.</span></span>
            <span data-ttu-id="bc29d-104">この形式は、イベントの発行元によって異なります。</span><span class="sxs-lookup"><span data-stu-id="bc29d-104">The format of this depends on the publisher of the events.</span></span>
            <span data-ttu-id="bc29d-105">ワイルドカード文字は、このパスではサポートされません。</span><span class="sxs-lookup"><span data-stu-id="bc29d-105">Wildcard characters are not supported in this path.</span></span></param>
        <param name="subjectEndsWith"><span data-ttu-id="bc29d-106">リソース パスのサフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する省略可能な文字列。</span><span class="sxs-lookup"><span data-stu-id="bc29d-106">An optional string to filter events for an event subscription based on a resource path suffix.</span></span>
            <span data-ttu-id="bc29d-107">ワイルドカード文字は、このパスではサポートされません。</span><span class="sxs-lookup"><span data-stu-id="bc29d-107">Wildcard characters are not supported in this path.</span></span></param>
        <param name="includedEventTypes"><span data-ttu-id="bc29d-108">イベント サブスクリプションの一部である必要がある該当するイベントの種類の一覧。</span><span class="sxs-lookup"><span data-stu-id="bc29d-108">A list of applicable event types that need to be part of the event subscription.</span></span>
            <span data-ttu-id="bc29d-109">すべての種類のイベントをサブスクライブする場合は、"all"の文字列をこのリスト内の要素として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bc29d-109">If it is desired to subscribe to all event types, the string "all" needs to be specified as an element in this list.</span></span></param>
        <param name="isSubjectCaseSensitive"><span data-ttu-id="bc29d-110">フィルターの SubjectBeginsWith および SubjectEndsWith プロパティが大文字小文字を区別の方法で比較するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-110">Specifies if the SubjectBeginsWith and SubjectEndsWith properties of the filter should be compared in a case sensitive manner.</span></span></param>
        <summary>
            <span data-ttu-id="bc29d-111">EventSubscriptionFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-111">Initializes a new instance of the EventSubscriptionFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedEventTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IncludedEventTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IncludedEventTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IncludedEventTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludedEventTypes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IncludedEventTypes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IncludedEventTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedEventTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc29d-112">取得またはイベント サブスクリプションの一部である必要がある該当するイベントの種類の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-112">Gets or sets a list of applicable event types that need to be part of the event subscription.</span></span>
            <span data-ttu-id="bc29d-113">すべての種類のイベントをサブスクライブする場合は、"all"の文字列をこのリスト内の要素として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bc29d-113">If it is desired to subscribe to all event types, the string "all" needs to be specified as an element in this list.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSubjectCaseSensitive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSubjectCaseSensitive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSubjectCaseSensitive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IsSubjectCaseSensitive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSubjectCaseSensitive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSubjectCaseSensitive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.IsSubjectCaseSensitive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSubjectCaseSensitive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc29d-114">取得または設定は、フィルターの SubjectBeginsWith および SubjectEndsWith プロパティが大文字小文字を区別の方法で比較するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-114">Gets or sets specifies if the SubjectBeginsWith and SubjectEndsWith properties of the filter should be compared in a case sensitive manner.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectBeginsWith">
      <MemberSignature Language="C#" Value="public string SubjectBeginsWith { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectBeginsWith" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectBeginsWith" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectBeginsWith As String" />
      <MemberSignature Language="F#" Value="member this.SubjectBeginsWith : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectBeginsWith" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subjectBeginsWith")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc29d-115">取得またはリソースのパス プレフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する任意の文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-115">Gets or sets an optional string to filter events for an event subscription based on a resource path prefix.</span></span>
            <span data-ttu-id="bc29d-116">この形式は、イベントの発行元によって異なります。</span><span class="sxs-lookup"><span data-stu-id="bc29d-116">The format of this depends on the publisher of the events.</span></span>
            <span data-ttu-id="bc29d-117">ワイルドカード文字は、このパスではサポートされません。</span><span class="sxs-lookup"><span data-stu-id="bc29d-117">Wildcard characters are not supported in this path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectEndsWith">
      <MemberSignature Language="C#" Value="public string SubjectEndsWith { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectEndsWith" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectEndsWith" />
      <MemberSignature Language="VB.NET" Value="Public Property SubjectEndsWith As String" />
      <MemberSignature Language="F#" Value="member this.SubjectEndsWith : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter.SubjectEndsWith" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subjectEndsWith")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc29d-118">取得またはリソース パスのサフィックスに基づくイベント サブスクリプションのイベントをフィルター処理する任意の文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc29d-118">Gets or sets an optional string to filter events for an event subscription based on a resource path suffix.</span></span>
            <span data-ttu-id="bc29d-119">ワイルドカード文字は、このパスではサポートされません。</span><span class="sxs-lookup"><span data-stu-id="bc29d-119">Wildcard characters are not supported in this path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>