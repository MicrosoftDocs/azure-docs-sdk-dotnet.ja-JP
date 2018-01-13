<Type Name="Message" FullName="Microsoft.Azure.Devices.Message">
  <TypeSignature Language="C#" Value="public sealed class Message : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Message extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Message" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type Message = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            データ構造体は、iot Hub と対話するために使用されるメッセージを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            本文データのない既定のコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Message : byte[] -&gt; Microsoft.Azure.Devices.Message" Usage="new Microsoft.Azure.Devices.Message byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray">本文ストリームを形成するために使用するバイト配列</param>
        <summary>
            入力バイト配列を本文として使用するコンス トラクター
            </summary>
        <remarks>ユーザーは、メッセージを送信するときに、変更不可として入力バイト配列を扱う必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Message : System.IO.Stream -&gt; Microsoft.Azure.Devices.Message" Usage="new Microsoft.Azure.Devices.Message stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">本文ストリームとして使用されるストリーム。</param>
        <summary>
            本文ストリームとして引数のストリームを使用するコンス トラクターです。
            </summary>
        <remarks>ユーザーは、このコンス トラクターを使用する場合に、ストリームの破棄を所有すると想定されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ack">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeliveryAcknowledgement Ack { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement Ack" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.Ack" />
      <MemberSignature Language="VB.NET" Value="Public Property Ack As DeliveryAcknowledgement" />
      <MemberSignature Language="F#" Value="member this.Ack : Microsoft.Azure.Devices.DeliveryAcknowledgement with get, set" Usage="Microsoft.Azure.Devices.Message.Ack" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            消費量や、メッセージの有効期限がフィードバック キューへのデータを投稿する必要があるかどうかを示します
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Message Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Devices.Message Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Message" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.Devices.Message" Usage="message.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Message</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のイベント データ インスタンスの複製を使用します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">イベント データは既に破棄されている場合にスローします。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.Azure.Devices.Message.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテンツのエンコードのメッセージの種類を指定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Devices.Message.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージのコンテンツの種類を指定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Devices.Message.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの返信およびフィードバックの使用
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime CreationTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.CreationTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.Devices.Message.CreationTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            カスタムの日付プロパティがメッセージの発信者によって設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="message.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のイベント データ インスタンスを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiryTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiryTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ExpiryTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiryTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.Devices.Message.ExpiryTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [オプション]このメッセージを考慮する場合、時刻の有効期限が切れてください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="message.GetBodyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のイベント データ インスタンスの本文ストリームを返す
            </summary>
        <returns />
        <remarks>このメソッドは、1 回のみ呼び出すことができ、メソッドはスロー後<see cref="T:System.InvalidOperationException" />です。</remarks>
        <exception cref="T:System.InvalidOperationException">メソッドが呼び出された場合にスローします。</exception>
        <exception cref="T:System.ObjectDisposedException">イベント データは既に破棄されている場合にスローします。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="message.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このメソッドは、バイト配列として本文ストリームを返す
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">メソッドが呼び出された場合にスローします。</exception>
        <exception cref="T:System.ObjectDisposedException">イベント データは既に破棄されている場合にスローします。</exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.Devices.Message.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [必須]受信したメッセージの LockToken
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.Devices.Message.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [方法の 2 つの要求に必要]双方向通信を関連付けるために使用します。 形式: 文字列 (最大 128 文字長) ASCII 7 ビットの英数字文字を使用 
            + {'-', ':', '/', '\', '.', '+', '%', '_', '#', '*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}. URN の RFC は英数字以外の文字です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSchema">
      <MemberSignature Language="C#" Value="public string MessageSchema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.MessageSchema" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageSchema As String" />
      <MemberSignature Language="F#" Value="member this.MessageSchema : string with get, set" Usage="Microsoft.Azure.Devices.Message.MessageSchema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの内容のスキーマを指定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Devices.Message.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディクショナリを取得時に設定されているユーザーのプロパティのユーザーがデータを送信します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.Devices.Message.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [必須]メッセージの送信先
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Devices.Message.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [フィードバック メッセージで必須]デバイスのハブによって生成されたメッセージの配信元を指定するために使用します。 使用可能な値:"{ハブ名}/"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>