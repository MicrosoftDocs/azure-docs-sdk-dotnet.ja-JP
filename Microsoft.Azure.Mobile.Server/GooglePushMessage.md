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
            <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> Chrome (GCM) のターゲット Google Cloud Messaging 通知のペイロードを生成するのに役立ちます。 使用して通知を送信できる、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />クラスです。
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> Chrome (GCM) のターゲット Google Cloud Messaging 通知メッセージの作成を有効にするクラス。メッセージに適切なプロパティを設定およびを通じて送信、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /></summary>
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
        <param name="timeToLive">A<see cref="T:System.TimeSpan" />現在の時刻の基準としました。 このパラメーターの値は 0 から 2,419,200 秒 (28 日) までの期間である必要があり、対象の GCM は保存して再試行して、メッセージを配信の最大期間に対応します。 4 週間の最大期間にこのフィールドの既定値が含まれていないように要求します。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> 、特定のセットを持つクラス<paramref name="data" />パラメーターと省略可能な<paramref name="timeToLive" />します。
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
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /> クラスの新しいインスタンスを初期化します。
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
            折りたたみキーは、オフラインのとき、デバイス、最新のメッセージのみを取得、クライアントに送信されるようにメッセージと同様のグループを折りたたむに使用される任意の文字列です。 たとえば、「新規メール」、"使用できる更新"のようにします。
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
            コレクションまたはメッセージに含める名前と値プロパティです。 プロパティは単純型である必要があります、入れ子にできませんなどです。
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
            デバイスがアイドル状態に、メッセージを配信するかどうかを示します。
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
            初期化することによって、通知を作成する代わりに、<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" />を直接変更されず、通知ハブに送信される完全な JSON 表現を提供することはできます。
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
            Time to Live (TTL) プロパティ、送信者にメッセージの最大有効期間を指定します。 このパラメーターの値は 0 から 2,419,200 (秒単位) の期間である必要があり、対象の GCM は保存して再試行して、メッセージを配信の最大期間に対応します。 4 週間の最大期間にこのフィールドの既定値が含まれていないように要求します。
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
            この JSON でエンコードされた表現を提供します。<see cref="T:Microsoft.Azure.Mobile.Server.GooglePushMessage" /></summary>
        <returns>JSON でエンコードされた文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>