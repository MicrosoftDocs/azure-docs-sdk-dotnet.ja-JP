<Type Name="OperationContext" FullName="Microsoft.WindowsAzure.Storage.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
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
            ストレージ サービスに対する要求操作のコンテキストを表し、その実行に関する追加のランタイム情報を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.OperationContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestID">
      <MemberSignature Language="C#" Value="public string ClientRequestID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestID As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestID : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
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
            取得またはクライアント要求 ID の設定
            </summary>
        <value>Id クライアント要求を含む文字列です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomUserAgent">
      <MemberSignature Language="C#" Value="public string CustomUserAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomUserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomUserAgent As String" />
      <MemberSignature Language="F#" Value="member this.CustomUserAgent : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
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
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>インスタンスごと (グローバル) SendingRequestEvent を使用して UserAgent 値が変更された場合、この値はオーバーライドされます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLogLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DefaultLogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.DefaultLogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の後に作成されるインスタンスに使用する既定のログ レベル、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />クラスです。
            </summary>
        <value>型の値<see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />どのイベントによってログに記録既定のインスタンスを指定する、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の終了時刻を設定します。
            </summary>
        <value>A<see cref="T:System.DateTime" />操作の終了時刻を示す値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRequestCompleted">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答が完全に受信および処理後に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalResponseReceived">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ダウンロードまたは応答がすべて処理する前に、サーバーから受信したときに発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRetrying">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRetrying" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRetrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRetrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRetrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求が再試行する前に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalSendingRequest">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalSendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalSendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalSendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalSendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求が署名する直前に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult LastResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult LastResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastResult As RequestResult" />
      <MemberSignature Language="F#" Value="member this.LastResult : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作で発生した最後の要求の結果を取得します。
            </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />最後の要求の結果を表すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.LogLevel LogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.LogLevel LogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property LogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.LogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のインスタンスに使用するログ記録レベル、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />クラスです。
            </summary>
        <value>型の値<see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />によってログに記録するイベントを指定する、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCompleted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.RequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event RequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.RequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.RequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答が完全に受信および処理後に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestResults As IList(Of RequestResult)" />
      <MemberSignature Language="F#" Value="member this.RequestResults : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;" Usage="Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在の操作によって作成された要求の結果のセットを設定します。
            </summary>
        <value><see cref="T:System.Collections.IList" />オブジェクトを含む<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />を現在の操作によって作成された要求の結果を表すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.ResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.ResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            またはダウンロードする処理前に、サービスから応答を受け取ったときに発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrying">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.Retrying" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event Retrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.Retrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.Retrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求が再試行する前に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendingRequest">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.SendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event SendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.SendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.SendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求が署名する直前に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の開始時刻を設定します。
            </summary>
        <value>A<see cref="T:System.DateTime" />操作の開始時刻を示す値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; UserHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; UserHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property UserHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.UserHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、プロキシやログ情報など、要求で追加のヘッダーを設定します。
            </summary>
        <value>A<see cref="T:System.Collections.Generic.IDictionary`2" />追加ヘッダー情報を含むオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>