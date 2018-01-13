<Type Name="ApplePushMessage" FullName="Microsoft.Azure.Mobile.Server.ApplePushMessage">
  <TypeSignature Language="C#" Value="public class ApplePushMessage : System.Collections.Generic.Dictionary&lt;string,object&gt;, Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ApplePushMessage extends System.Collections.Generic.Dictionary`2&lt;string, object&gt; implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplePushMessage&#xA;Inherits Dictionary(Of String, Object)&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type ApplePushMessage = class&#xA;    inherit Dictionary&lt;string, obj&gt;&#xA;    interface IPushMessage" />
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
            <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Apple Push Notification サービスを対象とする通知のペイロードを生成するのに役立ちます。 使用して通知を送信できる、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplePushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Apple Push Notification サービスを対象とする通知メッセージの作成を有効にするクラス。 メッセージに適切なプロパティを設定およびを通じて送信、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ApplePushMessage (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApplePushMessage : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.ApplePushMessage" Usage="new Microsoft.Azure.Mobile.Server.ApplePushMessage (info, context)" />
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
        <param name="info">A<see cref="T:System.Runtime.Serialization.SerializationInfo" />に関する情報を含む、<see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" />初期化されるようにします。</param>
        <param name="context">A<see cref="T:System.Runtime.Serialization.StreamingContext" />シリアル化ストリームのソースの変換先およびコンテキスト情報を示すです。</param>
        <summary>
            指定したシリアル化情報とストリーム コンテキストを使用して、<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplePushMessage (string alert, Nullable&lt;TimeSpan&gt; expiration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string alert, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; expiration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor(System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (alert As String, expiration As Nullable(Of TimeSpan))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApplePushMessage : string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Mobile.Server.ApplePushMessage" Usage="new Microsoft.Azure.Mobile.Server.ApplePushMessage (alert, expiration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="alert" Type="System.String" />
        <Parameter Name="expiration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="alert">通知の警告メッセージです。</param>
        <param name="expiration">A<see cref="T:System.TimeSpan" />現在の時刻の基準としました。 有効期間の最後に、通知が有効では不要になったと破棄することができます。 この値が null 以外の場合は、APNs は通知の格納され、少なくとも 1 回通知の配信を試みます。 通知がすぐに有効期限し、APNs 格納しないように通知まったくを示すために null を指定します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />クラスに、指定された<paramref name="alert" />メッセージと省略可能な<paramref name="expiration" />通知のです。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Aps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.ApsProperties Aps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.ApsProperties Aps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.Aps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Aps As ApsProperties" />
      <MemberSignature Language="F#" Value="member this.Aps : Microsoft.Azure.Mobile.Server.ApsProperties" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.Aps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.ApsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> の <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; Expiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; Expiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.Expiration" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiration As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.Expiration : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.Expiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定または通知の有効期間を取得します。 有効期間の最後に、通知が有効では不要になったと破棄することができます。 この値が null 以外の場合は、APNs は通知の格納され、少なくとも 1 回通知の配信を試みます。 通知がすぐに有効期限し、APNs 格納しないように通知まったくを示すために null を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPayload">
      <MemberSignature Language="C#" Value="public string JsonPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.JsonPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPayload As String" />
      <MemberSignature Language="F#" Value="member this.JsonPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.JsonPayload" />
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
            初期化することによって、通知を作成する代わりに、<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />を直接変更されず、通知ハブに送信される完全な JSON 表現を提供することはできます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applePushMessage.ToString " />
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
            この JSON でエンコードされた表現を提供します。<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /></summary>
        <returns>JSON でエンコードされた文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>