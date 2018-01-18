<Type Name="GooglePushMessage" FullName="Microsoft.Azure.Mobile.Server.GooglePushMessage">
  <TypeSignature Language="C#" Value="public class GooglePushMessage : System.Collections.Generic.Dictionary&lt;string,object&gt;, Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit GooglePushMessage extends System.Collections.Generic.Dictionary`2&lt;string, object&gt; implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class GooglePushMessage&#xA;Inherits Dictionary(Of String, Object)&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type GooglePushMessage = class&#xA;    inherit Dictionary&lt;string, obj&gt;&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Object&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Object</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2240:ImplementISerializableCorrectly", Justification="Expiration is not intended for serialization")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This describes a message.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="23a8e-101"><see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> Chrome (GCM) のターゲット Google Cloud Messaging 通知のペイロードを生成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="23a8e-101">The <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> helps generating a notification payload targeting Google Cloud Messaging for Chrome (GCM).</span></span> <span data-ttu-id="23a8e-102">使用して通知を送信できる、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="23a8e-102">Notifications can be sent using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GooglePushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.GooglePushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-103">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> Chrome (GCM) のターゲット Google Cloud Messaging 通知メッセージの作成を有効にするクラス。メッセージに適切なプロパティを設定およびを通じて送信、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /></span><span class="sxs-lookup"><span data-stu-id="23a8e-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> class enabling creation of a notification message targeting Google Cloud Messaging for Chrome (GCM).Set the appropriate properties on the message and submit through the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GooglePushMessage (System.Collections.Generic.IDictionary&lt;string,string&gt; data, Nullable&lt;TimeSpan&gt; timeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; data, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.GooglePushMessage.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (data As IDictionary(Of String, String), timeToLive As Nullable(Of TimeSpan))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.GooglePushMessage : System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Mobile.Server.GooglePushMessage" Usage="new Microsoft.Azure.Mobile.Server.GooglePushMessage (data, timeToLive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="data" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="data"></param>
        <param name="timeToLive"><span data-ttu-id="23a8e-104">A<see cref="T:System.TimeSpan" />現在の時刻の基準としました。</span><span class="sxs-lookup"><span data-stu-id="23a8e-104">A <see cref="T:System.TimeSpan" /> relative to the current time.</span></span> <span data-ttu-id="23a8e-105">このパラメーターの値は 0 から 2,419,200 秒 (28 日) までの期間である必要があり、対象の GCM は保存して再試行して、メッセージを配信の最大期間に対応します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-105">The value of this parameter must be a duration from 0 to 2,419,200 seconds (28 days), and it corresponds to the maximum period of time for which GCM will store and try to deliver the message.</span></span> <span data-ttu-id="23a8e-106">4 週間の最大期間にこのフィールドの既定値が含まれていないように要求します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-106">Requests that don't contain this field default to the maximum period of 4 weeks.</span></span></param>
        <summary>
            <span data-ttu-id="23a8e-107">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> 、特定のセットを持つクラス<paramref name="data" />パラメーターと省略可能な<paramref name="timeToLive" />します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> class with a given set of <paramref name="data" /> parameters and an optional <paramref name="timeToLive" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected GooglePushMessage (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.GooglePushMessage.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.GooglePushMessage : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.GooglePushMessage" Usage="new Microsoft.Azure.Mobile.Server.GooglePushMessage (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="23a8e-108">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" />初期化されるようにします。</span><span class="sxs-lookup"><span data-stu-id="23a8e-108">A <see cref="T:System.Runtime.Serialization.SerializationInfo" /> containing information about the <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> to be initialized.</span></span></param>
        <param name="context"><span data-ttu-id="23a8e-109">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</span><span class="sxs-lookup"><span data-stu-id="23a8e-109">A <see cref="T:System.Runtime.Serialization.StreamingContext" /> that indicates the source destination and context information of a serialized stream.</span></span></param>
        <summary>
            <span data-ttu-id="23a8e-110">指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> class with the specified serialization information and streaming context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollapseKey">
      <MemberSignature Language="C#" Value="public string CollapseKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollapseKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.GooglePushMessage.CollapseKey" />
      <MemberSignature Language="VB.NET" Value="Public Property CollapseKey As String" />
      <MemberSignature Language="F#" Value="member this.CollapseKey : string with get, set" Usage="Microsoft.Azure.Mobile.Server.GooglePushMessage.CollapseKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-111">折りたたみキーは、オフラインのとき、デバイス、最新のメッセージのみを取得、クライアントに送信されるようにメッセージと同様のグループを折りたたむに使用される任意の文字列です。</span><span class="sxs-lookup"><span data-stu-id="23a8e-111">A collapse key is an arbitrary string that is used to collapse a group of like messages when the device is offline, so that only the most recent message gets sent to the client.</span></span> <span data-ttu-id="23a8e-112">たとえば、「新規メール」、"使用できる更新"のようにします。</span><span class="sxs-lookup"><span data-stu-id="23a8e-112">For example, "New mail", "Updates available", and so on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.GooglePushMessage.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Data : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Mobile.Server.GooglePushMessage.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-113">コレクションまたはメッセージに含める名前と値プロパティです。</span><span class="sxs-lookup"><span data-stu-id="23a8e-113">A collection or name-value properties to include in the message.</span></span> <span data-ttu-id="23a8e-114">プロパティは単純型である必要があります、入れ子にできませんなどです。</span><span class="sxs-lookup"><span data-stu-id="23a8e-114">Properties must be simple types, i.e. they can not be nested.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DelayWhileIdle">
      <MemberSignature Language="C#" Value="public bool DelayWhileIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DelayWhileIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.GooglePushMessage.DelayWhileIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property DelayWhileIdle As Boolean" />
      <MemberSignature Language="F#" Value="member this.DelayWhileIdle : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.GooglePushMessage.DelayWhileIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-115">デバイスがアイドル状態に、メッセージを配信するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-115">Indicates whether the message should be delivered while the device is idle.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPayload">
      <MemberSignature Language="C#" Value="public string JsonPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.GooglePushMessage.JsonPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPayload As String" />
      <MemberSignature Language="F#" Value="member this.JsonPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.GooglePushMessage.JsonPayload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-116">初期化することによって、通知を作成する代わりに、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" />を直接変更されず、通知ハブに送信される完全な JSON 表現を提供することはできます。</span><span class="sxs-lookup"><span data-stu-id="23a8e-116">As an alternative to building the notification by initializing the <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> directly, it is possible to provide a complete JSON representation which will be sent to the Notification Hub unaltered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLiveInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeToLiveInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeToLiveInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.GooglePushMessage.TimeToLiveInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLiveInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeToLiveInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.GooglePushMessage.TimeToLiveInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-117">Time to Live (TTL) プロパティ、送信者にメッセージの最大有効期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-117">The Time to Live (TTL) property lets the sender specify the maximum lifespan of a message.</span></span> <span data-ttu-id="23a8e-118">このパラメーターの値は 0 から 2,419,200 (秒単位) の期間である必要があり、対象の GCM は保存して再試行して、メッセージを配信の最大期間に対応します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-118">The value of this parameter must be a duration from 0 to 2,419,200 seconds, and it corresponds to the maximum period of time for which GCM will store and try to deliver the message.</span></span> <span data-ttu-id="23a8e-119">4 週間の最大期間にこのフィールドの既定値が含まれていないように要求します。</span><span class="sxs-lookup"><span data-stu-id="23a8e-119">Requests that don't contain this field default to the maximum period of 4 weeks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.GooglePushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="googlePushMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23a8e-120">この JSON でエンコードされた表現を提供します。<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /></span><span class="sxs-lookup"><span data-stu-id="23a8e-120">Provides a JSON encoded representation of this <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /></span></span></summary>
        <returns><span data-ttu-id="23a8e-121">JSON でエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="23a8e-121">A JSON encoded string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>