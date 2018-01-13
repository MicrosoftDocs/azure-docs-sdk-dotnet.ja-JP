<Type Name="CorrelationFilter" FullName="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter">
  <TypeSignature Language="C#" Value="public class CorrelationFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CorrelationFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CorrelationFilter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            相関関係のフィルター式を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CorrelationFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId = null, string messageId = null, string to = null, string replyTo = null, string label = null, string sessionId = null, string replyToSessionId = null, string contentType = null, Nullable&lt;bool&gt; requiresPreprocessing = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId, string messageId, string to, string replyTo, string label, string sessionId, string replyToSessionId, string contentType, valuetype System.Nullable`1&lt;bool&gt; requiresPreprocessing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional correlationId As String = null, Optional messageId As String = null, Optional to As String = null, Optional replyTo As String = null, Optional label As String = null, Optional sessionId As String = null, Optional replyToSessionId As String = null, Optional contentType As String = null, Optional requiresPreprocessing As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter : string * string * string * string * string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter" Usage="new Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter (correlationId, messageId, to, replyTo, label, sessionId, replyToSessionId, contentType, requiresPreprocessing)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="to" Type="System.String" />
        <Parameter Name="replyTo" Type="System.String" />
        <Parameter Name="label" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="replyToSessionId" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="requiresPreprocessing" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="correlationId">関連付けの識別子</param>
        <param name="messageId">メッセージの識別子。</param>
        <param name="to">送信先アドレス</param>
        <param name="replyTo">返信するキューのアドレス</param>
        <param name="label">アプリケーション固有のラベル。</param>
        <param name="sessionId">セッションの識別子です。</param>
        <param name="replyToSessionId">返信するセッション識別子です。</param>
        <param name="contentType">メッセージのコンテンツの種類。</param>
        <param name="requiresPreprocessing">前処理を規則の操作が必要かどうかを示す値です。</param>
        <summary>
            CorrelationFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメッセージのコンテンツの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の相関関係の識別子。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="label")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーション固有のラベルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメッセージの識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replyTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはに返信するキューのアドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replyToSessionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定に返信するセッション識別子。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresPreprocessing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresPreprocessing As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requiresPreprocessing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプリプロセスを規則の操作が必要かどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sessionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはセッション識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="to")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信するアドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>