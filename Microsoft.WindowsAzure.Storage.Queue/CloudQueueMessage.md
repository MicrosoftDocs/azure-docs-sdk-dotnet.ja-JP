<Type Name="CloudQueueMessage" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage">
  <TypeSignature Language="C#" Value="public sealed class CloudQueueMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudQueueMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudQueueMessage" />
  <TypeSignature Language="F#" Value="type CloudQueueMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Microsoft Azure Queue サービスのメッセージを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : byte[] -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content">バイト配列としてメッセージのコンテンツ。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />指定したバイト配列を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">テキストの文字列としてメッセージのコンテンツ。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />文字列を指定しています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string messageId, string popReceipt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string messageId, string popReceipt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageId As String, popReceipt As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string * string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage (messageId, popReceipt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="messageId">メッセージ ID を指定する文字列</param>
        <param name="popReceipt">Popreceipt トークンを表す文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />クラスの特定のメッセージ ID と popreceipt を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsBytes">
      <MemberSignature Language="C#" Value="public byte[] AsBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] AsBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsBytes As Byte()" />
      <MemberSignature Language="F#" Value="member this.AsBytes : byte[]" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの内容をバイト配列として取得します。
            </summary>
        <value>バイト配列としてメッセージのコンテンツ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsString">
      <MemberSignature Language="C#" Value="public string AsString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AsString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsString As String" />
      <MemberSignature Language="F#" Value="member this.AsString : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            文字列として、メッセージの内容を取得します。
            </summary>
        <value>メッセージの内容を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DequeueCount">
      <MemberSignature Language="C#" Value="public int DequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DequeueCount : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このメッセージがデキューされた回数を取得します。
            </summary>
        <value>このメッセージがデキューされた回数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの有効期限が切れる時刻を取得します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />メッセージの有効期限が切れる時刻を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージ ID を取得します
            </summary>
        <value>メッセージ ID を含む文字列</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; InsertionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; InsertionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InsertionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.InsertionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージがキューに追加された時刻を取得します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />メッセージがキューに追加された時刻を表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public static long MaxMessageSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの最大サイズをバイト単位で取得します。
            </summary>
        <value>メッセージの最大サイズ (バイト単位)。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfMessagesToPeek">
      <MemberSignature Language="C#" Value="public static int MaxNumberOfMessagesToPeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxNumberOfMessagesToPeek As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfMessagesToPeek : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一度にピークできるメッセージの最大数を取得します。
            </summary>
        <value>一度にピークできるメッセージの最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTimeToLive">
      <MemberSignature Language="C#" Value="public static TimeSpan MaxTimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype System.TimeSpan MaxTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxTimeToLive : TimeSpan" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージがキューに保持される時間の最大量を取得します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />メッセージがキューに保持される時間の最大量を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextVisibleTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; NextVisibleTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; NextVisibleTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextVisibleTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.NextVisibleTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージが表示される次に、時間を取得します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />メッセージが表示される次に、時刻を表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PopReceipt">
      <MemberSignature Language="C#" Value="public string PopReceipt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PopReceipt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PopReceipt As String" />
      <MemberSignature Language="F#" Value="member this.PopReceipt : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの popreceipt を取得します。
            </summary>
        <value>Popreceipt 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As Byte())" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : byte[] -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content">バイト配列としてメッセージのコンテンツ。</param>
        <summary>
            このメッセージの内容を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As String)" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : string -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">新しいメッセージの内容を含む文字列。</param>
        <summary>
            このメッセージの内容を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>